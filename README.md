# Heart-Disease-Prediction-Using-Support-Vector-Machine-SVM-
The model is built using the Support Vector Machine (SVM) algorithm with different kernel functions to classify patients as either having heart disease or not.
📌 Project Overview

This project predicts the likelihood of heart disease using Machine Learning techniques. The dataset contains various medical attributes such as age, cholesterol level, blood pressure, maximum heart rate, and other clinical parameters.

The model is built using the Support Vector Machine (SVM) algorithm with different kernel functions to classify patients as either having heart disease or not.

This project demonstrates the complete Machine Learning workflow including:

Data Loading
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Scaling
Model Training
Model Evaluation
Visualization
🎯 Objective

The objective of this project is to develop a machine learning model that can accurately predict heart disease based on patient health records and assist in early diagnosis.

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Jupyter Notebook
📂 Dataset Features

The dataset contains the following important features:

Feature	Description
age	Age of patient
sex	Gender
cp	Chest pain type
trestbps	Resting blood pressure
chol	Cholesterol level
fbs	Fasting blood sugar
restecg	Resting ECG results
thalach	Maximum heart rate achieved
exang	Exercise-induced angina
oldpeak	ST depression
slope	Slope of peak exercise ST segment
ca	Number of major vessels
thal	Thalassemia
target	Heart disease prediction (0/1)
🔍 Exploratory Data Analysis

A scatter plot was created to visualize the relationship between:

Age
Maximum Heart Rate (thalach)
Heart Disease Status

This helps identify patterns and trends among patients with and without heart disease.

⚙️ Machine Learning Workflow
1. Data Preprocessing
Loaded dataset using Pandas
Checked missing values
Split features and target variable
2. Train-Test Split
Training Data: 80%
Testing Data: 20%
3. Feature Scaling

Used StandardScaler to normalize the data before training the SVM model.

4. Model Training

Implemented Support Vector Machine (SVM) with:

Linear Kernel
Polynomial Kernel
5. Model Evaluation

Performance metrics used:

Accuracy Score
Classification Report
Confusion Matrix
📈 Results
Linear Kernel SVM

Accuracy: 81.46%

Classification Metrics:

High Recall for Heart Disease Detection
Balanced Precision and F1-Score
Good Overall Performance
🚀 How to Run
Clone Repository
git clone https://github.com/yourusername/heart-disease-prediction.git
Install Dependencies
pip install pandas numpy matplotlib seaborn scikit-learn
Run Notebook
jupyter notebook

Open:

heart_disease_predict.ipynb
📊 Project Structure
Heart-Disease-Prediction/
│
├── heart_disease_predict.ipynb
├── dataset/
├── images/
├── README.md
└── requirements.txt
💡 Future Improvements
Hyperparameter tuning using GridSearchCV
Cross-validation
Feature selection techniques
Compare multiple algorithms
Logistic Regression
Random Forest
XGBoost
KNN
Deploy model using Flask or Streamlit
Build an interactive dashboard

✅ Conclusion

This project successfully developed a Heart Disease Prediction model using the Support Vector Machine (SVM) algorithm. After preprocessing and scaling the data, the SVM model achieved approximately 81.46% accuracy, demonstrating its effectiveness in classifying patients with and without heart disease. The results indicate that machine learning can be a valuable tool for supporting early diagnosis and healthcare decision-making. Further optimization and deployment can improve the model's performance and real-world usability.
