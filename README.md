#POWEr BI REPORT
Click Here:(https://gagandeep-1.github.io/AnalystVision/) To view the Power BI Reprt.
# HEALTH INSURANCE ANALYSIS REPORT
#OVERVIEW 
This repository contains a Power BI Report analyzing Health Insurance data. The Report explores Key aspects such as medical charges, BMI, Age, and how they vary by 
categorical features like "sex","region", and "smoker status".
#Objective
The purpose of this report is to provide insights into how different factors like gender, smoking insights and region affect health insurance charges and other health 
metrics.It helps identify trends and potential areas for further analysis.
# Features
 **Categorical Data Analysis**: Visualizes the relationship between **sex**, **region**, **smoker** status, and health-related numerical variables.
- **Numerical Data Analysis**: Focuses on analyzing **BMI**, **age**, **charges**, and **children** across different categories.
- **Interactive Visuals**: Users can interact with charts to filter data by region, sex, smoker status, etc.
- **Key Insights**: Understand how **smoking** and **region** influence **health insurance charges**.

- > Note: The report is publicly accessible via the link. If you want to explore it privately, please contact the administrator for access.
  >
  > ## Data Sources : Kaggle (https://www.kaggle.com/datasets/mustafaoz158/healthcare-insurance)
- Health insurance claims data
- Medical records, including BMI, age, and number of children
- Demographic information: **sex**, **region**, **smoker status**

- ## Key Metrics:
- **Charges**: Total medical charges incurred by each individual.
- **BMI**: Body Mass Index (BMI) of the individual.
- **Age**: Age of the individual.
- **Children**: Number of children or dependents covered under the health insurance plan.
- > The report above shows the medical charges distribution across different regions.
  


  ### Exploratory Data Analysis (EDA)
The following **EDA** steps were conducted to prepare the data for analysis:

#### 1. **Data Cleaning**:
   - Missing values were identified in columns such as **age**, **BMI**, and **charges**. Rows with missing values were removed for a cleaner dataset.
   - Outliers in the **BMI** and **Age** column were detected using **box plots**, and values that were extreme (beyond 1.5 * IQR) were flagged for review.
   - It is confirmed that the dataset contains no duplicate rows, ensuring data integrity.

 Z-Score Analysis

- **Children**: The Z-score for **children** is 0.18, indicating that the data points for this variable are close to the mean and there are no significant outliers.
- **BMI, Charges, Age**: The Z-scores for **BMI**, **charges**, and **age** are all 0, indicating that these variables are centered around the mean, with no extreme values detected.
- Since the Z-scores for all numerical columns are close to 0, there were no extreme outliers found in the dataset during the **EDA** process.

- 

