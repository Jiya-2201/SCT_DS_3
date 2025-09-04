# 📊 Internship Task 3 – Decision Tree Classifier on Bank Marketing Dataset

## 📌 Project Overview

This project is the **third task** of my internship, where I worked on applying **Machine Learning techniques** to a real-world dataset. The dataset comes from a **Portuguese banking institution**, collected as part of a direct marketing campaign.

The main objective of this project is to **predict whether a client will subscribe to a term deposit** (`y`: yes/no) using a **Decision Tree Classifier**.

By exploring customer demographics, economic conditions, and marketing campaign details, this project provides insights into **which factors influence customer decisions** and helps in designing more effective marketing strategies.

---

## 🎯 Objectives

The primary goals of this project are:

1. **Data Preprocessing** – Cleaning, encoding, and transforming raw data into a suitable format for machine learning models.
2. **Exploratory Data Analysis (EDA)** – Understanding patterns, correlations, and trends in the dataset using statistical analysis and visualizations.
3. **Model Building** – Implementing a **Decision Tree Classifier** to classify customers into potential subscribers (`yes`) or non-subscribers (`no`).
4. **Model Evaluation** – Measuring performance using accuracy, precision, recall, F1-score, and confusion matrix.
5. **Insights & Interpretability** – Extracting the most important features that drive customer subscription decisions.

---

## 📂 Project Structure

```
SCT_DS_3/
│── data/
│   ├── bank.csv               # Small sample dataset
│   ├── bank-full.csv          # Full dataset (45,211 records)
│   └── bank-names.txt         # Dataset description
│
│── notebook/
│   └── decision_tree.ipynb    # Jupyter Notebook with implementation
│
│── result/
│   ├── confusion_matrix.png   # Confusion matrix visualization
│   ├── decision_tree.png      # Decision tree structure
│   ├── feature_importance.png # Feature importance bar plot
│   └── classification_report.txt # Detailed classification metrics
│
│── requirements.txt           # Required dependencies
│── README.md                  # Project documentation
```

---

## 📊 Dataset Information

* **Source**: UCI Machine Learning Repository – Bank Marketing Dataset
* **Number of records**: \~45,000 (after cleaning)
* **Number of features**: 17 (categorical + numerical)
* **Target variable (`y`)**:

  * `yes`: Client subscribed to a term deposit
  * `no`: Client did not subscribe

### 🔹 Example Features

* **Demographic**: Age, Job, Marital Status, Education
* **Financial**: Balance, Housing Loan, Personal Loan
* **Campaign-related**: Contact Type, Duration of Call, Previous Outcome

---

## 🔎 Steps Performed

### 1. **Data Preprocessing**

✔ Handled missing values (if any)
✔ Encoded categorical features using One-Hot Encoding
✔ Converted target variable `y` into binary (yes=1, no=0)
✔ Normalized numerical features for better performance
✔ Split dataset into training (70%) and testing (30%)

---

### 2. **Exploratory Data Analysis (EDA)**

✔ Distribution plots for age, balance, and campaign outcomes
✔ Count plots for job, education, and contact type
✔ Correlation heatmap to study relationships between numerical features
✔ Class imbalance check (target variable `y`)

---

### 3. **Model Building**

✔ Implemented **Decision Tree Classifier** using `scikit-learn`
✔ Used **Entropy** criterion to calculate information gain
✔ Limited **max\_depth=5** to prevent overfitting
✔ Visualized the Decision Tree structure

---

### 4. **Model Evaluation**

✔ Evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
  ✔ Confusion Matrix plotted as a heatmap
  ✔ Classification report saved to file
  ✔ Feature importance ranking visualized

---

### 5. **Results & Insights**

* The model achieved an accuracy of **(\~fill your accuracy %)**
* The most important features influencing prediction:

  * **Duration of last contact**
  * **Age**
  * **Balance**
  * **Contact Type**
  * **Previous Outcome**

This shows that **longer call duration, financial stability, and previous campaign outcomes** are strong indicators of whether a client will subscribe.

---

## 📊 Results

### 🔹 Confusion Matrix

<img width="684" height="522" alt="Screenshot 2025-09-04 122758" src="https://github.com/user-attachments/assets/f23e63f3-1bfe-4f14-9ad2-ac28d85fbc4b" />


### 🔹 Feature Importance

<img width="1144" height="665" alt="Screenshot 2025-09-04 122829" src="https://github.com/user-attachments/assets/40c4e9b4-4571-4dd1-84bb-f8e00d51f642" />


### 🔹 Decision Tree Structure

<img width="1152" height="587" alt="Screenshot 2025-09-04 122813" src="https://github.com/user-attachments/assets/a0fb21e4-bfec-4e52-80f0-788f131a6279" />


---

## 🛠️ Technologies Used

* **Programming Language**: Python
* **Libraries**:

  * Data Processing: Pandas, NumPy
  * Visualization: Matplotlib, Seaborn
  * Machine Learning: Scikit-learn
* **Tools**: Jupyter Notebook, GitHub

---

## 📌 Key Learnings

* Gained hands-on experience in **data preprocessing and encoding techniques**
* Learned how to **build, evaluate, and interpret Decision Tree models**
* Understood the importance of **feature selection in predictive modeling**
* Improved skills in **data visualization and storytelling with data**
* Enhanced project documentation and reproducibility with GitHub

---

## 📖 References

* [UCI Machine Learning Repository – Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
* Scikit-learn Documentation – Decision Tree Classifier
* Hands-on Machine Learning with Scikit-Learn & TensorFlow (Aurélien Géron)

---

🔗 This repository demonstrates my ability to work with **real-world data, apply ML models, and extract business insights**.
