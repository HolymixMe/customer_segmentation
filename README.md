# 🧠 Customer Segmentation Project

This project aims to perform **customer segmentation** using **unsupervised and supervised machine learning** techniques.  
It involves clustering customers based on their demographic and behavioral attributes, and then classifying them using predictive models.

---

## 📊 Project Overview
The project is divided into two main stages:

### 1. **Clustering**
- **Algorithm:** K-Means  
- **Goal:** Group customers into segments based on demographics and spending patterns.  
- **Evaluation Metric:** Silhouette Score  

### 2. **Classification**
- **Algorithms:**
  - Logistic Regression  
  - Random Forest Classifier  
  - K-Nearest Neighbors (KNN)
- **Goal:** Predict which customer segment a new customer belongs to.  
- **Evaluation Metrics:** Accuracy, Precision, Recall, and F1-score  

---

## 🧰 Tools & Libraries
- **Python**
- **Google Colab / Jupyter Notebook**
- **Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 🗂️ Dataset
The dataset contains **2,240 records and 29 features** describing customer demographics, income, household composition, and spending habits across multiple product categories.

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Handle missing values using `SimpleImputer`
   - Encode categorical variables using `LabelEncoder`
   - Scale features using `MinMaxScaler`

2. **Exploratory Data Analysis (EDA)**
   - Visualize distributions and correlations
   - Analyze relationships between features

3. **Clustering**
   - Apply K-Means
   - Determine optimal cluster number using Elbow Method & Silhouette Score
   - Visualize clusters

4. **Classification**
   - Split data into train/test sets
   - Train Logistic Regression, Random Forest, and KNN models
   - Compare model performance using evaluation metrics

---

## 🔗 Google Colab Notebooks
- **Clustering:** [Open in Colab](https://colab.research.google.com/drive/1CeuO7DzQ5yRrHWqTizd5XG_h2mczARD0?usp=sharing)
- **Classification:** [Open in Colab](https://colab.research.google.com/drive/18EZ1BCY7_4jcg1Wbi36aDP8OX5HWpp9_?usp=sharing)

---

## 👨‍💻 Author
**Muhammad Fahmi Hussain**  
📧 [fahmisajaa@gmail.com](mailto:fahmisajaa@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/muhammad-fahmi-hussain)
