# Supervised

### Problem Statement  

A major challenge in the insurance industry is accurately determining the appropriate premium for each customer based on their risk profile. Predicting the correct claim amount is crucial, as it directly impacts an insurer’s financial planning and decision-making.  

Health insurance claim costs depend on several factors, including personal health indicators such as *Body Mass Index (BMI), age, smoking status, and existing health conditions*. Accurately forecasting these costs using data-driven methods allows insurers to improve pricing strategies, manage risks effectively, and enhance operational efficiency.  

To address this challenge, insurance companies utilize various analytical and predictive techniques to estimate health insurance claims more accurately and automate the process. The goal is to develop a reliable model that can predict claim amounts based on key health and demographic factors, ultimately leading to fair pricing and better financial management.


### Table of Contents
1. Import Libraries.
   
2. Set Options.
   
3. Read Data.
   
4. Data Analysis and Preparation.
   
   4.1 - Understand the Data
   
   4.1.1 - Data Dimension
   
   4.1.2 - Data Types
   
   4.1.3 - Summary Statistics
   
   4.1.4 - Missing Values
   
   4.1.5 - Correlation
   
   4.1.6 - Analyze Categorical Variables
   
   4.1.7 - Analyze Relationships Between Target and Categorical Variables
   
   4.1.8 - Feature Engineering
   
   4.1.9 - Discover Outliers
   
   4.1.10- Recheck the Correlation
   
   4.2 - Prepare the Data
   
   4.2.1 - Check for Normality
   
   4.2.2 - One-Way Anova
   
   4.2.3 - Dummy Encoding of Categorical Variables
   
5. Linear Regression (OLS).

   5.1 - Multiple Linear Regression - Full Model - with Log Transformed Dependent Variable (OLS)
  
   5.2 - Multiple Linear Regression - Full Model - without Log Transformed Dependent Variable (OLS)
  
   5.3 - Fine Tune Linear Regression Model (OLS)
  
   5.3.1 - Linear Regression after Removing Insignificant Variable (OLS)
  
   5.3.2 - Check the Assumptions of Linear Regression
  
   5.3.2.1 - Detecting Autocorrelation
  
   5.3.2.2 - Detecting Heteroskedasticity
  
   5.3.2.3 - Linearity of Residuals
  
   5.3.2.4 - Normality of Residuals
  
   5.3.3 - Linear Regression after Removing Insignificant Variable (OLS) - Scaled Data
  
   5.3.4 - Linear Regression with Interaction (OLS)
  
6. Regularization (OLS).

   6.1 - Ridge Regression Model (OLS)
  
   6.2 - Lasso Regression Model (OLS)
  
   6.3 - Elastic Net Regression Model (OLS)
  
7. Stochastic Gradient Descent - SGD (sklearn).

   7.1 - Linear Regression with SGD (sklearn)
  
   7.2 - Linear Regression with SGD using GridSearchCV (sklearn)
  
8. Conclusion and Interpretation.


### Analysis and Conclusion.

The graph presents the performance metrics of the implemented models, including *Root Mean Squared Error (RMSE), R-squared (R²), and Adjusted R-squared (Adj. R²)*. The X-axis represents the model numbers as listed in the table.  

From the plot, we observe an *inverse relationship between R-squared(R²) values and RMSE*—as the R-squared(R²) value increases, the RMSE decreases. This trend indicates that models with higher R-squared(R²) values provide more accurate predictions, as they explain more variance in the data while minimizing errors.  

Among the tested models, *Linear Regression with Interaction* achieves the *highest accuracy, evidenced by the highest R-squared(R²) and lowest RMSE. Based on these findings, we conclude that **Linear Regression with Interaction is the most suitable model* for predicting insurance claim amounts. Insurance companies can utilize this model to enhance their pricing strategies and risk assessment processes.
