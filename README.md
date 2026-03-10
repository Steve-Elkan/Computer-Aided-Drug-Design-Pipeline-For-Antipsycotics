# Computer-Aided-Drug-Design-Pipeline-For-Antipsychotics
Computational identification and evaluation of Antipsychotic drugs for severe psychiatric conditions like schizophrenia and bipolar disorder. 

Background
This project aims to develop a potential atypical antipsychotic to treat psychosis related symptoms common in several mood disorders.
An Atypical antipsychotic differs from a typical antipsychotic in that it also focuses on blocking certain serotonin receptors instead of just dopamine receptors. They are often preferred over typical antipsychotics because they reduce the risk of movement related side effects such as Parkinsonism and Tardive Dyskinesia.

Antipsychotics can be used to treat positive, negative and cognitive symptoms of psychosis.
Positive symptoms include hallucinations (visual and auditory), delusions and disorganised speech/thoughts.
Negative symptoms include social withdrawal and lack of emotion 
Cognitive symptoms like memory loss, reduced mental functioning and low attention span.
These drugs also reduce the chance of repeat episodes of psychosis or mania.

Disorders treated with this medication include:
Schizophrenia and schizoaffective disorder for acute episodes and reducing relapse rates
Bipolar Disorder for acute episodes of mania often used along side mood stabilisers
Major Depressive Disorder for patients with psychotic features in depression used along with antidepressants.
Other conditions like Tourette syndrome, dementia, as well as some personality and anxiety disorders.

Target
For this project we will be targeting 5-HT2A serotonin receptor and trying to block it. G-protein coupled receptor for 5-hydroxytryptamine (serotonin). Also functions as a receptor for various drugs and psychoactive substances, including mescaline, psilocybin, 1-(2,5-dimethoxy-4-iodophenyl)-2-aminopropane (DOI) and lysergic acid diethylamide (LSD). Ligand binding causes a conformation change that triggers signaling via guanine nucleotide-binding proteins (G proteins) and modulates the activity of downstream effectors. Affects neural activity, perception, cognition and mood. Plays a role in the regulation of behavior, including responses to anxiogenic situations and psychoactive substances. Plays a role in intestinal smooth muscle contraction, and may play a role in arterial vasoconstriction.

Dataset 
For this project we will first acquire known actives from ChEMBL`s targets database. For target search making sure it belongs to homo sapiens and is a single protein. The targets IDs are CHEMBL224, P28223 and 6A93. Then we download a tsv dataset for its IC50 actives.
Using KNIME for developing a pipeline to clean the raw dataset. The KNIME nodes all have comments and are self explanatory. Favourable criteria and pIC50 were taken from previous assignment guidelines. Finally we get a clean processed dataset in CSV form
