My R&D task on detecting PHI elements.

The libray used is SciSpaCy. A python package containing spaCy models for processing, biomedical, scientific, or clinical data. I will be using the en_ner_bc5cdr_md model. This model is trained on the BC5CDR Corpus which consists of 1500 PubMed articles with 4409 annotated chemicals, 5818 diseases and 3116 chemical disease interactions.

The following PHI elements this notebook covers is: 
 * patient diagnosis [6] 
 * treatment plans [7] (only detects medication NOT activities/actions)
 * patient blood test results [10] 
 * Prescribed medications[12]
 * pre-existing condition info [13]
 * mental health information  [14]
 