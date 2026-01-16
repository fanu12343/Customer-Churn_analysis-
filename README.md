# Customer Churn Analysis & Prediction

## 📌 Project Overview

This project focuses on **analyzing customer churn** and **predicting potential churners** using machine learning, followed by building **interactive dashboards** for both historical and predicted churn insights.

The complete workflow includes data cleaning, feature preparation, exploratory analysis, model building, prediction on new customers, and visualization through dashboards.

---

## 📂 Dataset

* **Dataset Name:** Telco Customer Churn Dataset
* **Source:** Imported into **Google Colab** for preprocessing and analysis
* **Key Column:** `Customer_Status`

  * `Joined` – Newly joined customers
  * `Stayed` – Existing retained customers
  * `Churned` – Customers who left the service

---

## 🔧 Tools & Technologies Used

* **Google Colab** – Data preprocessing & machine learning
* **Python** – Core programming language
* **Pandas & NumPy** – Data cleaning and manipulation
* **Scikit-learn** – Machine learning model building
* **Power BI / Dashboard Tool** – Data visualization & dashboards
* **Machine Learning Model** – Customer churn prediction

---

## 🧹 Data Cleaning & Preprocessing

1. Imported the Telco dataset into Google Colab.
2. Handled missing values by filling them with **appropriate and context-aware values**.
3. Standardized and cleaned categorical columns.
4. Identified three customer status values:

   * `Joined`
   * `Stayed`
   * `Churned`

---

## 📁 Data Segmentation

After cleaning, the dataset was split into **three structured datasets**:

* **Joined Customers Dataset**

  * Contains only newly joined customers
  * Used later for churn prediction

* **Churned & Stayed Dataset**

  * Contains historical customer behavior
  * Used for dashboard creation and model training

---

## 📊 Dashboard – Churn Analysis (Historical Data)

Using the **Churned & Stayed dataset**, a detailed churn analysis dashboard was created.

### Dashboard Highlights:

* Total Customers, New Joiners, Total Churn, Churn Rate
* Churn by:

  * Gender
  * Age Group
  * Tenure Groups
  * Internet Type
  * Payment Method
  * Contract Type
  * State
* Churn Reasons & Categories

📈 This dashboard provides **business-level insights** into why customers are leaving and which segments are most affected.

---

## 🤖 Machine Learning – Churn Prediction

### Model Development

* The cleaned **Churned & Stayed dataset** was used to:

  * Encode categorical variables
  * Scale numerical features (if required)
  * Train a machine learning classification model

### Model Objective

To **predict customer churn status** based on customer attributes and service usage patterns.

---

## 🔍 Prediction on New Customers

* The trained model was tested on the **Joined Customers dataset**.
* The model predicted whether newly joined customers are **likely to churn or stay**.
* Predictions were stored in a separate file for visualization.

---

## 📊 Dashboard – Churn Prediction Insights

A second dashboard was created using the **predicted churn data**.

### Dashboard Highlights:

* Count of predicted churners
* Predicted churners by:

  * Gender
  * Age Group
  * Marital Status
  * Tenure Groups
  * Payment Method
  * Contract Type
  * State
* Detailed table with:

  * Customer ID
  * Monthly Charges
  * Total Revenue
  * Number of Referrals

📌 This dashboard helps businesses **proactively identify at-risk customers**.

---

## 🎯 Key Outcomes

* Cleaned and structured real-world telecom data
* Built an end-to-end churn analysis pipeline
* Developed a machine learning model for churn prediction
* Created **two professional dashboards**:

  1. Historical Churn Analysis
  2. Predicted Churn Insights

---

## 🚀 Future Enhancements

* Improve model performance using advanced algorithms (XGBoost, LightGBM)
* Hyperparameter tuning & cross-validation
* Real-time churn prediction integration
* Deployment using Streamlit or Flask

---

## 👤 Author

**Fahad VB**
BTech Graduate | Data Analytics & Machine Learning Enthusiast

---

## 📄 License

This project is for **educational and portfolio purposes**.
