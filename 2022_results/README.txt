This is to explain what is in the folder I'm providing: 

- Male Analysis 2022.ipynb => notebook containing the required analysis for male patients
- Female Analysis 2022.ipynb => notebook containign the required anlaysis for female patients 

- 2022_results/rules_male_full.csv => dataset containing all the rules extracted for males
- 2022_results/rules_female_full.csv => dataset containing all the rules extracted for females 

For each rule in the previous two files we have: 
    - LHS of the rule (genes composing the rule) 
    - RHS of the rule (grading = 0 corresponding to mild symptoms, grading = 1 corresponding to severe symptoms)
    - support of the rule
    - confidence of the rule 
    - lift of the rule 
    - support count of the rule
    - coverage of the rule
    - p-value of the rule
    
- 2022_results/corrispondenza_paziente_regole_M.csv => dataset containing for each patient the rules he satisfies
- 2022_results/corrispondenza_paziente_regole_F.csv => dataset containing for each patient the rules she satisfies

- Data/relevant genes in males.csv => dataset containing infos related to the relevant genes for males (self explanatory columns) 
- Data/relevant genes in females.csv => dataset containing infos related to the relevant genes for females (self explanatory columns)

- Data/All_Male_bool_index.csv => dataset containing male patients, their genetic mutations and their grading (mild/severe)
- Data/All_Male_bool.csv => similar dataset to the previous one (I honestly do not recall why I used two files :(
- Data/All_Female_bool_index.csv => dataset containing female patients, their genetic mutations and their grading (mild/severe)
- Data/All_Female_bool.csv => similar dataset to the previous one (I honestly do not recall why I used two files :(

