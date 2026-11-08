# Credit Card Customer Segmentation and Churn

This Python project asks two questions about credit card customers: which customers behave similarly, and which are at risk of leaving? Segmentation supports tailored outreach, while churn prediction helps prioritize retention efforts.

## Approach

- Load the BankChurners dataset through KaggleHub and prepare features for analysis.
- Scale the clustering inputs and use K-means to identify four customer segments.
- Fit logistic regression and random forest churn models and evaluate classification performance using ROC AUC and related metrics.

## Explore the analysis

Open [Credit_Card_Customer_Segmentation.ipynb](Credit_Card_Customer_Segmentation.ipynb) in Jupyter or Google Colab. Run the data-loading cell before the analysis and modeling cells.
