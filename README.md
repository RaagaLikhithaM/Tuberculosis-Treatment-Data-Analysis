# Tuberculosis-Treatment-Data-Analysis
This repository contains an analysis of a Tuberculosis Treatment Dataset, exploring demographic, socioeconomic, and health-related factors contributing to treatment outcomes. The analysis includes statistical tests, logistic regression modeling, and data visualization to uncover associations and predict factors influencing treatment default rates.

**📖 Project Description**

The analysis investigates treatment outcomes among tuberculosis patients, focusing on demographic (age, sex), socioeconomic (poverty, education), and health risk factors (alcohol use, drug use, diabetes). Statistical and predictive modeling techniques are used to identify significant predictors of treatment default.

**📊 Dataset Overview**

_Sample Size:_ 1,234 patients

_Key Variables:_ 
Age group (21 and younger, 22-26, 27-37, 38 and older) 
Sex (Male, Female) 
Poverty Status (Poverty/Extreme Poverty, Not in Poverty)
Education Level (Secondary Education, No Secondary Education)
Alcohol Use, Drug Use, History of Rehabilitation, Diabetes
Treatment Outcomes (Cured, Default, Died, Transferred, Current)

**🎯 Objectives**

Explore the demographic and socioeconomic characteristics of TB patients.
Analyze treatment default rates and associated factors.
Test associations between diabetes, substance abuse, and treatment default.
Fit logistic regression models to identify significant predictors of default.
Evaluate the effectiveness of self-reported data for treatment interventions.

**⚙️ Methodology**

_Exploratory Data Analysis (EDA):_

_Summary statistics_
Visualization of demographic distributions

_Statistical Testing:_  Chi-Square Tests;  Two-Proportion Z-Tests

_Regression Modeling:_  Logistic Regression; Model Comparison using AIC

_Hypothesis Testing:_  Significance Testing (p-values, confidence intervals)


**📈 Key Findings**

Default Rate: 10.3% of patients defaulted from TB treatment.
Significant Predictors:
Age: Patients aged 38 and older have a lower risk of default.
Sex: Males have higher odds of default.
Education: Completing secondary education reduces the risk of default.
Drug Use & Alcohol Use: Strongly associated with higher default rates.
MDR-TB: Increases the risk of default.
Diabetes Status: No significant association with default risk was observed.
Rehabilitation History: Appeared significant initially, but became non-significant after adjusting for substance use.

**📊 Statistical Analysis**
Chi-Square Tests: Tested associations between poverty, education, age, and sex.
Logistic Regression Models: Evaluated predictors of treatment default.
Model Comparison (AIC): Compared models with and without diabetes status.

**⚠️ Limitations**
Self-Reported Data Bias: Risk of underreporting substance use and subjective responses.
Small Diabetic Subgroup: Limited power for diabetes-related conclusions.
Confounding Variables: Residual confounding may persist despite adjustments.
Recommendation: Combine self-reported data with clinical assessments, medical records, and objective socioeconomic indicators.

**📦 Dependencies**
Ensure you have the following R packages installed:

dplyr
ggplot2
broom
tidyverse
stats

**Install all dependencies using:**
r
install.packages(c("dplyr", "ggplot2", "broom", "tidyverse", "stats"))

**🤝 Contributing**
Contributions are welcome! Please:
Fork the repository.
Create a feature branch (git checkout -b feature-new-analysis).
Commit changes and submit a pull request.
