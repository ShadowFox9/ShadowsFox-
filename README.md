Boston House Price Prediction – ShadowFox AIML Internship (Task 2)

This project is part of the ShadowFox AIML Internship, focusing on building a complete Regression Model to predict Boston house prices using various housing and environmental features.

The task involves:

Data loading

Data preprocessing

Handling missing values

Feature engineering

Model selection

Model training

Evaluation

This README provides a clear overview of the full machine learning workflow implemented in this task.

📂 Dataset Information

The dataset used is HousingData.csv, containing features such as:

CRIM – Crime rate

ZN – Residential land zoned proportion

INDUS – Industrial proportion

CHAS – Charles River dummy variable

NOX – Nitric oxide concentration

RM – Average number of rooms per dwelling

AGE – Proportion of owner-occupied units built before 1940

DIS – Distances to employment centers

RAD – Accessibility to radial highways

TAX – Property-tax rate

PTRATIO – Pupil–teacher ratio

B – African American proportion

LSTAT – Lower-status population

MEDV – Target variable representing house prices

🧹 Step 1: Data Preprocessing

Preprocessing steps included:

Checking dataset shape and column structure

Identifying missing values

Handling missing values using median imputation

Ensuring clean and consistent data for model training

Splitting data into training and testing sets

🤖 Step 2: Model Selection

A Linear Regression Model was chosen due to the continuous nature of the target variable (MEDV – Median House Value)
and its suitability for predicting numerical values.

🎯 Step 3: Model Training

Model was trained using 80% training data

Features were fed into the linear model

Target variable was used to compute best-fit parameters

📊 Step 4: Model Evaluation

The model was evaluated using standard regression metrics:

Metric	Score
Mean Squared Error (MSE)	24.999
Root Mean Squared Error (RMSE)	4.9999
R² Score	0.6591

These results show a reasonably good model performance for this dataset.

💻 Technologies Used

Python 3.14.1

Pandas

NumPy

Scikit-Learn

Jupyter Notebook / VS Code

📁 Files in This Folder
Task2/
│── Boston_House_Price_Prediction.ipynb   # Full model code
│── HousingData.csv                       # Dataset
└── README.md                              # Documentation

📹 Proof of Work (POW)

A short explanatory video has been provided on LinkedIn as required by ShadowFox:

The video includes:

Dataset overview

Preprocessing explanation

Model training

Evaluation results

👤 Author

Mark Makuochukwu
ShadowFox AIML Intern
