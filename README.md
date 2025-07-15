# 🧠 PCOS Detection using Machine Learning

This project focuses on the early detection of **Polycystic Ovary Syndrome (PCOS)** using machine learning techniques. It uses patient health data to train and evaluate classification models to support clinical diagnosis. The primary models used are **Support Vector Machine (SVM)** and **Random Forest Classifier**.

---

## 📊 Problem Statement

**Polycystic Ovary Syndrome (PCOS)** is a common hormonal disorder among women of reproductive age. It affects metabolic, reproductive, and psychological health. Early diagnosis is critical, and this project aims to provide a predictive system based on clinical features using ML.

---

## 📁 Dataset

- **Source**: [Mention Dataset Source, e.g., Kaggle]
- **Features**: Includes hormonal data, menstrual history, BMI, insulin resistance indicators, and dermatological signs
- **Target Variable**: `PCOS (Y/N)`

---

## 🔍 Exploratory Data Analysis (EDA)

To understand feature relationships and detect outliers, the following techniques were used:
- 📦 **Boxplot**: To visualize outliers and distribution of key variables
- 🔗 **Correlation Matrix (Heatmap)**: To analyze relationships between features and identify multicollinearity

---

## 🛠️ Technologies Used

- **Python**
- **Libraries**: pandas, numpy, seaborn, matplotlib, scikit-learn
- **Environment**: Google Colab

---

## 🤖 Machine Learning Models

After preprocessing and EDA, the following models were trained and evaluated:

### ✅ 1. **Support Vector Machine (SVM)**
- Kernel-based classification
- Good performance with smaller datasets

### ✅ 2. **Random Forest Classifier**
- Ensemble model using decision trees
- Good at handling non-linear relationships and overfitting

---

## 📈 Model Evaluation

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| SVM                 | 0.5%      | 0.5%      | 1.0%    | 0.66%  |
| Random Forest       | 0.5%      | 0.0%     | 0.0%    | 0.0%    |

---

## 🚀 Future Work

- Add hyperparameter tuning using **GridSearchCV**
- Implement additional models (e.g., Logistic Regression, XGBoost)
- Deploy the model using **Streamlit** or **Flask** for user-friendly access

---

## 👩‍💻 Author

**Aashritha Rao**  
📧 aashritharao2005@gmail.com  
📍 India  
🔗 [LinkedIn](www.linkedin.com/in/battaji-aashritha-13b7b232a)

---

## 🙏 Acknowledgments

- Thanks to the dataset providers and the ML community
- Inspired by real-world health challenges and the need for early PCOS detection
