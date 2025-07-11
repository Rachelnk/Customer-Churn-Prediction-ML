# Customer-Churn-Prediction-ML
## Background
- This project analyzes customer data to predict customer churn for a telecommunications company that provides home phone and internet services.
## Methodology:
1.Clean and prepare data for analysis using Pandas:
   - Removing unnecessary columns that are not required for modelling i.e. Customer ID.
   - Check for missing values in the dataset.
   - Replace missing values in the TotalCharges column with 0.
   - Class imbalance identified in the target column churn.
2. Perform exploratory data analysis:
   - Understand the distribution of the numerical features i.e. Tenure, MonthlyCharges, TotalCharges.
   - Create a correlation heatmap for numerical features(columns).
   - Create count plot for categorical columns.
3. Data preprocessing:
   - Encode labels for target column, churn i.e. replace yes with 1 and no with 0.
   - Encode labels for categorical features.
   - Split data into training and test sets.
   - Apply SMOTE technique to address the class imbalance issue in the dataset.
   - Train the model with default hyperparameters
   - Of the two models used in training i.e. Random Forest and Decision Tree Classifier, Random Forest Classifier had the highest accuracy of 0.84.
   - Evaluate the model using test data.
   - Save the trianed model as a pickle file.
   - Load the saved model and build a predictive system
