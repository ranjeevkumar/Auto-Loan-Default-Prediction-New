### Auto Loan Default Prediction

**Ranjeev Kumar**

#### Executive summary

This project aims to predict vehicle loan defaults using machine learning techniques. The analysis includes data preprocessing, handling class imbalance, and model training using Logistic Regression, Random Forest, and Gradient Boosting. The final model helps financial institutions identify high-risk loan applications.

#### Rationale

Understanding and predicting loan defaults is crucial for financial institutions, as it directly impacts profitability and risk management. By predicting defaults accurately, lenders can reduce losses, optimize loan portfolios, and improve financial stability.

#### Research Question

Can we accurately predict the likelihood of vehicle loan defaults using historical data, and which factors contribute most significantly to loan default risk?

#### Data Sources

Vehicle Loan Default Prediction Dataset from Kaggle:  https://www.kaggle.com/datasets/avikpaul4u/vehicle-loan-default-prediction/data

#### Methodology

Data preprocessing: Removed missing values, scaled numerical data, and one-hot encoded categorical data.

Machine learning models: Trained Logistic Regression, Random Forest, and Gradient Boosting models. Applied Grid Search for hyperparameter tuning.

Evaluation metrics: Evaluated models using precision, recall, F1-score, and ROC-AUC. Visualized feature importance to identify key drivers of loan default.


#### Results

The Gradient Boosting model achieved the highest performance, with an AUC score that suggests good differentiation between default and non-default cases.

Feature importance analysis highlighted key factors that contribute to loan default risk, such as income level, loan tenure, and credit history.

#### Next steps

Integrate the Gradient Boosting model into the loan approval system for real-time prediction.

Collect more data to further improve model accuracy and robustness.

Experiment with other advanced techniques like XGBoost or neural networks to improve predictive power.

Adjust decision thresholds based on business needs to optimize precision vs. recall trade-offs.

#### Outline of project

https://github.com/ranjeevkumar/Auto-Loan-Default-Prediction-New


##### Contact and Further Information

For more information, please contact Ranjeev kumar at ranjeevkumar@gmail.com
