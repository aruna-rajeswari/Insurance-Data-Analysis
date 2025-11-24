# 🏥 Insurance Data Analysis

A comprehensive exploratory data analysis (EDA) project on the **Insurance dataset**, focused on understanding the factors that influence medical insurance charges. This analysis helps uncover patterns across demographics, lifestyle factors, and regional categories that impact premium costs.

---

## 📌 Problem Statement

ABC Insurance holds a large repository of customer and claims data. They want to understand how different factors—such as body type, environment, habits, and demographics—affect medical insurance premiums.

Insurance costs vary significantly based on personal behaviors and conditions. For example:

- Smokers generally pay higher premiums due to higher health risks.
- BMI may influence the chances of developing medical conditions.
- Regional healthcare costs may differ across the country.

The goal is to **analyze patterns in the dataset** that affect insurance charges and prepare insights useful for modeling premium predictions.

---

## 🎯 Objective

To perform exploratory data analysis (EDA) on the insurance dataset to understand key factors affecting medical insurance charges, and derive insights that can eventually support building a predictive model.

---

## 🩺 Domain  
**Healthcare Analytics**

---

## 📂 Dataset  
**File:** `insurance.csv`

### 📘 Dataset Description

| Feature | Description |
|--------|-------------|
| **age** | Age of the individual |
| **sex** | Gender (male/female) |
| **BMI** | Body Mass Index – health/fitness indicator |
| **children** | Number of dependent children |
| **smoker** | Smoking status (yes/no) |
| **region** | Residential region (northeast/northwest/southeast/southwest) |
| **charges** | Medical insurance cost |

---

## 📝 Steps Performed

### **1️⃣ Import Libraries & Load Dataset**
- Imported **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**
- Loaded `insurance.csv` into a DataFrame

### **2️⃣ Data Structure Overview**
- Checked the **shape** of the dataset  
- Reviewed **data types** for each column  

### **3️⃣ Missing Values Check**
- Identified missing values  
- Used suitable techniques to handle/clean missing data  

### **4️⃣ Univariate & Bivariate Analysis**
- **Count plots** for categorical variables:  
  - sex, smoker, region, children  
- **Scatter plots** for numerical variables:  
  - age, BMI, charges  

### **5️⃣ Feature-vs-Feature Visualizations**
- Pairplots and correlation heatmaps  
- Relationship analysis of:
  - age vs charges  
  - BMI vs charges  
  - smoker vs charges  
  - region vs charges  

### **6️⃣ Smoker vs Non-Smoker Premium Trend**
- Analyzed whether smoker premiums increase as age increases  
- Compared distributions and trend lines for both groups  

### **7️⃣ Observations**
After each major step, insights were recorded, such as:
- Smokers show significantly higher charges  
- BMI positively correlates with charges  
- Age strongly impacts medical costs, especially among smokers  
- Regional differences show minor variations in premiums  

---

## 📌 Key Insights (Summary)

- Smoking status has the **largest impact** on charges  
- Higher BMI tends to increase insurance costs  
- Age consistently increases medical expenses  
- Number of children has minimal effect on charges  
- Visualizations show clear separations between smoker and non-smoker costs  

---

## 🏁 Conclusion

The analysis reveals that lifestyle factors such as **smoking habits** and health indicators like **BMI** play a significant role in determining insurance charges. These findings support the hypothesis that medical premiums are closely aligned with underlying health risks. This exploratory analysis provides a strong foundation for developing a predictive model that can estimate insurance costs using key features such as **age**, **BMI**, and **smoker status**. Such a model can help insurance providers make more informed pricing decisions and improve risk assessment accuracy.

---
---

