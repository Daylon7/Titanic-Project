# 🚀 Titanic Survival Prediction Project 🚢

## Description

This project is part of the **Data Science Bootcamp** and serves as a comprehensive application of the techniques and methodologies learned throughout the course. Leveraging the widely-known **Titanic dataset**, we follow the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework to develop a robust predictive model that determines whether a passenger survived the Titanic disaster.

## 1. **Business Understanding** 🎯
In this phase, we define the project's objectives, scope, and success criteria. The primary goal is to predict passenger survival with high evaluations metrics, which can provide insights into the factors that influenced survival rates during the Titanic disaster.

## 2. **Data Understanding** 📂
This phase involves exploring the dataset to gain insights into its structure, quality, and potential challenges. We perform exploratory data analysis (EDA) to understand the relationships between variables and identify missing values

## 3. **Data Preparation** 🧹
Data preparation is a critical step to ensure the dataset is clean, consistent, and ready for modeling. We apply various preprocessing techniques to handle missing values, encode categorical variables, and normalize numerical features.

**Key Steps:**
- Handling missing values through replaces.
- Encoding categorical variables using **One-Hot Encoding** and **Label Encoding**.
- Feature scaling using **StandardScaler**.
- Creating new features, such as extracting titles from passengers names.
- PCA to reduce dimensionality according to correlations variables.
- Outliers reduction and identification with Isolation Forest.

## 4. **Modeling** 🤖

In this phase, we experiment with multiple machine learning algorithms to identify the best-performing model. We focus on interpretability, accuracy, and generalization capabilities.

**Algorithms Applied:**

- **Random Forest**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**

**Model Tuning:**
- Hyperparameter optimization using **RandomizedSearchCV**.

## 5. **Evaluation** 📏
We evaluate the models using a variety of metrics to ensure they meet the project's objectives. The evaluation phase helps us select the best model for deployment.

**Evaluation Metrics:**
- **Precision**: Proportion of true positives among predicted positives.
- **Recall**: Proportion of true positives among actual positives.
- **F1-Score**: Harmonic mean of precision and recall.
- **AUC-ROC**: Area under the receiver operating characteristic curve.

**Key Insights:**
- Random Forest is the best model to predict.
- PCA and Outliers reduction does not improve the perfomance of the model significantly.

## 6. **Implementation** 🚀
The final phase involves deploying the selected model into a production environment. While this step is beyond the scope of the current project, it is essential for real-world applications.

**Future Steps:**
- Improve Feature Engineering.
- Deployment using frameworks like **Flask**.
- Integration with a web application or dashboard.
