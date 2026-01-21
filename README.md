# Insurance Claim Prediction for Buildings

## 📌 Project Overview

This project focuses on building a **machine learning classification model** to predict whether a building will have **at least one insurance claim** during an insured period. The prediction is based on various **building characteristics** and risk-related features.

The notebook demonstrates a **complete end-to-end data analytics and machine learning workflow**, including data preprocessing, handling missing values, model training, and performance evaluation.

---

## 🎯 Problem Statement

Insurance companies need to accurately assess the risk associated with insuring buildings. The goal of this project is to:

> **Predict the probability that a building will have at least one insurance claim during the insured period.**

### Target Variable

* **`Claim`**

  * `1` → Building has at least one claim
  * `0` → Building has no claims

---

## 📊 Data Overview

* The dataset consists of **building-level features** such as structural, environmental, and risk-related attributes.
* The data includes **missing values**, which are handled during preprocessing.
* The task is a **binary classification problem**.

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas & NumPy** – Data manipulation and analysis
* **Scikit-learn** – Machine learning models and preprocessing
* **Matplotlib & Seaborn** – Data visualization

---

## ⚙️ Machine Learning Workflow

### 1️⃣ Data Preprocessing

* Handling missing values using **SimpleImputer**
* Feature scaling with **StandardScaler**
* Train-test split using `train_test_split`

### 2️⃣ Models Implemented

* **Logistic Regression**
* **Random Forest Classifier**

### 3️⃣ Model Evaluation Metrics

* Accuracy Score
* ROC-AUC Score
* Confusion Matrix
* Classification Report

---

## 📈 Results & Insights

* The models are evaluated using multiple performance metrics to ensure reliability.
* ROC-AUC is used to assess how well the model separates claim vs non-claim buildings.
* Feature preprocessing significantly improves model performance.

---

## 📂 Project Structure

```
├── building_insurance.ipynb   # Main Jupyter Notebook
├── README.md                 # Project documentation
```

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/oluwaseun55/Insurance-Claim-Prediction-for-Buildings.git

```

2. Navigate to the project directory:

```bash
cd your-repo-name
```

3. Open the notebook:

```bash
jupyter notebook building_insurance.ipynb
```

---

## 🔮 Future Improvements

* Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
* Feature importance analysis
* Class imbalance handling (SMOTE, class weights)
* Deployment as a web application or API

---

## 👤 Author

**Oluyinka Oluwaseun Emmanuel**
Computer Engineer | Data Analyst | Machine Learning Enthusiast

📍 Lagos, Nigeria
🔗 LinkedIn: [www.linkedin.com/in/oluyinka-oluwaseun-a31843187](http://www.linkedin.com/in/oluyinka-oluwaseun-a31843187)

---

## 📜 License

This project is for **educational and research purposes**.

---

⭐ *If you find this project useful, please consider giving the repository a star!*
