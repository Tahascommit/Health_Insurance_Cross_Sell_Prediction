<p align="center" >
  <img src="https://github.com/Tahascommit/Health_Insurance_Cross_Sell_Prediction/blob/bc7807b3ece22fa82722d3f57c6c0883e6155624/assets/Health-cross-sell.png" width="703" height="340">
</p >


# Health Insurance Cross Sell Prediction (GPU Required)

Overview
--------

This project was designed to assist our client, an Insurance company, in expanding their product range by introducing Vehicle Insurance to their Health Insurance customer base. Our primary objective was to develop a predictive analytics model that could effectively identify potential customers for this new insurance offering.

Objectives
----------

*   **Customer Identification**: Accurately determine which customers are most likely to be interested in Vehicle Insurance.
*   **Data Utilization**: Leverage existing customer data to forecast the propensity to purchase Vehicle Insurance.
*   **Marketing Efficiency**: Enhance the client's marketing strategies through targeted communication.

Methodology
-----------

### Data Analysis

*   **Exploratory Data Analysis (EDA)**: Conducted a comprehensive EDA to understand customer demographics, vehicle details, and insurance policy specifics.
*   **Feature Engineering**: Refined and transformed data to be more effective for predictive modeling.

### Predictive Modeling

*   **Model Development**: Built a machine learning model to analyze customer attributes such as age, gender, region, vehicle age, damage history, and insurance policy details.
*   **Model Validation**: Ensured the accuracy and reliability of the model through rigorous validation processes.

Outcomes
--------

*   **Pattern Recognition**: Identified key patterns and relationships that correlate with a customer's likelihood to buy Vehicle Insurance.
*   **Strategic Insights**: Provided the insurance company with valuable insights for informed decision-making in their Vehicle Insurance marketing campaigns.
*   **Business Impact**: The deployment of this model is expected to streamline outreach efforts and potentially boost revenue through higher conversion rates.

Conclusion
----------

This project represents a significant step towards leveraging data-driven strategies to expand market offerings and enhance customer targeting for insurance products. Our predictive model serves as a tool for the insurance company to identify prospective Vehicle Insurance customers, thereby optimizing their marketing efforts and contributing to overall business growth.

### Models used for Classification:

1. Logistic Regression
2. Naive Bayes
3. Decision Tree
4. Random Forest
5. Gradient Boosting
6. XGBoost

### Model Evaluation:
<p>
  <img src="https://github.com/Tahascommit/Health_Insurance_Cross_Sell_Prediction/blob/78bf96ce69f8cb662d9a35c5ba612065f9c1e0a6/assets/ROC_AUC_All_Models.png" width="703" height="340">
</p>


Logistic Regression Precision: 0.250

Logistic Regression Recall: 0.975

Logistic Regression F1 Score: 0.397

-------------------------------------
Naive Bayes Precision: 0.250

Naive Bayes Recall: 0.975

Naive Bayes F1 Score: 0.397

--------------------------------------
Decision Tree Precision: 0.287

Decision Tree Recall: 0.317

Decision Tree F1 Score: 0.301

---------------------------------------
Random Forest Precision: 0.334

Random Forest Recall: 0.329

Random Forest F1 Score: 0.331

----------------------------------------
Gradient Boosting Precision: 0.290

Gradient Boosting Recall: 0.874

Gradient Boosting F1 Score: 0.435

-----------------------------------------
XGBoost Precision: 0.310

XGBoost Recall: 0.724

XGBoost F1 Score: 0.434

#### Predicting Probability and Class for new data with trained model:

<img src="https://github.com/Tahascommit/Health_Insurance_Cross_Sell_Prediction/blob/0aa6d00d5016c2fc62ac748b5335c4c9d1b5d60d/assets/Predicting_probs_Binary.png" width="703" height="340">
