Research and development on detecting PHI elements wih Natrual Language Processing (NLP).

The libray used is SciSpaCy. A python package containing spaCy models for processing, biomedical, scientific, or clinical data. The specific model is the en_ner_bc5cdr_md. This model is trained on the BC5CDR Corpus which consists of 1500 PubMed articles with 4409 annotated chemicals, 5818 diseases and 3116 chemical disease interactions.

The following PHI elements this notebook covers is: 
 * patient diagnosis
 * treatment plans (only detects medication NOT activities/actions)
 * patient blood test results 
 * Prescribed medications
 * pre-existing condition info
 * mental health information 
 
