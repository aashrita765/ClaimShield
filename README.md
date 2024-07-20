# ClaimShield: Machine Learning Model for Fraudulent Claim Analysis

In this project, I developed a machine learning model to predict insurance fraud using a RandomForestClassifier. The project involved data preprocessing, model training, and evaluation, with a focus on real-world application and model deployment.

1. Load the Dataset:
   - Loaded the insurance claims dataset from a CSV file.

3. Handle Missing Values:
   - Filled missing values in the dataset using forward fill.

4. Encode Categorical Variables:
   - Converted categorical variables into numerical format using one-hot encoding, dropping the first category to avoid multicollinearity.

5. Data Visualization:
   - Plotted a histogram of claim amounts to understand the distribution of the data.

6. Split Data:
   - Separated the dataset into features and target variables.
   - I split the data into training and testing sets with an 80-20 split.

7. Standardize Features:
   - Standardized the numerical features using StandardScaler to improve model performance.

8. Train the Model:
   - Trained a RandomForestClassifier on the training data.

9. Evaluate the Model:
    - Made predictions and evaluated the model using a classification report, confusion matrix, and ROC-AUC score.
    - Plotted the ROC curve to visualize model performance.

10. Save and Load the Model:
    - Saved the trained model and scaler using joblib.
    - Demonstrated loading the saved model and scaler for future predictions.

11. Predict on New Data:
    - Created a function to prepare new claim data for prediction.
    - Standardized the new data and predicted the probability of fraud.
