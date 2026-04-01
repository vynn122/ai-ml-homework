# Week 1 Day 1 - Homework Assignment

## Mapping the ML Universe

---

# Exercise A: Classify Real-World ML Problems

| Scenario                                            | Problem Type   | Input Features                                | Output                                       |
| --------------------------------------------------- | -------------- | --------------------------------------------- | -------------------------------------------- |
| Predict whether a loan applicant will default       | Classification | Credit score, annual income                   | Default / Not Default                        |
| Forecast next month's energy consumption for a city | Regression     | Historical energy usage, temperature forecast | Predicted energy consumption (numeric value) |
| Group customers by purchasing behavior              | Clustering     | Purchase frequency, average spending          | Customer groups/segments                     |
| Detect fraudulent credit card transactions          | Classification | Transaction amount, location                  | Fraud / Not Fraud                            |
| Generate product descriptions from an image         | Generative     | Product image, product category               | Generated product description text           |
| Predict the severity (1–5) of a patient's condition | Classification | Vital signs, symptoms                         | Severity level (1–5)                         |

---

# Exercise B: Map the ML Lifecycle

### 1. Problem Definition

The hospital wants to predict which patients admitted to the ER are at high risk of being readmitted within 30 days. The goal is to help doctors identify high-risk patients early so they can provide additional care or monitoring to reduce readmissions.

### 2. Data Collection

The hospital can collect historical patient records such as age, medical history, diagnosis codes, treatments, medications, and previous admissions. Data from several years should be used to ensure enough examples of readmitted and non-readmitted patients.

### 3. EDA & Preprocessing

Exploratory Data Analysis (EDA) would help identify missing values, inconsistencies, or outliers in the medical records. Categorical features such as diagnosis codes may need to be encoded into numerical form so they can be used by machine learning models.

### 4. Model Training

The team could start with simple and interpretable models such as logistic regression or decision trees. These models allow healthcare professionals to understand why the model predicts a patient as high-risk.

### 5. Evaluation

Accuracy alone may be misleading if only a small percentage of patients are readmitted. Metrics such as precision, recall, and F1-score would better measure how well the model identifies high-risk patients.

### 6. Deployment

The model could be integrated into the hospital’s electronic health record system. When a patient is admitted to the ER, the system would generate a readmission risk score that doctors or nurses can review.

### 7. Monitoring

The model’s performance should be monitored over time because patient populations and medical practices can change. If prediction accuracy decreases, the model may need to be retrained with newer data.

---

# Exercise C: AI vs ML vs Deep Learning Sorting

| System                                                                 | Type          | Explanation                                                                                     |
| ---------------------------------------------------------------------- | ------------- | ----------------------------------------------------------------------------------------------- |
| A chess engine with hand-crafted evaluation function                   | Rule-based AI | The rules and evaluation logic are manually programmed by humans rather than learned from data. |
| A spam filter trained on 10 million labeled emails using random forest | Classical ML  | The model learns patterns from labeled email data using a machine learning algorithm.           |
| GPT-4 generating text responses                                        | Deep Learning | It uses large neural networks trained on massive text data to generate human-like responses.    |
| Netflix collaborative filtering recommendation engine                  | Classical ML  | It learns user preferences from historical interaction data using mathematical models.          |
| A thermostat that adjusts temperature based on time-of-day rules       | Rule-based AI | The system follows predefined rules created by humans instead of learning from data.            |
| A CNN that detects tumors in medical images                            | Deep Learning | Convolutional neural networks automatically learn image features from large datasets.           |
| A decision tree approving/rejecting credit card applications           | Classical ML  | The decision tree learns patterns from historical application data to make decisions.           |
