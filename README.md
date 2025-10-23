# 🧩 Adult Dataset – Data Preprocessing & EDA

This project performs complete **data preprocessing** and **exploratory data analysis (EDA)** on the **Adult Dataset** to prepare it for machine learning tasks.  
It includes handling missing values, detecting and fixing noisy data, imputing missing values using **KNN Imputer**, analyzing **numerical and categorical relationships**, and **normalizing the data**.

---

## 📚 Steps Included

### **1️⃣ Data Description**
- Identified numerical and categorical columns  
- Checked data types, missing values, and duplicates  

---

### **2️⃣ Data Cleaning**
- Replaced “?” marks in categorical columns with `NaN`  
- Handled missing values using **mode** for categorical columns  
- Handled `0` values in numeric columns using **KNN Imputer**

---

### **3️⃣ Data Imputation**
- Applied **KNN Imputer** on columns like `2174` and `0`  
- Verified imputation results to ensure consistency  

---

### **4️⃣ Handling Noisy Data**
- Detected outliers using **IQR (Interquartile Range)**  
- Replaced outliers with **median values**  
- Cleaned categorical noise (e.g., typos, rare categories)  

---

### **5️⃣ Data Relationship Analysis**

| Relationship Type | Statistical Test | Visualization |
|-------------------|------------------|----------------|
| Numerical ↔ Numerical | Pearson & Spearman | Heatmap, Pairplot |
| Numerical ↔ Categorical | ANOVA & t-test | Boxplot |
| Categorical ↔ Categorical | Chi-Square / Cramer’s V | Crosstab Heatmap |

---

### **6️⃣ Normalization**
- Applied **MinMaxScaler** or **StandardScaler** to normalize numeric features  

---

## 📊 Visualizations
- ✅ Correlation Heatmap  
- ✅ Boxplots for outlier detection  
- ✅ Crosstab heatmap for categorical relationships  
- ✅ Pairplot for numerical correlations  

---

## ⚙️ Libraries Used

```bash
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
scipy
