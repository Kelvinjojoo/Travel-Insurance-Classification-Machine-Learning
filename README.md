# ✈️ Travel Insurance Classification using Machine Learning

Welcome to the **Travel Insurance Classification** project! This project is built to predict whether a customer will purchase travel insurance based on their personal and travel-related information. It’s a hands-on machine learning pipeline — from data cleaning to model deployment — designed to offer real-world classification insights.

---

## 📘 Introduction

The travel insurance claim process often presents challenges for insurance companies due to the high volume of claims and various influencing factors, which can lead to slower decision-making and increased risk of errors. On the other hand, customers expect a fast and accurate process. In this context, the application of Machine Learning (ML) becomes crucial, as ML can quickly and accurately analyze large amounts of historical data to predict claim outcomes.

ML enables insurance companies to:

- **Accelerate the claims process:** Automated decisions can significantly reduce customer waiting times.  
- **Reduce human errors:** With data-driven predictions, the risk of manual errors decreases, especially in complex claim cases.  
- **Improve operational efficiency:** Insurance teams can focus on more complicated claims, while simpler claims are processed automatically.

The impact of this implementation includes increased customer satisfaction, better service efficiency, and reduced operational costs. In addition, companies can strengthen customer trust by providing more responsive and reliable services.

---

## 📊 Dataset Description

The dataset includes customer demographics, policy details, and claim status. Key features include:

- **Agency** – Code of the travel agency managing the insurance  
- **Agency Type** – Type of Travel Agency  
- **Distribution Channel** – How the product is sold  
- **Product Name** – Name of the insurance product sold  
- **Claim** – Insurance claim status (Target: 0 = No, 1 = Yes)  
- **Duration** – Travel duration in days  
- **Destination** – Destination country  
- **Net Sales** – Net sales of the insurance  
- **Commission** – Commission received by the insurance agent  
- **Gender** – Gender of the policyholder  
- **Age** – Age of the policyholder  

---

## 📈 Results

- **Best Performing Model**: **CatBoost Classifier**
- **Accuracy Achieved**: **72.05%**
- **Confusion Matrix**:

```
[[ 82 45]
[26 101]]
Classification Report:
            precision    recall  f1-score   support

         0       0.76      0.65      0.70       127
         1       0.69      0.80      0.74       127

  accuracy                           0.72       254
 macro avg       0.73      0.72      0.72       254
```

