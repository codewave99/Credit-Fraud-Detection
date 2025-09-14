# Credit-Fraud-Detection
This project presents a machine learning solution to detect credit card fraud using transaction data. Credit card fraud poses a significant risk to financial institutions and customers, leading to financial losses and reduced trust. Traditional detection methods often struggle with accuracy and timely identification of fraudulent transactions.
The project leverages a Random Forest Classifier to build a robust fraud detection model. It includes comprehensive data preprocessing, feature engineering, model training, evaluation, and deployment readiness. The model achieves high accuracy and provides insights into the most important features contributing to fraud detection.

Project Highlights
Data Preprocessing: Handles missing values, encodes categorical variables, and scales numeric features.
Model Development: Trains a Random Forest Classifier on credit card transaction data.
Evaluation: Uses accuracy, confusion matrix, classification report, and ROC-AUC score to assess model performance.
Feature Importance: Identifies key features influencing fraud detection.
Deployment: Includes a function to preprocess and predict fraud on new transaction data.
Logging: Saves model performance metrics to a log file for transparency.

Model Performance Summary
Accuracy: 100% on the test set
Confusion Matrix: Perfect classification with no false positives or false negatives
ROC-AUC: 1.00 indicating excellent discrimination ability
Feature Importance: Credit card limit and location-based features are significant predictors
How to Use
1. Clone the Repository
bash

Run
Copy code
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
2. Install Dependencies
Make sure you have Python 3.x installed. Install required packages:

bash

Run
Copy code
pip install pandas scikit-learn seaborn matplotlib joblib
3. Run the Project
Place your dataset CSV file in the specified path or update the file path in the script.
Run the Python script to train the model, evaluate it, and save the trained model.
bash

Run
Copy code
python credit_card_fraud_detection.py
4. Predict on New Data
Use the provided predict_new_data function to make predictions on new transaction data by passing a pandas DataFrame with the same features.

Outputs Included
Confusion Matrix and ROC Curve plots visualizing model performance.
Feature Importance plot showing top predictors of fraud.
Model saved as random_forest_model.pkl for reuse.
Model performance logged in model_performance_log.txt.
Future Work and Recommendations
Implement real-time fraud detection for immediate transaction monitoring.
Develop continuous learning pipelines to adapt to new fraud patterns.
Explore advanced algorithms such as Gradient Boosting Machines or Neural Networks for improved accuracy.
Integrate the model into existing banking systems for automated fraud alerts.
