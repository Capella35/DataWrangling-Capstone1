# DataWrangling-Capstone1
Data Cleaning Process: 
-Columns having same values for all employers were removed from the data set. 
    Standard hours: As it was always 80 for all employees this columns was useless.
    Over18 : Yes for all
    EmployeeCount: This column was not useful during the study.
- The Attrition was moved to the first column to make easier slicing for next works. 
Pandas' .head(), .info(), shape  methods were used for EDA. 
Unique columns were checked by nuinique() function in the data to find which are categorical.
Following columns are labeled: 'Education', 'EnvironmentSatisfaction', 'JobInvolvement', 'JobSatisfaction', 'PerformanceRating', 'RelationshipSatisfaction' and 'WorkLifeBalance'. 
'Age' columns renamed to prevent unwanted symbols infront of 'Age' 
By using the pandas get_dummies() function to create dummy variables from the df DataFrame for 'Attrition' as 'Attrition_r'
