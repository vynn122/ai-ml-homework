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

The hospital wants to predict if a patient will come back to the hospital within 30 days. This helps doctors know which patients need more care.

### 2. Data Collection

The hospital collects data such as patient age, illness, treatment, and past hospital visits.

### 3. EDA & Preprocessing

Check the data for missing values or errors. Clean the data and prepare it so the model can use it.

### 4. Model Training

Train a model using the data. Start with a simple model so doctors can understand the results.

### 5. Evaluation

Check if the model works well. Use metrics like precision and recall to see if the model correctly finds high-risk patients.

### 6. Deployment

Add the model to the hospital system. When a patient comes in, the system shows the risk score.

### 7. Monitoring

Check the model over time to make sure it still works well. Update the model if needed.

---

# Exercise C: AI vs ML vs Deep Learning

| System                               | Type          | Explanation                                  |
| ------------------------------------ | ------------- | -------------------------------------------- |
| Chess engine with hand-written rules | Rule-based AI | The rules are written by humans.             |
| Spam filter using random forest      | Classical ML  | The model learns from email data.            |
| GPT-4 generating text                | Deep Learning | Uses a neural network trained on large data. |
| Netflix recommendation system        | Classical ML  | Learns from user watching history.           |
| Thermostat using time rules          | Rule-based AI | Follows rules set by humans.                 |
| CNN detecting tumors in images       | Deep Learning | Neural network learns from medical images.   |
| Decision tree for credit approval    | Classical ML  | Learns decision rules from past data.        |
