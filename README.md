# 💰 Insurance Cost Prediction using Decision Tree Regression

## 📌 Project Overview

This project focuses on predicting individual medical insurance charges using a **Decision Tree Regression** model. The objective is to estimate insurance costs based on demographic and health-related features such as age, BMI, smoking status, number of children, sex, and region.

The project demonstrates a complete machine learning workflow, including data preprocessing, feature engineering, model training, hyperparameter tuning using GridSearchCV, and model evaluation.

---

# 🎯 Problem Statement

Develop a machine learning model capable of accurately predicting medical insurance charges based on customer demographic and lifestyle information.

---

# 📂 Dataset

**Dataset:** Medical Insurance Cost Dataset

The dataset contains information about:

- Age
- Sex
- BMI
- Number of Children
- Smoker Status
- Region
- Medical Insurance Charges (Target Variable)

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Decision Tree Regressor
- GridSearchCV
- Pipeline
- ColumnTransformer
- Jupyter Notebook

---

# ⚙️ Machine Learning Workflow

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Train-Test Split
- Data Preprocessing
- Pipeline Creation
- Hyperparameter Tuning using GridSearchCV
- Model Training
- Model Evaluation

---

# 🔍 Hyperparameter Tuning

GridSearchCV was used to optimize the Decision Tree Regression model.

### Best Parameter

| Parameter | Value |
|-----------|------:|
| max_depth | **4** |

The tuned model improved generalization by selecting the optimal tree depth.

---

# 📊 Model Performance

| Metric | Score |
|---------|------:|
| Train R² Score | **0.8653** |
| Test R² Score | **0.8641** |
| Mean Absolute Error (MAE) | **2697.77** |
| Mean Squared Error (MSE) | **21093484.00** |

The small difference between training and testing performance indicates that the model generalizes well on unseen data.

---

# 📈 Evaluation

The model was evaluated using regression metrics including:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

The tuned Decision Tree Regression model achieved strong predictive performance while maintaining a good balance between model complexity and generalization.

---

# 📁 Repository Structure

```text
insurance-cost-prediction/
│
├── README.md
├── requirements.txt
├── insurance_cost_prediction_decision_tree.ipynb
└── insurance.csv
```

> **Note:** If the dataset is not included in the repository, download the Medical Insurance Cost dataset from Kaggle or another public source and place it in the project directory before running the notebook.

---

# 📈 Key Insights

- Built a Decision Tree Regression model to predict medical insurance charges.
- Applied GridSearchCV to identify the optimal tree depth.
- Achieved strong predictive performance with good generalization on unseen data.
- Demonstrated a complete machine learning workflow using Scikit-Learn Pipelines and ColumnTransformer.

---

# 💡 Future Improvements

- Compare Decision Tree Regression with Random Forest and XGBoost.
- Perform advanced feature engineering.
- Deploy the trained model using Streamlit or Flask.
- Experiment with ensemble learning techniques for improved accuracy.

---

# 🏆 Conclusion

This project successfully demonstrates a complete regression workflow using Decision Tree Regression for medical insurance cost prediction.

### Key Achievements

- End-to-end machine learning pipeline
- Data preprocessing using ColumnTransformer
- Hyperparameter tuning using GridSearchCV
- Decision Tree Regression model
- Good model generalization
- **R² Score: 0.8641** on the test dataset

The project showcases practical implementation of regression techniques for predicting medical insurance costs and serves as a strong portfolio project for machine learning and data science roles.

---

## 📄 License

This project is created for learning and portfolio purposes.
