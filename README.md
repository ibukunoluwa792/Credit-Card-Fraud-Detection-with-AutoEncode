### 🕵️‍♂️ Fraud Detection Using Machine Learning.

This project helps explores the detection of fraudulent transactions using machine learning techniques. It leverages data preprocessing, exploratory data analysis (EDA), and multiple classification algorithm to identify any suspicious activities in financial database.

### 📓 Project Overview

- **Notebook**: [`fraud_detection.ipynb`](./fraud_detection.ipynb)
- **Goal**: Build and evaluate models to accurately classify transactions as fraudulent or legitimate
- **Approach**:
  - Data Cleaning & Preparations.
  - Exploratory Data Analysis (EDA).
  - Feature Engineering.
  - Model Training & Evaluation

### 🛠️ Tools & Libraries

- Python (Jupyter Notebook)
- `pandas`, `numpy`
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for ML models'.
- `xgboost` (if used).
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix.

### 📊 EDA Highlights

- Class imbalance visualizations
- Feature distribution comparisons
- Correlation heatmaps

### 🤖 Models Trained

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting /// XGBoost (if applicable)

### 🧪 Model Evaluation

Each model was evaluated using:

- Confusion Matrix
- Classification Report
- ROC Curve (if plotted)
- Cross-validation scores

### 🔍 Key Findings

- Significant class imbalance (fraud cases are rare)
- Certain features have strong predictive power
- Ensemble models like Random Forest or XGBoost performed better on recall and precision metrics

### 📁 Project Structure

```
.
├── data
│   └── creditcardfraud.zip
├── fraud_detection.ipynb
├── LICENSE
├── logs
│   ├── events.out.tfevents.1497173435.poincare
│   ├── events.out.tfevents.1497174259.poincare
│   ├── events.out.tfevents.1497174328.poincare
│   ├── events.out.tfevents.1497175610.poincare
│   ├── events.out.tfevents.1497175679.poincare
│   ├── events.out.tfevents.1497176316.poincare
│   └── events.out.tfevents.1497193550.poincare
├── model.h5
└── README.md

2 directories, 12 files
``````````

### ✅ How to Run

1. Clone the repository:
   ````bash and fix
   git clone https://github.com/ibukunoluwa792/Credit-Card-Fraud-Detection-with-AutoEncode.git
   cd Credit-Card-Fraud-Detection-with-AutoEncode
   ````

2. Install Requirements.
```
pip install -r requirements.txt
````

