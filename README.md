# Predicting Student Employability using Machine Learning based on Soft Skills Assessment

## 📌 Project Overview
This research explores the application of **educational data mining** and machine learning to predict the employability status of graduates based on their **soft skills**. By analyzing a dataset of 2,982 students, the study identifies key traits that distinguish "Employable" from "Less Employable" candidates, providing an explainable framework for job readiness.

## ❓ Research Questions
The study focuses on answering the following:
*   Is there a significant relationship between soft skills and student employability?
*   Which soft skills significantly influence the prediction of student employability?
*   Which data mining algorithm provides the highest accuracy in predicting student employability?

## 📊 Dataset Details
*   **Source:** Kaggle (Mock job interview results from university agencies in the Philippines).
*   **Size:** 2,982 observations.
*   **Format:** 5-point Likert scale (1 = lowest, 5 = highest).
*   **Independent Variables (8):** Mental Alertness, Communication Skills, General Appearance, Ability to Present Ideas, Manner of Speaking, Self-Confidence, Student Performance Rating, and Physical Condition.
*   **Target Variable:** Class (Employable vs. Less Employable).

## 🛠 Methodology: SEMMA Framework
The project follows the **SEMMA** (Sample, Explore, Modify, Model, Assess) methodology:
1.  **Sample:** 70/30 training and testing split.
2.  **Explore:** EDA using frequency distributions (pie charts) and **Spearman Correlation** analysis.
3.  **Modify:** Data cleaning, encoding, and **Min-Max normalization**.
4.  **Model:** Implementation of Decision Tree (DT), Support Vector Machine (SVM), and k-Nearest Neighbors (kNN).
5.  **Assess:** Evaluation using confusion matrices, accuracy, precision, recall, and F1 score.

## 🚀 Technologies Used
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SHAP
*   **Framework:** SEMMA

## 📈 Model Performance
The models were evaluated to determine the most effective algorithm for career forecasting:

| Model | Accuracy | Precision | Recall | F1 Score |
| :--- | :--- | :--- | :--- | :--- |
| **Decision Tree (DT)** | **89.72%** | 90.24% | **91.33%** | **0.9078** |
| **k-Nearest Neighbors (kNN)** | 88.60% | **91.56%** | 87.50% | 0.8948 |
| **Support Vector Machine (SVM)** | 84.02% | 88.29% | 82.06% | 0.8506 |

## 🔍 Key Insights & Feature Importance
Using **SHAP (SHapley Additive exPlanations)** analysis, the study identified the most influential soft skills:
1.  **General Appearance:** The top predictor for employability.
2.  **Mental Alertness:** Highly significant in classifying employable students.
3.  **Ability to Present Ideas:** Critical for positive classification.
4.  **Communication Skills & Manner of Speaking:** Essential competencies prioritized by employers.

*Note: Academic performance and physical condition were found to have a lower impact compared to cognitive and communication-related skills.*

## ⚠️ Limitations
*   Reliance on secondary, assessment-based data which may contain bias.
*   Exclusion of technical skills, work experience, and academic specialization.

## 🔮 Future Work
*   Incorporating longitudinal data to track skill development over time.
*   Exploring ensemble models (e.g., Random Forest) to further improve accuracy.
*   Developing a practical assessment system for educational institutions to provide student recommendations.

## 👥 Authors
*   **Abdulkarim, Hamad D.**
*   **Macarandas, Rohaimah S.**
*   **Ms. Norniña J. Dia** (Instructor)
*   *Mindanao State University - College of Information and Computing Sciences (May 2026)*
