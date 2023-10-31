# Internship Project: MOLSIP2340

Welcome to my internship project repository, where I worked on three significant data analysis and prediction tasks:

1. Real Estate Price Prediction
2. Medical Insurance Cost Prediction
3. Market Basket Analysis

## Real Estate Price Prediction

This repository hosts a real estate price prediction project, designed to assist investors, buyers, and sellers in making informed decisions regarding housing investments. The project focuses on predicting housing prices in terms of "Pyng" based on various factors and attributes.

## Key Insights

- **Price Range**: House prices vary within a range of 7.6 Pyng to 117.5 Pyng, with an average price of 37.98 Pyng. The median price, approximately 38.45 Pyng, closely aligns with the average, indicating the validity of the Normal Distribution Assumption.

- **Correlation Analysis**: The correlation test reveals a relationship between several variables (X3, X4, X5, and X6) and the target variable (Y - House Price).

    1. **X3 and Y**: They exhibit a negative correlation coefficient of -0.67, implying that the distance to the nearest MRT station is inversely related to housing unit price. Closer proximity to an MRT station corresponds to higher house prices, and vice versa.

    2. **Longitude (X6) and Y**: These variables show a positive or aligned relationship, suggesting that as longitude increases (indicating a different map location), house prices tend to increase.

## Correlated Variables

The following variables exhibit correlation with the House Price (Y):

1. **X3 (Distance to MRT)**: Negative correlation.
2. **X4 (Number of Shopping Centers)**: Positive correlation.
3. **X5 (Latitude)**: Positive correlation.
4. **X6 (Longitude)**: Positive correlation.

Among these, X3 (distance to MRT) is the only variable with a negative correlation.

## Multicollinearity

Multicollinearity is observed between variables X3 and X6, with a correlation coefficient of -0.62. This indicates a strong correlation between the distance to the MRT and longitude, which could affect model accuracy.

## Model Performance

The project has implemented four different regression models to predict house prices. The best-performing model is the **Random Forest Regression Model**, which exhibits higher accuracy compared to the other models. Additionally, the **Support Vector Regression (SVR)** model demonstrates the lowest error rate, making it a reliable choice for accurately predicting house prices.


 # Medical Insurance Cost Prediction

Welcome to the Medical Insurance Cost Prediction project repository. This project is of significant importance as it aims to predict medical insurance costs for individuals based on various factors and attributes. The insights and predictions derived from this analysis have several implications:

## Significance

1. **Informed Decision-Making:** Predicting medical insurance costs empowers individuals and families to make informed decisions when selecting insurance plans. By understanding how factors such as age, BMI, and smoking status affect insurance charges, individuals can choose plans that best suit their needs and budget.

2. **Insurance Industry Optimization:** For insurance companies, accurate cost prediction is crucial for setting competitive premiums and managing risk. This project's predictive model provides insurers with a tool to refine pricing strategies, improving their competitiveness and profitability.

3. **Smoking Cessation Incentives:** The finding that smokers tend to pay higher insurance charges can serve as an incentive for individuals to quit smoking. This project highlights the potential long-term financial benefits of a smoke-free lifestyle.

4. **Personalized Healthcare Planning:** Individuals with higher medical insurance costs can plan their healthcare and financial resources more effectively. This prediction model provides a basis for financial planning and decision-making related to healthcare expenditures.

## Model Training and Evaluation

We trained multiple regression models to predict insurance costs. Here are the accuracy scores of the models:

- Random Forest Regression (RF): 0.8023
- K-Nearest Neighbors (KNN): 0.7385
- Linear Regression: 0.7291
- Decision Tree Regression (DTR): 0.7770

The best accuracy model from the four models is the Random Forest Regression Model with an accuracy score of 0.8023. It outperforms the other models, making it the preferred choice for predicting medical insurance costs.

## Conclusion

This project not only advances our understanding of how various factors influence medical insurance costs but also has practical implications for individuals, insurance companies, and public health. It underscores the importance of data-driven decision-making in the insurance and healthcare industries and promotes healthier lifestyles.

# Market basket analysis

Welcome to the Market basket analysis project repository. In this project, we apply K-Means clustering, along with the elbow method, to segment customers into distinct groups based on their behavior and attributes. The result of this analysis is 5 distinct customer clusters.

## Project Overview

Customer segmentation is a powerful technique used by businesses to better understand and cater to the diverse needs and preferences of their customer base. By grouping customers with similar characteristics, businesses can tailor marketing strategies, product offerings, and customer support to meet specific needs.

## K-Means Clustering and the Elbow Method

We used K-Means clustering, a popular unsupervised machine learning technique, to group customers into distinct clusters based on their similarities. The elbow method was employed to determine the optimal number of clusters. In this case, the elbow method suggests that 5 clusters provide a balanced and meaningful segmentation of customers.


## Conclusion

Customer segmentation is a fundamental tool for businesses seeking to enhance their understanding of their customer base. In this project, we successfully applied K-Means clustering and the elbow method to segment customers into 5 distinct groups, each with its unique set of characteristics. This segmentation can guide personalized marketing efforts and improve customer satisfaction.

