# 🛒 E-commerce Customer Churn Prediction

This project focuses on predicting customer churn in an e-commerce platform using machine learning techniques. It includes a full ML pipeline from data preprocessing, handling class imbalance, feature engineering, model selection, hyperparameter tuning, evaluation, and final interpretation. A research paper is also included to document the study and findings.

---

## 📁 Dataset

- **File:** `ecommerce_customer_data_custom_ratios.csv`
- **Attributes:** Customer demographics, product purchase behavior, payment method, and churn labels.
- **Target Variable:** `Churn` (Binary classification: 0 = Retained, 1 = Churned)

---

## 🔍 Techniques Used

- Data Cleaning & Date Feature Extraction
- Categorical Encoding (One-Hot Encoding)
- SMOTE for Imbalanced Classes
- Feature Scaling (StandardScaler)
- K-Fold Cross Validation
- GridSearchCV & RandomizedSearchCV for Hyperparameter Tuning
- Feature Selection using RFE

---

## 🧠 Models Compared

| Model               | Description                         |
|--------------------|-------------------------------------|
| Logistic Regression | Baseline linear classifier          |
| Random Forest       | Ensemble tree-based model           |
| Gradient Boosting   | Boosted ensemble model              |
| SVM (commented)     | Optional for future testing         |

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## 📄 Research Paper

📘 A full research paper detailing methodology, implementation, and results is included in the `paper/` folder:

- [`ecommerce_churn_research_paper.pdf`](https://github.com/shahmi0519/Ecommerce-Churn-Prediction/blob/main/paper/E-commerce%20Customers%20Churn%20Prediction.pdf)

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shahmi0519/Ecommerce-Churn-Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook notebooks/ecommerce.ipynb
   ```

---

## 📦 Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- wordcloud

---

## 📂 Project Structure
```bash
ecommerce-churn-prediction/
├── data/
│   └── ecommerce_customer_data_custom_ratios.csv
│
├── notebooks/
│   └── ecommerce.ipynb
│
├── images/
│   └── churn_distribution.png
│
├── paper/
│   └── E-commerce_Customers_Churn_Prediction.pdf
│
├── requirements.txt
├── README.md
└── LICENSE
```
---

## ✍️ Author
**Ahamed Shahmi A.J**
- **📧 Mail**: shahmiahamed0519@gmail.com
- **🔗 LinkedIn**: Ahamed Shahmi (https://www.linkedin.com/in/ahamed-shahmi-abduljabbar/)
- **💻 GitHub**: shahmi0519 (https://github.com/shahmi0519)

---

## 📝 License
This project is licensed under the MIT License – see the LICENSE file for details.
