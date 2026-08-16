 Classification Model Comparison — Logistic Regression vs Random Forest

## 📌 Project Overview

This project demonstrates a complete **machine learning classification workflow** using Python and scikit-learn.

The project builds and evaluates two classification models:

* **Logistic Regression**
* **Random Forest Classifier**

The models are evaluated and compared using multiple performance metrics to determine which model performs better on the given dataset.

---

## 🎯 Project Objective

The main objective of this project is to understand and implement a practical classification workflow, including:

* Data preprocessing
* Target distribution analysis
* Feature and target separation
* Train-test splitting
* Feature scaling
* Logistic Regression
* Confusion Matrix
* ROC Curve
* Random Forest Classification
* Model evaluation
* Model comparison

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Target Distribution
   ↓
Separate Features & Target
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Model Evaluation
   ↓
Confusion Matrix
   ↓
ROC Curve
   ↓
Random Forest
   ↓
Model Comparison
   ↓
Final Model Selection
```

---

## 📊 Models Used

### 1. Logistic Regression

Logistic Regression is used as the baseline classification model.

It predicts the probability of an observation belonging to a particular class.

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC Curve
* AUC

### 2. Random Forest Classifier

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to make predictions.

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score

---

## 📈 Evaluation Metrics

### Accuracy

Measures the percentage of predictions that are correct.

```text
Accuracy = Correct Predictions / Total Predictions
```

### Precision

Measures how many predicted positive observations were actually positive.

### Recall

Measures how many actual positive observations were correctly identified.

### F1 Score

F1-score combines precision and recall into a single metric.

### Confusion Matrix

The confusion matrix shows the number of correct and incorrect predictions for each class.

### ROC Curve

The ROC curve evaluates the model's ability to distinguish between classes.

The project also calculates the **AUC (Area Under the Curve)**.

---

## 🏆 Model Comparison

The Logistic Regression and Random Forest models are compared using:

| Metric    |    Logistic Regression |          Random Forest |
| --------- | ---------------------: | ---------------------: |
| Accuracy  | Calculated in notebook | Calculated in notebook |
| Precision | Calculated in notebook | Calculated in notebook |
| Recall    | Calculated in notebook | Calculated in notebook |
| F1 Score  | Calculated in notebook | Calculated in notebook |

The final model selection is based on the evaluation results generated during the notebook execution.

---

## 📁 Project Structure

```text
classification-model-comparison/
│
├── Classification_Model_Comparison.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

### Option 1 — Google Colab

Open the `.ipynb` file using Google Colab and run the notebook cells sequentially.

### Option 2 — Local Environment

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook using Jupyter Notebook or JupyterLab.

---

## 📦 Requirements

The main libraries used in this project are:

```text
pandas
numpy
scikit-learn
matplotlib
```

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Preparing data for machine learning
* Splitting data into training and testing sets
* Scaling numerical features
* Building classification models
* Evaluating machine learning models
* Understanding confusion matrices
* Understanding ROC curves and AUC
* Comparing different machine learning algorithms
* Selecting a model based on performance metrics

---

## 🔮 Future Improvements

Possible improvements for this project include:

* Hyperparameter tuning
* Cross-validation
* Support Vector Machine (SVM)
* Feature importance analysis
* Hyperparameter optimization using GridSearchCV
* Additional classification algorithms
* Deployment of the final model

---

## 👨‍💻 Author

**Arya Marale**

This project was created as part of my practical learning journey in **Data Analysis and Machine Learning with Python**.
