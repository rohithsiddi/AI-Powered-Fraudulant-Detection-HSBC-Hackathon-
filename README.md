# AI-Powered Fraud Detection System

## Project Overview
- This project develops an AI model capable of detecting fraudulent transactions in real-time. It leverages historical transaction data to train the model, allowing it to identify anomalies and flag suspicious activities effectively.
- This project was part of a hackathon conducted by HSBC.

## Objectives
- Implement and deploy a model that accurately detects fraudulent transactions with minimal false positives.
- Achieve high precision and recall metrics, ensuring robust fraud detection capabilities with minimal impact on genuine transactions.

## Dataset Analysis
The dataset comprised historical transaction data. Extensive exploratory data analysis (EDA) was conducted to understand the underlying patterns and anomalies in the data. This analysis informed subsequent data preprocessing and feature engineering steps, enhancing model accuracy and reliability.

## Data Preprocessing
- **Data Cleaning:** Removed irrelevant features, handled missing values, and corrected anomalies in the dataset.
- **Feature Engineering:** Developed new features that significantly improved the model’s ability to distinguish between fraudulent and genuine transactions.

## Model Development
- **Machine Learning Techniques Used:**
  - **Bagging:** Utilized Random Forest to reduce variance and prevent overfitting, ensuring robust performance across diverse scenarios.
  - **Boosting:** Applied XGBoost to sequentially build models that correct the predecessors' errors, focusing on difficult cases to improve overall accuracy.
  - **Hyperparameter Tuning:** Employed Optuna to systematically search for the optimal hyperparameters, significantly enhancing the models' performance.
- **Model Evaluation:**
  - Achieved a precision of **97%**, indicating a high rate of accurately identified fraud cases.
  - Attained a recall of **85%**, ensuring that the majority of fraudulent transactions were detected.

## Results
- **Precision:** 97% (High accuracy in predicting fraudulent transactions)
- **Recall:** 85% (Effective in capturing a significant proportion of fraudulent activities)
- The model demonstrates a strong balance between precision and recall, effectively addressing the challenge of fraud detection in transaction data.

## Technologies Used
- **Python:** Main programming language for data analysis and model building.
- **Pandas & NumPy:** For data manipulation and numerical calculations.
- **Scikit-learn:** Employed for model development and evaluation.
- **Matplotlib & Seaborn:** For visualizing data and insights.


## Conclusion
The AI-powered fraud detection system developed during this hackathon effectively detects fraudulent transactions with high precision and recall, minimizing false positives while ensuring comprehensive fraud coverage. This system is poised for further refinement and real-world implementation.
