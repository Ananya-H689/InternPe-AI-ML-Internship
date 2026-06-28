# IPL First Innings Score Prediction using Machine Learning

## Project Overview

This project predicts the **first innings score of an IPL cricket match** using Machine Learning.

The prediction is based on the current match situation, including the batting team, bowling team, runs scored, wickets lost, overs completed, runs scored in the last five overs, and wickets lost in the last five overs.

A complete machine learning workflow was implemented, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, comparison, and prediction. Multiple regression algorithms were trained and compared to identify the best-performing model for IPL score prediction.

---

# Dataset

**Dataset:** IPL Match Dataset

### Features

- Batting Team
- Bowling Team
- Runs
- Wickets
- Overs
- Runs in Last 5 Overs
- Wickets in Last 5 Overs

### Target

- First Innings Total Score

---

# Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib

---

# Machine Learning Workflow

## 1. Data Collection

- Loaded the IPL match dataset
- Explored the dataset structure
- Displayed dataset information
- Checked missing values
- Analyzed feature distributions

---

## 2. Data Preprocessing

Performed preprocessing to improve data quality before training.

### Steps Performed

- Removed unnecessary columns
- Filtered valid IPL teams
- Removed records before the 5th over
- Selected important input features
- Encoded categorical variables
- Prepared feature and target variables
- Split dataset into training and testing sets

---

## 3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the relationships between different match features.

Visualizations included:

- Correlation Matrix
- Heatmap
- Feature Relationship Analysis

These visualizations helped understand how different match conditions influence the predicted first innings score.

---

## 4. Model Training

The following Machine Learning regression algorithms were trained:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Lasso Regression
- Support Vector Regression (SVR)
- Neural Network Regressor (MLP)

---

## 5. Model Evaluation

Each model was evaluated using the following performance metrics:

- Training Score
- Testing Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

These metrics were used to compare prediction accuracy and overall model performance.

---

## 6. Best Model Selection

After evaluating all regression models, their performances were compared using a visualization.

The comparison showed that **Random Forest Regressor** achieved the best overall prediction performance and was selected as the final model for IPL score prediction.

---

## 7. Prediction

The trained model was tested using sample IPL match scenarios.

Example input features include:

- Batting Team
- Bowling Team
- Current Runs
- Wickets
- Overs Completed
- Runs in Last Five Overs
- Wickets in Last Five Overs

The model predicts the expected **first innings score** for the match.

---

## 8. Model Saving

The trained models were saved using **Joblib**, allowing them to be reused later without retraining.

Saved models include:

- Decision Tree Model
- Random Forest Model
- Neural Network Model

---

# Project Screenshots

## Correlation Matrix

![Correlation Matrix](correlation_matrix.png)

---

## Heatmap

![Heatmap](heatmap.png)

---

## Model Comparison

![Model Comparison](model_comparison.png)

---

## Prediction Output

![Prediction Output](prediction_output.png)

---

# Repository Structure

```
Task-03-IPL-Score-Prediction/
│
├── IPL_Prediction_Model_Training_Ananya_Hebbar.ipynb
├── ipl_colab.csv
├── README.md
├── correlation_matrix.png
├── heatmap.png
├── model_comparison.png
├── prediction_output.png
├── forest_model.pkl
├── tree_model.pkl
└── neural_nets_model.pkl
```

---

# Results

✅ Successfully loaded and preprocessed IPL match data

✅ Performed Exploratory Data Analysis (EDA)

✅ Generated correlation matrix and heatmap

✅ Trained multiple Machine Learning regression models

✅ Evaluated models using MAE, MSE, RMSE, Training Score, and Testing Score

✅ Compared model performances visually

✅ Selected **Random Forest Regressor** as the best-performing model

✅ Predicted IPL first innings scores based on live match conditions

✅ Saved trained models using Joblib for future predictions

---

# Future Improvements

- Develop a web application for live score prediction
- Deploy the trained model using Flask or Streamlit
- Integrate live IPL match APIs
- Improve prediction accuracy using advanced ensemble models
- Extend the system for second innings win probability prediction

---

# Author

**Ananya Hebbar**

AI/ML Intern – InternPe
