# FDADrugLabel_to_ICD10


- **Description**: Write a program that maps FDA drug labeling to related diagnoses

- **Drug Class Analyzed** - Recombinant Human Growth Hormone - abuse of HGH

- **Diagnosis Information used**:
    - Int'l Classification of Diseases (#10)

- **Drug Data**: 
    - National Drug Code (NDC)
    - FDA Label (openFDA API)

- Program takes two input files, one for drugs, other for diagnoses
    - Takes the drug file, pulls back label info from openFDA API

- Label and Diagnoses are then put into N-grams sets
     - Intersection of sets is shared wording between drug and diagnoses
