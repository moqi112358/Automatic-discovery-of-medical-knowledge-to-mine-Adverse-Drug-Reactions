# Knowledge graph for Adverse Drug Reactions

In our project, we built a knowledge graph for drugs and their adverse reactions that have been reported. The knowledge graph will explain the possible reasons why a drug causes a side effect.
 
The knowledge graph contains four types of nodes: drug, adverse reactions, medical subject headings retrieved from the MeSH database, GO terms database. We extract the reported drug-adverse reaction pair from FDA database, and mine knowledge for each edge from PubMed literature database. Finally, we use the networks to give a possible explanation of the relation between drugs and adverse reactions.
 
We also built a web application to provide a visualization and better interactivity with users. It takes drug and adverse reaction pairs as input and returns a knowledge graph contains interconnected nodes, which stand for medical terms, to explain the potential relationship between the drug and the adverse reaction. Hopefully, this project will be a useful tool for patient, doctors and drug manufacturers for a quick reference.

### Project Implementation

1. Mined adverse drug reactions from FDA Adverse Event Reporting System (FAERS)
2. Built a healthcare information system which mined drug side effects from different online health forums and social networks using a probabilistic topic model based on PLSA
3. Built a knowledge graph for drugs which contained three types of nodes: drug, adverse reactions and medical subject headings from the MeSH database. Mined knowledge for each edge from PubMed literature data. Made a possible explanation of the relation between drugs and adverse drug reactions using the knowledge graph
4. Built a web application to provide a visualization and better interactivity with users. It takes drug and adverse reaction pairs as input and returns a knowledge graph contains interconnected nodes, which stand for medical terms, to explain the potential relationship between the drug and the adverse reaction. Hopefully, this project will be a useful tool for patient, doctors and drug manufacturers for a quick reference.
