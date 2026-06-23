# Turning-clicks-to-cash-MachineLearning-Python
Digital advertising budgets are frequently wasted on poorly targeted demographics, resulting in low conversion rates and inflated Customer Acquisition Costs . This project develops a predictive machine learning model to accurately forecast whether a specific user will click on an advertisement based on their behavioral and demographic profile. 


# Turning Clicks into Cash: Predicting Ad Click-Through Rates (CTR) 📊

> **Objective:** Developing a predictive machine learning model to accurately forecast user ad-clicks, achieving a 93% accuracy rate to optimize digital marketing spend and minimize Customer Acquisition Cost (CAC).

---

## 📑 Table of Contents
1. [Business Problem](#-business-problem)
2. [Dataset Overview](#-dataset-overview)
3. [Tools and Technologies](#%EF%B8%8F-tools-and-technologies)
4. [Project Execution](#-project-execution)
5. [Optimized Results](#-optimized-results)
6. [How to Run This Project](#-how-to-run-this-project)
7. [Future Work](#-future-work)
8. [Author & Contact](#-author--contact)

---

## 💼 Business Problem
Marketing teams frequently waste digital advertising budgets on poorly targeted demographics, resulting in low conversion rates. Without predictive targeting, companies deploy "spray and pray" advertising, leading to wasted ad spend, user fatigue, and lowered ROI. 

**Goal:** Engineer a classification model that predicts ad clicks, enabling the business to prioritize high-probability prospects and intelligently reallocate marketing budgets.

---

## 📂 Dataset Overview
The project utilizes historical consumer behavior data. 
* **Data Source:** `advertising.csv` (Located in the `/data` folder)
* **Key Features:** Daily Time Spent on Site, Age, Area Income, Daily Internet Usage, Ad Topic Line, City, Male (Gender), Country, Timestamp.
* **Target Variable:** `Clicked on Ad` (Binary: 0 or 1)

---

## 🛠️ Tools and Technologies
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest Classifier, Logistic Regression, Train/Test Split)
* **Version Control:** Git & GitHub

---

## ⚙️ Project Execution
1. **Exploratory Data Analysis (EDA):** Investigated correlations between area income, age, and internet usage. 
2. **Data Preprocessing:** Handled missing values, formatted timestamps, and split data into training and testing sets.
3. **Model Selection:** Evaluated baseline models before deploying a **Random Forest Classifier** due to its robustness against overfitting complex consumer data patterns.
4. **Evaluation:** Generated classification reports and confusion matrices to validate precision, recall, and f1-scores.

---

## 📈 Optimized Results
The **Random Forest model successfully predicted user click behavior with 93% accuracy.**

By applying this model to a live campaign environment, a business could:
* **Reduce Wasted Impressions:** Filter out users modeled as `< 50%` likely to click.
* **Optimize Budget:** Bid higher on ad placements for high-probability users, driving down the overall Cost Per Click (CPC).

---

## 🚀 How to Run This Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/turning-clicks-into-cash.git](https://github.com/your-username/turning-clicks-into-cash.git)

---

## 👨‍💻 Author & Contact
**Collin Aslin Dsouza** *Business Analytics & Management Accounting*

* 📧 **Email:** [dszcollin@gmail.com](mailto:dszcollin@gmail.com)
* 💼 **LinkedIn:** [Connect with me on LinkedIn](https://www.linkedin.com/in/collindsouza30)
* 🐙 **GitHub:** [Explore my projects](https://github.com/CollinAslinDsouza)
