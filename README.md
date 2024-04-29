# Carlifonia-Housing-prediction


## Overview

This repository contains an evaluation of different regression models for predicting housing prices in California. Three regression models were trained and evaluated: Linear Regression, Decision Tree Regression, and Random Forest Regression.

## Evaluation Metrics

The evaluation metrics for each model are as follows:

- **Linear Regression:**
  - Mean Squared Error (MSE): 4.350202e+09
  - R2 Score: 0.896423
  
- **Decision Tree Regression:**
  - MSE: 1.086866e+08
  - R2 Score: 0.997412
  
- **Random Forest Regression:**
  - MSE: 2.414949e+07
  - R2 Score: 0.999425

## Interpretation

### Linear Regression
The Linear Regression model has a relatively high MSE and an R2 Score of approximately 0.90, indicating that about 90% of the variance in the target variable (property prices) is explained by the model. However, the MSE is quite high, suggesting that the predictions have larger errors compared to the other models.

### Decision Tree Regression
The Decision Tree Regression model has a significantly lower MSE and a very high R2 Score close to 1, indicating that it explains about 99.74% of the variance in the target variable. The Decision Tree model performs exceptionally well on the validation set compared to Linear Regression.

### Random Forest Regression
The Random Forest Regression model has an extremely low MSE and an R2 Score very close to 1, suggesting an excellent fit to the data. The Random Forest model performs the best among the evaluated models, with the lowest MSE and highest R2 Score, indicating high predictive accuracy and goodness-of-fit.

## Conclusion

Based on the evaluation metrics provided, Random Forest Regression appears to be the best-performing model. It demonstrates the lowest MSE and highest R2 Score, suggesting superior predictive accuracy and model fit. Decision Tree Regression also performs exceptionally well, with a very low MSE and high R2 Score. Linear Regression, although not as strong as the other models based on the MSE and R2 Score, still provides a decent performance in predicting property prices.


