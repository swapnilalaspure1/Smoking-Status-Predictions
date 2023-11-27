# Smoking-Status-Predictions

# About Dataset

Smoking has been proven to negatively affect health in a multitude of ways.Smoking has been found to harm nearly every organ of the body, cause many diseases, as well as reducing the life expectancy of smokers in general. As of 2018, smoking has been considered the leading cause of preventable morbidity and mortality in the world, continuing to plague the world’s overall health.

According to a World Health Organization report, the number of deaths caused by smoking will reach 10 million by 2030.

Evidence-based treatment for assistance in smoking cessation had been proposed and promoted. however, only less than one third of the participants could achieve the goal of abstinence. Many physicians found counseling for smoking cessation ineffective and time-consuming, and did not routinely do so in daily practice. To overcome this problem, several factors had been proposed to identify smokers who had a better chance of quitting, including the level of nicotine dependence, exhaled carbon monoxide (CO) concentration, cigarette amount per day, the age at smoking initiation, previous quit attempts, marital status, emotional distress, temperament and impulsivity scores, and the motivation to stop smoking. However, individual use of these factors for prediction could lead to conflicting results that were not straightforward enough for the physicians and patients to interpret and apply. Providing a prediction model might be a favorable way to understand the chance of quitting smoking for each individual smoker. Health outcome prediction models had been developed using methods of machine learning over recent years.



Certainly! Here's a concise summary of the steps i have taken to predict smoking status using machine learning:
0. **Data Spurce:**
    - Data gathered and downloaded from Kaggle
    
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
