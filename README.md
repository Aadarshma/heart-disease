# Heart-Disease Predictor
📌 Overview

This project focuses on predicting the likelihood of heart disease using the UCI Heart Disease dataset. The notebook includes:

Data preprocessing and cleaning

Exploratory Data Analysis (EDA)

Feature encoding and preparation

Machine learning model training for classification

The goal is to build a reliable model to assist in early diagnosis of heart disease using clinical and demographic data.

📂 Dataset

Source: UCI Heart Disease Dataset on Kaggle

Rows: ~300+

Columns: Includes demographic, medical, and clinical attributes such as:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Maximum heart rate achieved

Exercise-induced angina

Target variable (num) → Indicates presence/absence of heart disease

⚙️ Installation

Clone this repository and install the dependencies:

git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
pip install -r requirements.txt

🧑‍💻 Usage

Upload your kaggle.json API key to access the dataset.

Run the Jupyter Notebook:

jupyter notebook Untitled2.ipynb


The notebook will:

Download the dataset

Clean and preprocess the data

Perform exploratory data analysis

Train machine learning models

📊 Exploratory Data Analysis

Distribution plots of numerical features

Correlation heatmap of all numerical variables

Categorical feature encoding

🤖 Models (Planned/Implemented)

Logistic Regression

Random Forest

Support Vector Machines (SVM)

Gradient Boosting

Evaluation metrics will include Accuracy, Precision, Recall, and F1-score.

🚀 Future Improvements

Hyperparameter tuning

Cross-validation for robust results

Deployment using Streamlit or Flask

Integration with a real-time health monitoring system

📌 Requirements

Main libraries used:

pandas

numpy

matplotlib

seaborn

scikit-learn

kaggle

Install them using:

pip install -r requirements.txt

📜 License

This project is licensed under the MIT License.
