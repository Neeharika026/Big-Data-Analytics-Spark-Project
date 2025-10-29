# 🧠 Big Data Analytics using PySpark & Machine Learning  

This project demonstrates **big data analytics** and **machine learning** using **PySpark** on the **IDS 2018 Intrusion Detection Dataset** (from Kaggle).  
The entire workflow is implemented in **Google Colab** using a **Jupyter Notebook (.ipynb)** file.  

---

## 📂 Dataset  

**Source:** [IDS 2018 Intrusion Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv)  
**Format:** CSV files  
**Description:** Network intrusion data used to identify normal and malicious network traffic patterns.  

---

## ⚙️ Environment & Tools  

- **Platform:** Google Colab  
- **Language:** Python  
- **Framework:** PySpark (Spark SQL, MLlib)  
- **Notebook Type:** Jupyter (.ipynb)  

**Libraries Used:**  
`pyspark`, `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, and other supporting modules for data analysis, visualization, and machine learning.  

---

## 🧩 Project Structure  

### **Task 1: Spark SQL Analysis**  
Performed exploratory and analytical queries using **Spark SQL**.  

**Queries and Functions Used:**  
1. Use of `COALESCE`, `COUNT`, `CASE...WHEN...THEN...END`, and `GROUP BY` clauses.  
2. Measurement of **skewness** and **kurtosis** for data distribution understanding.  
3. Data analysis and visualization queries including:  
   - Counting **normal** vs **harmful** connections.  
   - Categorizing attacks as **Network Attack** or **Database Attack** based on attack names.  
   - Querying each **attack name** with its **attacked port** and **number of attacks** (excluding *Benign*).  

---

### **Task 2 – Part 1: Analytical Methods (PySpark)**  
Applied analytical and statistical methods using **PySpark**:  
- **Descriptive Statistics**  
- **Statistical Correlation**  
- **Kernel Density Estimation (KDE)**  
- **Z-Score Calculation**  

---

### **Task 2 – Part 2: Machine Learning (PySpark MLlib)**  
Implemented and evaluated multiple **machine learning classifiers** for intrusion detection:  
1. **Decision Tree Classifier**  
2. **Random Forest Classifier**  
3. **Logistic Regression**  

---

## 📊 Visualization  

Data visualization was performed using **Matplotlib** and **Seaborn** to illustrate:  
- Class distribution (Normal vs Harmful connections)  
- Feature correlations and data trends  
- Model performance comparisons  

---

## 🚀 Key Highlights  

- Scalable data preprocessing and querying with **Spark SQL**.  
- Statistical and analytical computations on large-scale datasets.  
- Implementation of **ML models** using PySpark MLlib.  
- Visual insights for **data-driven decision making**.  

---

## 📘 How to Run  

1. Open the `.ipynb` file in **Google Colab**.  
2. Mount your **Google Drive** and upload the IDS 2018 CSV dataset files.  
3. Run each cell sequentially to reproduce the analysis and results.  

---

## 🏁 Conclusion  

This project demonstrates the integration of **Big Data Analytics**, **Statistical Analysis**, and **Machine Learning** using **PySpark** for effective **intrusion detection** on large-scale network datasets.  

---

*Developed in Google Colab using PySpark, MLlib, and Python for Big Data Analysis and Machine Learning.*
```

---
