# Employee Churn Analysis 🚀

## 🎯 Project Overview

This project focuses on analyzing and predicting employee churn (attrition) using the **IBM HR Analytics Attrition dataset**. The goal is to build and evaluate various machine learning models to identify the key factors contributing to employee turnover and to predict which employees are most likely to leave the company. 📊

---

## 💾 Dataset

The analysis is based on the [IBM HR Analytics Employee Attrition & Performance dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) from Kaggle.

This dataset contains **1470 instances** with **35 features**, providing detailed information about employees, such as:

* Demographics (Age, Gender)
* Job-related factors (Job Role, Department, Job Level)
* Satisfaction levels (Environment Satisfaction, Job Satisfaction)
* Compensation (Monthly Income, Percent Salary Hike)
* The target variable: **Attrition** (Yes/No)

---

## 🤖 Predictive Models Implemented

To tackle this classification problem, we implemented and compared the performance of three different predictive models:

1.  **🌲 Random Forest Classifier:** An ensemble model that uses multiple decision trees to improve prediction accuracy and control over-fitting.
2.  **🌳 Decision Tree Classifier:** A simple yet powerful model that creates a tree-like structure to make predictions based on a series of if-else conditions.
3.  **🧠 Artificial Neural Network (ANN):** A deep learning model inspired by the human brain, capable of learning complex patterns from the data.

---

## 📈 Results & Evaluation

The models were trained and evaluated on a held-out test set. Their prediction accuracies are summarized below.

| Model                       | Accuracy Score |
| --------------------------- | :------------: |
| 🧠 **Simple ANN** |   **0.8526** |
| 🌲 Random Forest            |     0.8277     |
| 🌳 Decision Tree            |     0.7506     |

### ✨ Conclusion

The **Simple Artificial Neural Network (ANN)** achieved the highest accuracy, making it the most effective model for predicting employee attrition in this analysis.

---

## 🛠️ How to Use This Project

To get started with this project, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/employee-churn-analysis.git](https://github.com/your-username/employee-churn-analysis.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd employee-attrition-analysis
    ```

3.  **Install the required libraries:**
    
    *Install all the libraries like pandas, scikit-learn, tensorflow, etc.*

4.  **Run the analysis notebooks or scripts!** 💻
