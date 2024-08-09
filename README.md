# Logistic Regression on Advertising Data

## Project Overview

This project aims to analyze the effectiveness of advertising campaigns by applying logistic regression to predict whether a user will click on an ad based on various features. The goal is to build a model that helps in understanding the key factors that influence user behavior in response to advertisements.

## Dataset

- **Source:** The dataset includes user data related to their interaction with online advertisements, including features such as age, daily time spent on the website, area of residence, and the advertisement clicked status (target variable).
- **Features:** Key features include user demographics, website interaction metrics, and previous ad engagement.

## Tools & Libraries Used

- **Data Analysis:**
  - `Pandas` for data manipulation and analysis
  - `Matplotlib` and `Seaborn` for data visualization
- **Data Preprocessing:**
  - `Sklearn` for splitting the dataset into training and test sets, and for data normalization
- **Modeling:**
  - `LogisticRegression` from `sklearn.linear_model` to model the likelihood of a user clicking on an advertisement
- **Model Evaluation:**
  - Metrics such as `accuracy_score`, `confusion_matrix`, `precision_score`, `recall_score`, and `f1_score` to evaluate the model's performance

## Methodology

1. **Data Exploration:**
   - Performed exploratory data analysis (EDA) to understand the distribution of features and the relationship between the predictors and the target variable.

2. **Data Preprocessing:**
   - Cleaned the data by handling missing values and normalizing the features to ensure the model performs optimally.
   - Split the data into training and testing sets to evaluate the model's performance on unseen data.

3. **Model Training:**
   - Trained a `LogisticRegression` model to predict whether a user will click on an ad.
   - Analyzed the coefficients of the logistic regression model to understand the impact of each feature on the likelihood of clicking an advertisement.

4. **Model Evaluation:**
   - Evaluated the model using accuracy, precision, recall, and F1 score to assess its effectiveness in predicting ad clicks.
   - Analyzed the confusion matrix to understand the distribution of true positives, false positives, true negatives, and false negatives.

## Results

- The logistic regression model was able to accurately predict whether users would click on advertisements based on their demographic and interaction data.
- The model's coefficients provided insights into which features were most influential in driving ad clicks.

## Conclusion

This project successfully applied logistic regression to analyze advertising data, providing valuable insights into user behavior. The results can be used to optimize future advertising campaigns by focusing on the factors that are most likely to influence user engagement.

## Future Work

- Explore the use of more complex models, such as decision trees or neural networks, to improve prediction accuracy.
- Implement feature engineering techniques to create new variables that could further enhance model performance.
- Deploy the model in a real-time advertising system to provide ongoing predictions and insights.

