# PRODIGY_DS_03 — Decision Tree Classifier

## 📌 Project Overview

This project was completed as **Task 3** of my Data Science Internship at **Prodigy InfoTech**.

The objective is to build a Decision Tree Classifier using the Bank Marketing dataset to predict whether a customer will subscribe to a term deposit based on their demographic and marketing-related information.

## 🎯 Objective

- Build a Decision Tree Classification model.
- Preprocess the dataset and encode categorical variables.
- Train and evaluate the model using training and testing datasets.
- Visualize the confusion matrix and decision tree.

## 📂 Dataset

**Dataset:** Bank Marketing Dataset

The dataset contains customer information and details about marketing campaigns.

Some of the features include:
- Age
- Job
- Marital status
- Education
- Account balance
- Housing loan
- Personal loan
- Contact method
- Campaign information
- Previous campaign outcome

**Target variable:** `y`
- `yes` — Customer subscribed to a term deposit.
- `no` — Customer did not subscribe to a term deposit.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Project Workflow

1. Loaded the Bank Marketing dataset.
2. Explored the dataset using summary statistics and data-quality checks.
3. Checked for missing values and duplicate records.
4. Separated the input features and target variable.
5. Converted the target variable into numerical values.
6. Applied one-hot encoding to categorical features.
7. Split the data into training and testing sets.
8. Trained a Decision Tree Classifier with a maximum depth of 5.
9. Evaluated the model using accuracy, precision, recall, and F1-score.
10. Visualized the confusion matrix and decision tree.

## 📊 Model Performance

**Model:** Decision Tree Classifier

**Test Accuracy:** 89.84%

| Metric | No Subscription | Subscription |
|---|---:|---:|
| Precision | 0.91 | 0.64 |
| Recall | 0.98 | 0.30 |
| F1-score | 0.94 | 0.41 |

### Key Observation

The model performs well in identifying customers who do not subscribe. However, its recall for customers who subscribe is relatively low at 30%. This indicates that the model misses many actual subscribers despite achieving high overall accuracy.

Further improvements could include class balancing, hyperparameter tuning, and evaluating additional classification metrics.

## 📈 Visualizations

The project includes:
- Confusion matrix heatmap
- Decision tree visualization

These visualizations help explain the model's predictions and classification performance.

## ▶️ How to Run

1. Open the notebook `PRODIGY_DS_03.ipynb` in Google Colab or Jupyter Notebook.
2. Run the cells in order.
3. Load the Bank Marketing dataset using the dataset-loading code.
4. Train the model and review the evaluation results and visualizations.

## ✅ Conclusion

This project demonstrates how a Decision Tree Classifier can be used to predict customer subscription behavior. The model achieved **89.84% test accuracy**, while the classification report highlighted the need to improve the identification of actual subscribers.

## 👩‍💻 Internship

**Organization:** Prodigy InfoTech  
**Program:** Data Science Internship  
**Task:** Task 3 — Decision Tree Classifier

#ProdigyInfoTech #DataScience #Python #MachineLearning #DecisionTree #Classification
