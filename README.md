BREAST CANCER PREDICTION USING LOGISTIC REGRESSION

Project Overview
This project uses Logistic Regression, a simple yet powerful Machine Learning algorithm, to predict whether a breast tumor is Malignant (Cancerous) or Benign (Non-Cancerous). The dataset used is the Breast Cancer Data.csv, which contains medical measurements of breast cells.

The goal of this project is to help beginners understand the end-to-end process of building a classification model — from loading data to evaluating model accuracy.

Steps Performed

1. Import Libraries
   Loaded essential Python libraries like Pandas, Numpy, and Scikit-Learn.

2. Load and Explore Dataset  
   Viewed first few rows using head()  
   Checked dataset shape, missing values, and duplicates

3. Data Cleaning  
•	Removed unnecessary columns (like “Unnamed: 32”)
•	Verified all features are numeric

4. Label Encoding  
  Converted the target column “diagnosis” from text to numbers:  
•	“M” → 1 (Malignant)
•	“B” → 0 (Benign)

5. Train-Test Split  
   Split data into 80% training and 20% testing sets.

6. Feature Scaling  
   Standardized all numerical columns using “StandardScaler()”.

7. Model Training  
   Trained a Logistic Regression model on the scaled training data.

8. Model Evaluation  
•	Predicted on the test set.
•	Calculated accuracy score to measure performance.

9. Prediction for One Sample  
   Tested the model with a single example input to check whether it’s cancerous or not.

Results
•	The model achieved high accuracy on the test data.
•	Logistic Regression was effective and easy to interpret.

Technologies Used
•	Python
•	NumPy
•	Pandas
•	Scikit-learn (sklearn)

What I Learned
•	How to clean and prepare a dataset for ML.
•	How to use Logistic Regression for binary classification.
•	How to evaluate and test your model.
•	How to make single predictions with trained models.

Author
Abdul Muqeet Burki  
Aspiring Data Scientist | Excel & Power BI Enthusiast | Python Learner

#MachineLearning #DataScience #Python #LogisticRegression

