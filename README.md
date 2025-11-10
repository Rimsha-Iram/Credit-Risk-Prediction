# Credit Risk Prediction

## Objective
The goal of this project is to predict whether a loan application will be approved or rejected based on applicant and loan-related features. The predictions can help banks identify high-risk applicants and optimize lending strategies.

## Approach
1. **Data Cleaning & Preprocessing**
   - Handled missing values using median for numerical features.
   - Encoded categorical variables for model compatibility.
2. **Exploratory Data Analysis (EDA)**
   - **Univariate Analysis:** Studied distributions of numerical features like ApplicantIncome, LoanAmount, and Credit_History.
   - **Bivariate Analysis:** Examined relationships between features and Loan_Status.
   - **Correlation Analysis:** Checked correlations between numerical features.
3. **Modeling**
   - Trained Logistic Regression (baseline) and Random Forest models.
   - Evaluated performance on the test set using accuracy, recall, precision, and F1-score.
4. **Feature Importance**
   - Determined which features contribute most to loan approval prediction.

## Results & Insights
- **Model Performance:** Both Logistic Regression and Random Forest achieved 75% accuracy on the test set.
- **Key Predictors:** Credit_History, LoanAmount, and ApplicantIncome are the most influential features.
- **Business Insights:** 
  - Focus verification and interventions on high-risk applicants.
  - Policy adjustments such as collateral requirements or tiered interest rates for risk mitigation.
- **Limitations:** Dataset size is limited; class imbalance affects prediction for rejected loans.
- **Next Steps:** Explore advanced models (XGBoost, LightGBM), feature engineering, and larger datasets for improved performance.

## Author
- Rimsha Iram
- [Check Portfolio](https://www.datascienceportfol.io/rimshairamanalytics)
- Let’s connect on [LinkedIn](https://www.linkedin.com/in/rimsha-iram-analytics)

