# Alzheimer’s Disease Analysis Using Regression Models 🧠

## Project Summary 📄

This analysis aims to estimate various factors of Alzheimer’s disease using regression models in R. The primary objectives include:

- Designing a linear regression model for hypothesis testing.
- Investigating the relationship between gender and Alzheimer’s disease.
- Identifying significant independent variables for Alzheimer’s disease through multiple linear regression.

## Dataset and Sources 📊

Data for this study was obtained from OASIS (Open Access Series of Imaging Studies), a cross-sectional dataset available on Kaggle. The dataset comprises 436 rows and 12 variables, focusing on aspects like gender, age, education level, socioeconomic status, clinical dementia rating, and normalized whole brain volume.

## Methodology 🔍

### Hypothesis Testing:

1. **Gender and Alzheimer’s Disease**: Examining if there's a significant difference in dementia between males and females.
2. **Multiple Linear Regression**: Identifying the most significant independent variables affecting Alzheimer’s disease.

### Data Analysis Steps:

- Data loading and transformation using R.
- Handling missing values through various imputation techniques.
- Employing two-sample t-tests and multiple regression analysis.
- Analyzing the effect of missing data on the study results.

## Key Findings 📌

- The study found no substantial evidence to suggest a significant gender-based difference in dementia.
- Multiple linear regression highlighted specific variables that significantly impact Alzheimer’s disease, though the influence of some factors like education level and socioeconomic status was found to be minimal.

## Limitations and Future Directions 🚧

- The presence of missing data, particularly in education and socioeconomic status, poses challenges.
- Future research could focus on expanding the dataset and exploring other potential risk factors for Alzheimer’s disease.

## References and Resources 📚

- Data Source: [Kaggle - MRI and Alzheimer's Dataset](https://www.kaggle.com/jboysen/mri-and-alzheimers?select=oasis_longitudinal.csv)
- OASIS Project: [OASIS Brains](https://www.oasis-brains.org/#data)
- Methodological Reference: Van Buuren, S., & Groothuis-Oudshoorn, K. (2011). MICE: Multivariate Imputation by Chained Equations in R. Journal of Statistical Software, 45(3), 1–67. [DOI](https://doi.org/10.18637/jss.v045.i03)




