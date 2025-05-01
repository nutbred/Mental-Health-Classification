# Machine Learning Classification of Mental Health Conditions: Bipolar I Disorder, Bipolar II Disorder, Depression, and Healthy Individuals.

## Project Overview

This project was developed as the final assignment for the **Introduction to Programming** course. It explores the application of Machine Learning techniques to the task of classifying mental health conditions, specifically focusing on differentiating between Bipolar I Disorder, Bipolar II Disorder, Major Depression, and healthy individuals.

The project addresses the limitations of traditional diagnostic methods by leveraging Machine Learning's capability for rapid and accurate data analysis. The primary goal was to build a proof-of-concept tool to support automated diagnosis by classifying these distinct groups based on patient data.

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
* [Optional: Briefly mention or link to specific results or charts if available in the repo]

## Application and Future Improvements

This project serves as an introduction to applying programming and machine learning to complex real-world problems like mental health diagnosis.

* **Potential Application:** The developed models demonstrate the potential for ML to serve as a supportive tool in clinical diagnosis by providing automated classification based on data.
* **Future Improvements:** Discuss potential areas for further development, such as:
    * Using a larger and more diverse dataset.
    * Exploring additional machine learning algorithms.
    * More advanced feature engineering techniques.
    * Implementing cross-validation rigorously.
    * Deploying the model as a simple web application (beyond the scope of an intro course, but a future direction).

## Technologies Used

* [Programming Language, e.g., Python]
* Relevant Libraries (e.g., scikit-learn, pandas, numpy, matplotlib, seaborn - list the ones you actually used)

## Getting Started

[Optional: Add instructions on how to clone the repository and run the code if applicable. Example below]

1.  Clone the repository:
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3.  Install dependencies:
    ```bash
    pip install -r requirements.txt # (If you created a requirements.txt)
    ```
    or list individual packages:
    ```bash
    pip install scikit-learn pandas numpy etc.
    ```
4.  Run the main script:
    ```bash
    python your_main_script.py # (Replace with your actual script name)
    ```

## License

[Choose a license, e.g., MIT License - you can add a LICENSE file to your repo]
This project is licensed under the [Name of License] - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Introduction to Programming Course
* [Name of Professor/TA, if you want to acknowledge them]
* [Mention source of dataset if it wasn't created by you for the project]