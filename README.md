# Real Estate Price Prediction

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


