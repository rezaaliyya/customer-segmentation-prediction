# 🤖 Customer Segmentation & Prediction

## 📌 Overview
This project focuses on customer segmentation and prediction using machine learning techniques. It combines clustering and classification approaches to identify customer groups and predict their behavior based on data patterns.

---

## 🎯 Objectives
- Perform customer segmentation using clustering techniques  
- Identify patterns and relationships between features  
- Build classification models to predict customer segments  
- Improve model performance through evaluation and tuning  

---

## 📂 Dataset
The dataset contains customer-related information such as:
- Demographic features  
- Transaction behavior  
- Numerical and categorical attributes  

Each row represents a unique customer.

---

## 🔎 Exploratory Data Analysis (EDA)
- Displayed dataset structure and summary statistics  
- Analyzed feature distributions using histograms  
- Generated correlation matrix to identify relationships  
- Identified patterns and potential outliers  

---

## ⚙️ Data Preprocessing
- Handled missing values and removed duplicates  
- Performed outlier handling  
- Dropped irrelevant features (ID, address, date)  
- Applied encoding for categorical variables (LabelEncoder)  
- Applied feature scaling using StandardScaler  
- Performed feature engineering (binning on selected features)  

---

## 🔵 Clustering (K-Means)
- Applied K-Means clustering on preprocessed data  
- Determined optimal number of clusters using Elbow Method  
- Evaluated clustering performance using Silhouette Score  
- Applied PCA for dimensionality reduction  
- Visualized clustering results  

---

## 🟢 Classification
- Split dataset into training and testing sets  
- Built Decision Tree model  
- Experimented with additional classification algorithms  
- Evaluated models using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
- Applied hyperparameter tuning to improve performance  

---

## 📊 Output
- Generated clustered dataset with target label  
- Exported processed data for further analysis  
- Produced model files for reuse  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Scikit-learn  
- Matplotlib, Seaborn  
- Joblib  

---

## 🚀 Key Takeaway
This project demonstrates how machine learning techniques such as clustering and classification can be used together to extract insights and build predictive models for customer behavior.
