# Churn Prediction Model Project

## Project Overview

This project aims to develop a churn prediction model to assist in identifying customers who are likely to churn from a subscription service. By utilizing a combination of data preprocessing, feature engineering, model building, optimization, and deployment techniques, this project provides actionable insights for customer retention.

## Project Structure

- `data/`: Contains the dataset 'churn_dataset.xlsx'.
- `notebooks/`: Includes the Jupyter Notebook 'Churn_Prediction_Model.ipynb' detailing code implementation.
- `app/`: Holds the Flask web application for model deployment.
  - `app.py`: Flask app code for serving the model through an API.
  - `trained_model.pkl`: Serialized trained model file.
  - `scaler.pkl`: Serialized StandardScaler file for preprocessing.

## Project Steps

1. **Data Preprocessing:**
   - Loaded the dataset and conducted initial exploratory analysis.
   - Managed missing data using imputation techniques and addressed potential outliers.
   - Employed one-hot encoding for categorical variables and performed a train-test split.

2. **Feature Engineering:**
   - Introduced a new feature 'Usage_Bill_Ratio' to capture usage-bill relationship.
   - Utilized StandardScaler to normalize numerical features for optimal model performance.

3. **Model Building:**
   - Explored different machine learning algorithms, including Logistic Regression and Random Forest Classifier.
   - Trained and validated models, leveraging cross-validation techniques.
   - Evaluated model performance metrics including accuracy, precision, recall, and F1-score.

4. **Model Optimization:**
   - Employed GridSearchCV to fine-tune hyperparameters of the Random Forest Classifier.
   - Utilized cross-validation to ensure robustness of hyperparameter choices.

5. **Model Deployment:**
   - Created a user-friendly Flask web application to serve the model via API.
   - Tested the API using sample data to demonstrate real-time predictions.

## Project Deliverables

- `Churn_Prediction_Model.ipynb`: Detailed Jupyter Notebook with comprehensive code and explanations.
- `Approach_Report.pdf`: In-depth report summarizing the methodology, decisions, and key insights.
- `Model_Performance.png`: Visualization depicting model performance metrics.
- `README.md`: This file, offering an overview of the project, its structure, and steps.

## Conclusion

This project underscores a holistic data science approach, showcasing proficiency in data preprocessing, feature engineering, model selection, optimization, and web application development. It stands as a testament to the application of machine learning in solving real-world business challenges.
