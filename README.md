# Smoking-Status-Predictions

Certainly! Here's a concise summary of the steps i have taken to predict smoking status using machine learning:

1. **Data Exploration and Preprocessing:**
   - The dataset contains health parameters such as age, height, weight, blood pressure, cholesterol levels, and more.
   - No missing values were found in the dataset, and there were no duplicate entries.
   - A correlation matrix and heatmap were used to explore relationships between different health parameters.

2. **Outlier Removal:**
   - Outliers were removed from the dataset using the Interquartile Range (IQR) method to ensure a more accurate model.

3. **Feature Selection:**
   - Features were selected based on their importance for predicting smoking status using the SelectKBest method.

4. **Model Building:**
   - Various machine learning models were trained and evaluated:
      - Random Forest Classifier
      - Decision Tree Classifier
      - ExtraTrees Classifier
      - AdaBoost Classifier
      - Gradient Boosting Classifier
      - XGBoost Classifier
      - Naive Bayes Classifier
      - K-Nearest Neighbors (KNN) Classifier
      - Logistic Regression

5. **Model Evaluation:**
   - Each model's performance was assessed using classification reports, including precision, recall, and F1-score.
   - The training accuracy was also evaluated to understand how well the models performed on the training data.

6. **Prediction on Test Data:**
   - The AdaBoost Classifier was selected as the final model.
   - The model was used to make predictions on new test data entries.

7. **Conclusion:**
   - The machine learning model, particularly the AdaBoost Classifier, can be utilized to predict smoking status based on various health parameters.
   - Feature selection and outlier removal are crucial steps to enhance the model's accuracy and reliability.
