# Machine Learning Classification of Mental Health Conditions: Bipolar I Disorder, Bipolar II Disorder, Depression, and Healthy Individuals.
[Canva Slides](https://www.canva.com/design/DAGmMEwtm7s/Y7IgHhQyN_s81ifnqmreGg/edit?utm_content=DAGmMEwtm7s&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
## Project Overview

This project was developed as the final assignment for the **Introduction to Programming** course. It explores the application of Machine Learning techniques to the task of classifying mental health conditions, specifically focusing on differentiating between Bipolar I Disorder, Bipolar II Disorder, Major Depression, and healthy individuals.

## Data Description and Processing

This section details the dataset used and the steps taken to prepare it for machine learning models.

* **Dataset Overview:** Description of the dataset utilized for the project. The dataset comprised information from 120 patients across the target categories (Bipolar I, Bipolar II, Depression, Healthy).
* **Feature Handling:** Explanation of how features within the dataset were processed and prepared for model input.
* **Feature Relationship Visualization:** Overview of any visualizations created to understand the relationships and patterns among the different features in the dataset.

## Machine Learning Models

Two primary machine learning models were implemented and evaluated for the classification task.

### Random Forest Model

* **Concept:** Based on the decision tree algorithm, the Random Forest model aggregates results from multiple trees for improved robustness.
* **Model Overview:** Description of the Random Forest model's structure and how it was applied to the classification problem.
* **Model Training:** Details on the process of training the Random Forest classifier using the prepared dataset.

### Logistic Regression Model

* **Model Overview:** Description of the Logistic Regression model, a fundamental algorithm for classification.
* **Model Training (Binary):** Details on training a basic Logistic Regression model (if applicable, e.g., initial binary classification attempts).
* **Model Training (Multi-class with Regularization):** Explanation of training the model to handle multiple classes (Bipolar I, Bipolar II, Depression, Healthy) and the application of regularization techniques to prevent overfitting.

## Evaluation

The performance of the implemented models was evaluated to determine their effectiveness in classifying the different conditions.

* The primary metric used for evaluation was the **F1 Score**, which provides a balance between precision and recall.
