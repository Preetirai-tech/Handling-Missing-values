# Complete Case Analysis for Data Science Job Dataset

In this analysis, we utilized complete case analysis (CCA) to handle missing values in the "Data Science Job" dataset obtained from Kaggle. CCA involves excluding rows with missing values and analyzing only the subset of complete cases.

## Dataset

The "Data Science Job" dataset contains information about data science job postings, including various attributes such as enrollee_id, city, city_development_index, gender, relevent_experience, enrolled_university, education_level, education_level, experience, company_size, company_size, training_hours and target.

## Missing Values Assessment

Before performing CCA, we assessed the missingness pattern in the dataset. It is important to note the following assumptions related to CCA:

1. Missing Completely at Random (MCAR): We assume that the missingness of values in this dataset is completely random, meaning that the probability of missingness is unrelated to the observed or unobserved variables. We acknowledge that this assumption may impact the validity of our analysis.

2. Missingness Independent of the Outcome (MIO): We assume that the missingness of values is independent of the variables of interest in the dataset. It is essential to consider that any relationship between missingness and the variables being analyzed may introduce bias in the results.

3. No Differential Missingness: We assume that the missingness is not systematically related to specific subgroups or characteristics within the dataset. It is important to be cautious as differential missingness could potentially lead to biased results.

## Columns Safe for Complete Case Analysis (CCA)

Based on our assessment, the following columns are considered safe for performing CCA:

- city_development_index
- enrolled_university
- education_level
- experience
- training_hours

These columns have negligible percentage (ie < 5) of missing values, making them suitable for the complete case analysis approach.

## Conclusion

In this analysis, we performed complete case analysis (CCA) on the "Data Science Job" dataset to handle missing values. We acknowledge the assumptions of CCA, including MCAR, MIO, and no differential missingness. By documenting these assumptions, we emphasize the need to interpret the results with caution, considering any potential bias or limitations introduced by the missing data handling technique.


