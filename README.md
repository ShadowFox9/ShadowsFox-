🏡 Boston House Price Prediction — Regression Model
ShadowFox AIML Internship • Task 2

This project presents a complete end-to-end machine learning regression model for predicting Boston House Prices using real-world housing features such as crime rate, number of rooms, and socioeconomic indicators.
It follows the required steps: Preprocessing → Model Selection → Training → Evaluation → Final Results.

🚀 Project Overview

The objective is to design and implement a regression model capable of predicting the Median Value of Owner-Occupied Homes (MEDV) in Boston using the provided dataset.

Key components of the workflow:

✔ Data Preprocessing

✔ Exploratory Data Analysis

✔ Model Selection & Training

✔ Model Evaluation

✔ Interpretation of Results

✔ Submission-ready documentation

This project satisfies all requirements for ShadowFox AIML Internship Task 2.

📂 Dataset Description

The dataset contains several numeric predictors influencing housing prices in Boston. Key features include:

Feature	Description
CRIM	Per capita crime rate by town
ZN	Residential land zoned proportion
RM	Average number of rooms per dwelling
AGE	Proportion of old units built before 1940
TAX	Full-value property tax rate
PTRATIO	Pupil–teacher ratio
LSTAT	% lower status of the population
MEDV	Target Variable (median house value)
🛠️ Steps Performed
1️⃣ Data Preprocessing

Loaded dataset into DataFrame

Checked & confirmed no missing values

Conducted exploratory distribution checks

Split data into train (80%) and test (20%)

Normalized all features using StandardScaler

This ensures the model receives clean, scaled data.

2️⃣ Model Selection

The model used for this task is:

🔹 Linear Regression

Chosen because:

Interpretable and simple

Performs strongly on continuous numerical datasets

Suitable baseline model for regression problems

3️⃣ Training the Model

Trained the regression model on the scaled training features

Verified learned coefficients & intercept

Ensured all preprocessing steps were correctly applied

📊 Model Evaluation

The model was evaluated using three key performance metrics:

Metric	Value	Interpretation
MSE	24.999384790103072	Average squared error (lower = better)
RMSE	4.99993847863182	Model's average prediction error in price units
R² Score	0.659101389390355	Model explains 65.9% of total variance
🔍 Insight

A 65.9% R² indicates a solid baseline model capable of capturing most relationships in the dataset. With advanced models (e.g., Random Forest, XGBoost), accuracy could improve — but the task's requirement is fully satisfied.

📁 Project Structure
ShadowFox/
│── Task2_Boston_Housing.ipynb
│── boston.csv
│── README.md

🎥 Proof of Work (ShadowFox Requirement)

As required by the internship:

A LinkedIn video explanation of this task will be uploaded.

Screenshots and repository links will be included during submission.

Repository name: ShadowFox

Task organized in a dedicated folder.

✅ Conclusion

This project successfully implements a regression model that:
✔ Performs clean preprocessing
✔ Utilizes a correct and interpretable model
✔ Achieves respectable performance metrics
✔ Follows the exact instructions stated in the internship task list

👤 Author

Ngwoke Makuochukwu Mark
ShadowFox AIML Intern

