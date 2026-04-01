# Week 1 Day 1 - Homework

## Mapping the ML Universe

---

# Exercise A: Classify Real-World ML Problems

| Scenario                                            | Problem Type   | Input Features                         | Output                 |
| --------------------------------------------------- | -------------- | -------------------------------------- | ---------------------- |
| Predict whether a loan applicant will default       | Classification | Credit score, income                   | Default or Not Default |
| Forecast next month's energy consumption for a city | Regression     | Past energy usage, weather temperature | Amount of energy used  |
| Group customers by purchasing behavior              | Clustering     | Purchase frequency, total spending     | Customer groups        |
| Detect fraudulent credit card transactions          | Classification | Transaction amount, location           | Fraud or Not Fraud     |
| Generate product descriptions from an image         | Generative     | Product image, product type            | Text description       |
| Predict severity (1–5) of a patient's condition     | Classification | Heart rate, symptoms                   | Severity level (1–5)   |

---

# Exercise B: ML Lifecycle

### 1. Problem Definition

The goal is to build a model that predicts whether a patient admitted to the ER will be readmitted within 30 days. Doctors can use this prediction to identify high-risk patients and provide additional care.

### 2. Data Collection

Data can be collected from hospital databases such as patient age, diagnosis, treatment history, length of hospital stay, and whether the patient was readmitted within 30 days.

### 3. EDA & Preprocessing

Analyze the data to find missing values, incorrect records, or duplicates. Clean the data and prepare it for machine learning models.

### 4. Model Training

Train different machine learning models and choose the one that performs best.

### 5. Evaluation

Check if the model works well using test data. Use metrics like precision and recall to see if the model correctly identifies high-risk patients.

### 6. Deployment

Integrate the model into the hospital system so doctors can see the patient's readmission risk.

### 7. Monitoring

Monitor the model regularly and retrain it if the performance decreases over time.

---

# Exercise C: AI vs ML vs Deep Learning Sorting

### 1. Chess Engine

**Type:** Rule-based AI  
**Explanation:** The rules and evaluation logic are written manually by humans.

---

### 2. Spam Filter (Random Forest)

**Type:** Classical ML  
**Explanation:** The model learns patterns from a large dataset of labeled emails.

---

### 3. GPT-4

**Type:** Deep Learning  
**Explanation:** It uses a large neural network trained on massive text data to generate responses.

---

### 4. Netflix Recommendation System

**Type:** Classical ML  
**Explanation:** It Learns from user watching history.

---

### 5. Thermostat with Time Rules

**Type:** Rule-based AI  
**Explanation:** The system follows predefined rules created by humans.

---

### 6. CNN for Tumor Detection

**Type:** Deep Learning  
**Explanation:** A convolutional neural network learns features from medical images.

---

### 7. Credit Card Approval (Decision Tree)

**Type:** Classical ML  
**Explanation:** Learns decision rules from past data.
