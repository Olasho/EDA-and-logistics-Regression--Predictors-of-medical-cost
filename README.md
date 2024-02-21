# EDA-and-logistics-Regression--Predictors-of-medical-cost
In this analysis, I explored the factors that influenced the individual medical costs billed by health insurance in the United States. The factors investigated for their influence on medical costs included the age of the primary beneficiary, sex of the contractor, smoking status of the beneficiary, body mass index (BMI) of the beneficiary, region (the beneficiary's residential area in the US), and number of children covered by health insurance.

To begin, I conducted descriptive statistics and exploratory data analysis (EDA) on these factors, providing a comprehensive overview of their distribution and characteristics. Following this, I used a multivariate linear regression model to ascertain which factors exerted a discernible influence on the charges billed by the health insurance.

The underlying assumptions of the linear regression model were also assessed. A component partial residual plot was used to evaluate the linearity of the model, while the variance inflation factor (VIF) was utilized to assess the collinearity among predictor variables. Additionally, Cook's distance was used to identify influential observations, normality and equality of variance were examined to evaluate the model's fit, and potential outliers were scrutinized. 

This project was conducted using R markdown in R Studio and included a multifaceted approach. It involved data cleaning, the identification of missing values, the conversion of variables where necessary, extensive data analysis, data visualization, and the creation of a comprehensive and detailed report on the findings. The codes used were also reported. The project was reported in the following steps accordingly;

1.    Code used to execute the analysis.
2.    Output for the code executed.
3.    Interpretation of the results obtained.

# Setting the Chunk options

First, the options of interest on the output of all the chunks was set.
