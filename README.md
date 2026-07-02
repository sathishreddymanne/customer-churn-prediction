# 📉 Customer Churn Prediction

### Machine Learning-Based Customer Churn Prediction using Classification Algorithms

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📌 Overview

## 📖 Project Overview

Customer churn is one of the major challenges faced by telecom companies. This project focuses on predicting whether a customer is likely to leave the service based on factors such as **tenure, monthly charges, contract details, and service usage patterns**.

The objective is to analyze customer behavior, identify churn-related patterns, and develop Machine Learning classification models that help businesses proactively retain customers by predicting potential churn.

---

# 🎯 Objectives

- ✅ Analyze customer behavior and churn patterns.
- ✅ Clean and preprocess customer data.
- ✅ Perform Exploratory Data Analysis (EDA).
- ✅ Train multiple Machine Learning classification models.
- ✅ Compare model performance and select the best-performing model.

---

# 📊 Dataset

The dataset contains customer information collected from a telecom company.

## Features

| Feature | Description |
|----------|-------------|
| Gender | Customer Gender |
| Tenure | Number of months the customer stayed |
| Monthly Charges | Monthly subscription charges |
| Internet Service | Type of Internet service |
| Contract | Customer contract type |
| Churn | Target Variable (Yes/No) |

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Loaded and explored the dataset using Pandas.
- Handled missing values.
- Checked for duplicate records.
- Cleaned and prepared the dataset.
- Encoded categorical variables into numerical values.
- Prepared features for Machine Learning models.

---

# 📈 Exploratory Data Analysis

Various visualization techniques were used to understand customer behavior and churn patterns.

### Analysis Performed

- Customer Churn Distribution
- Tenure Analysis
- Monthly Charges Distribution
- Correlation Analysis
- Feature Relationship Visualization

### Example Visualizations

> Add your screenshots inside the **images/** folder.

```markdown
![Churn Distribution](images/churn_distribution.png)

![Correlation Heatmap](images/heatmap.png)

![Monthly Charges](images/monthly_charges.png)
```

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented.

| Model |
|--------|
| Logistic Regression |
| K-Nearest Neighbors (KNN) |
| Support Vector Machine (SVM) |
| Decision Tree Classifier |
| Random Forest Classifier |

---

# ⚖️ Feature Scaling

Feature scaling was applied using **StandardScaler** before training models that are sensitive to feature magnitude.

---

# 📏 Model Evaluation

The models were evaluated using the following metrics.

- 📌 Accuracy Score
- 📌 Confusion Matrix
- 📌 Classification Report
- 📌 Performance Comparison

---

# 🏆 Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | XX% |
| KNN | XX% |
| SVM | XX% |
| Decision Tree | XX% |
| Random Forest | **86%** |

## ⭐ Best Model

> **Random Forest Classifier** achieved the highest prediction accuracy of **86%** and was selected as the final model.

*(Update this section if another model performs better.)*

---

# 🔄 Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Collection
   │
   ▼
Data Cleaning
   │
   ▼
Missing Value Handling
   │
   ▼
Encoding
   │
   ▼
Feature Scaling
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Performance Comparison
   │
   ▼
Best Model Selection
```

---

# 📂 Project Structure

```text
Customer-Churn-Prediction/
│
├── dataset/
│   └── Customer_Churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── heatmap.png
│   └── model_comparison.png
│
├── outputs/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-Learn | Machine Learning |

---

# 📦 Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```

Navigate to the project folder.

```bash
cd Customer-Churn-Prediction
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

---

# ▶️ Usage

1. Open the notebook.
2. Load the customer churn dataset.
3. Run all notebook cells.
4. Train the classification models.
5. Compare evaluation metrics.
6. Predict customer churn using the best-performing model.

---

# 📚 Python Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# 💡 Key Learnings

This project provided practical experience in:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Classification Algorithms
- Hyperparameter Tuning using GridSearchCV
- Model Evaluation and Comparison
- End-to-End Machine Learning Pipeline Development

---

# 🚀 Future Improvements

- Implement advanced feature engineering.
- Address class imbalance using SMOTE or other resampling techniques.
- Deploy the model using Flask or FastAPI.
- Build an interactive dashboard using Streamlit.
- Implement XGBoost and LightGBM for improved performance.
- Containerize the application using Docker.
- Automate model retraining using CI/CD pipelines.

---

# 👨‍💻 Author

**Sathish Reddy Manne**

AI & ML Student • Machine Learning Enthusiast • Aspiring Data Scientist

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

# 🙏 Acknowledgements

- Scikit-Learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

Special thanks to the open-source community for providing the tools and libraries used in this project.

---

# ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub. It helps others discover the project and motivates future improvements.
