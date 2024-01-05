# Predicting-Diabetes-with-BRFSS

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses.

Diabetes is a chronic health condition that affects the transformation of food into energy for the body. The disease exists as two major types:

Type I Diabetes - Autoimmune condition, body attacks insulin producing cells in pancreas, lack of insulin produced to regulate blood sugar
Type II Diabetes - Pancreas is able to produce insulin, yet cells build resistance to insulin

The presumption around the types of diabetes are often linked by genetic vs environmental factors. Type II diabetes is heavily linked with obesity and is generalized to be acquired through lifestyle factors. Whereas Type I diabetes has a significant genetic link with hereditary effects.

Nonetheless, both types of diabetes are affected by both genetics and the individuals environment but this was an important consideration to note due to the limitations of the BRFSS survey data. Many of the questions answered from this survey are lifestyle based, and do not attribute to a persons genetic factors that may play a role for the presence of the disease, diabetes.

## Research Question
Can we accurately predict an individuals disease status (diabetes, pre diabetes, or no diabetes) using data derived from the BRFSS questionnare?

To answer this question we can explore various machine learning models and test them on our large dataset
