# E-Commerce-Churn-Prediction
Classification Model for Churn Prediction

## Background

The e-commerce company in this dataset has a churn rate of 16.8%. Customer churn is something businesses need to prevent as retaining existing customers is cheaper than acquiring new ones (Reichheld & Sasser, 1990). According to data from Chargebee Blog (2022) and Recurly Research (2022), a good churn rate for e-commerce companies is around 5%-10%. Therefore, there is a need for a system capable of identifying customers with a likelihood of churn, implementing further treatment to prevent them from churning.

## Objectives

The main objective of this project is to create a system that can identify customers with a likelihood of churn, pinpoint the causes of churn, and provide recommendations to prevent actual churn.

## Research Questions

1. What is the best machine learning model to predict customer churn in this dataset?

2. What factors contribute to customer churn?

3. What are the best recommendations to prevent customer churn?

## Data and Assumptions

The dataset used can be downloaded from the [dataset source](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction). The assumption in this study is that I ONLY process the dataset, and I cannot guarantee the validity of the dataset as there is no clarity on whether the data truly belongs to any specific e-commerce company, and the country of origin of the e-commerce is unknown.

## Data Analysis

In this project, several Python libraries such as Pandas, NumPy, and Matplotlib are used for data analysis. The file `E-Commerce Churn Prediction.ipynb` presents the detailed analysis steps. However, here, I will only display the results of the analysis according to the research questions previously formulated, and the analysis steps can be found in the file `E-Commerce Churn Prediction.ipynb`.

1. Results of Machine Learning Modeling with respective metrics
![Modeling Results](<fig/Modeling Results ML.png>)

2. Feature Importance
![Feature Importance](<fig/Feature Importance.png>)

## Conclusion

The analysis results indicate that the best model is XGBoost with its F2 score metric. From the feature importance, it is evident that there are 2 features with the highest values, namely tenure and complain. Hyperparameter Tuning has been applied to XGBoost, and the results are not significantly different from before tuning. Business recommendations will be based on the top 2 features in Feature Importance.

## Recommendations

Based on the analysis results, some recommendations that the e-commerce business owner may consider are:

1. Start Membership Program

The company can extend tenure by introducing a Membership Program. With a Membership Program, customers will receive more benefits by paying upfront. This encourages customers to make purchases more frequently as they are part of the membership program.

According to McKinsey, "62% of consumers are more likely to spend more money after subscribing to a paid loyalty program," and according to LoyaltyOne, "64% of program members are willing to pay if they receive better benefits such as free shipping. This percentage even increases to 70% for millennials."

2. Start Reward Program

The company can extend tenure by implementing a Reward Program. With a Reward Program, customers feel appreciated, leading to longer customer retention on the e-commerce platform, resulting in increased tenure.

In a report published by WireCard titled The Wirecard 2019 Consumer Incentives report, it is mentioned that: "For over half of respondents, rewards rated as extremely or very important for both big-ticket and small, habitual purchases." Additionally, "Over 92% of customers agree that rewards influence their purchase decision," and even more surprisingly, "75% of customers said they were likely to make another purchase after receiving an incentive."

3. Start Chatbot

The company can introduce a Chatbot to provide immediate answers to customer queries. A Chatbot can operate 24/7, enhancing customer convenience. The Chatbot can also connect with Customer Service to ensure customers receive comprehensive answers to their queries.

According to an article published by Qontak, "Sales will automatically increase due to customer satisfaction and a good relationship with customers. The Chatbot can not only answer customer questions but can also be utilized to offer product catalogs to your business using the robot marketing feature."

