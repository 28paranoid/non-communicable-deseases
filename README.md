# non-communicable-deseases
WHO Health Indicators to Support Mental Health Insights in Bhutan
This project is an end-to-end Python data science workflow built to analyze Bhutan’s national health indicators using official datasets from the World Health Organization (WHO) Global Health Observatory (GHO).

Although the dataset covers many general health indicators (life expectancy, cholesterol, mortality rates, etc.), the core long-term goal is to use these indicators to support mental-health–related insights, such as understanding:

How lifestyle, non-communicable diseases (NCDs), or demographic factors may correlate with stress and wellbeing.

Which years and indicators show unusual patterns that may relate to broader public-health stress.

This project lays the technical foundation, including a machine learning predictor, for future mental-health research tools in Bhutan.

Project Objectives
Analyze official WHO health indicators for Bhutan.

Perform data cleaning and preparation, including manual categorical encoding (no LabelEncoder).

Build a Random Forest Regression Model to predict health metric values.

Build a basic Streamlit dashboard to visualize health trends and make real-time predictions.

Support longer-term goals of studying mental health from a scientific, data-driven perspective.

Dataset Source
All health indicators are taken from: WHO Global Health Observatory (GHO) 🔗 https://data.humdata.org/dataset/who-data-for-btn (official WHO dataset for Bhutan).

The dataset includes indicators such as:

Life expectancy

Mortality rates

Non-communicable disease metrics

Cholesterol and blood pressure values

These indicators help us understand broader public health patterns that may indirectly influence mental-health risks.

Why Mental Health?
While the dataset does not provide direct "depression/suicide" indicators, mental health is influenced by many general health and societal indicators, such as:

NCD burden (chronic illness)

Alcohol & tobacco indicators

Demographic stress

Understanding national health trends is the first step toward building data-driven mental-health insights for Bhutan. This project builds the technical foundation for future work such as risk-factor analysis and simple prediction models.

License
This project is open-source under the MIT License.

Details for the indicators:
This comparative analysis shows the predicted values for the three key health indicators across all available demographic and substance-related dimensions for Bhutan in 2022. The predicted values vary significantly based on the specific dimension (gender, age-standardization, alcohol type) used as input.

1. Prevalence of Diabetes, crude (%)
   Gender Gap: The model predicts a notable gender difference, with the Female population having the highest expected prevalence at 16.98%, compared to 14.97% for the Male    population.
   Highest Risk: The data suggests Females are the highest-risk group for diabetes prevalence based on the model's prediction.
2. Alcohol Consumption (litres of pure alcohol)
   Gender Comparison: The predicted per capita consumption is very similar between genders (4.09 litres for Female and 4.04 litres for Male).
   Beverage Type: The prediction suggests that the largest portion of consumption comes from Beer (4.09 litres), with Spirits and Wine contributing very little (0.39 and      0.10 litres, respectively) to the overall recorded consumption

3.Mean Non-HDL Cholesterol (mmol/L)
  Age vs. Gender: The Age-standardized measure (4.43mmol/L) is predicted to be significantly higher than the crude values for the gender dimensions (3.02mmol/L) for Male     and Female).
  Interpretation: A value of (4.43mmol/L-)(Age-standardized) is often considered above the desirable threshold (<4.0mmol/L), suggesting that when adjusted for age           demographics, the average 'bad' cholesterol level may pose a greater cardiovascular risk than when simply looking at crude gender averages.
