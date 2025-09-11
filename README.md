Loan Prediction Project

## Project Overview

This project focuses on predicting **loan approval status** based on applicant details such as income, education, employment, dependents, loan amount, and credit history.

The goal is to help **banks and financial institutions**:

* Automate loan eligibility checks
* Reduce manual errors and biases
* Improve decision-making with data-driven insights
* Save time and improve customer satisfaction

The project is divided into **two parts**:

1. **EDA (Exploratory Data Analysis)** – Understanding the dataset and extracting insights.
2. **Machine Learning Models** – Building and comparing algorithms to predict loan approval.

---

## Part 1: Exploratory Data Analysis (EDA)

### Steps Performed

1. **Data Cleaning**

   * Replaced missing values with median (for numerical) and mode (for categorical).
   * Converted `Dependents` column from `3+` to `3`.

2. **Data Visualization**

   * **Histograms** → Show distribution of numerical features like income, loan amount, etc.
   * **Bar Charts & Pie Charts** → Visualize categorical features like gender, education, and property area.
   * **Correlation Heatmap** → Understand relationships between features.
   * **Boxplots** → Detect outliers in numerical data.

###Key Insights

* **Credit History** has a very strong impact on loan approval.
* Applicants with higher income tend to have better chances.
* Self-employed applicants show slightly lower approval rates compared to salaried applicants.
* Property area also plays a role (urban > semi-urban > rural).

---

## Part 2: Machine Learning Models

### Steps Performed

1. **Feature Engineering**

   * Converted categorical columns into numeric using **Label Encoding**.
   * Split dataset into **train (80%) and test (20%)**.

2. **Models Used**

   * **Logistic Regression** – For baseline prediction.
   * **Decision Tree Classifier** – For rule-based learning.
   * **Random Forest Classifier** – For ensemble-based robust prediction.

3. **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1-Score
   * Confusion Matrix

### Results

* **Random Forest** performed the best with higher accuracy and balanced precision/recall.
* Logistic Regression was fast but less accurate.
* Decision Tree worked well but prone to overfitting.

---

##  Business Impact

By using this model, banks can:

* Quickly identify **high-risk vs low-risk applicants**.
* Improve **loan approval efficiency**.
* Reduce **default risks** by making informed decisions.
* Enhance **customer trust** through fair, transparent, and consistent approvals.

## 🛠️ Tech Stack

* **Programming Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

---

## 🚀 Future Improvements

* Use **SMOTE** to handle class imbalance.
* Try advanced models like **XGBoost or LightGBM**.
* Deploy the model as a **web app** for real-world use.

---

## 📌 Conclusion

This project demonstrates the **end-to-end pipeline of a Data Analyst / Data Scientist** – starting from **EDA** to **Machine Learning** and providing a **business solution**.

The final ML model can significantly assist banks in automating loan approvals with accuracy and efficiency.

✨ *Made with Python, Data, and Curiosity!* ✨
