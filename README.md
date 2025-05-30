# Elevate Labs Task 4: Logistic Regression Binary Classifier

This project builds a binary classification model using **Logistic Regression** on the Titanic dataset. The goal is to predict whether a passenger survived or not based on features like age, sex, fare, etc.

## 🔧 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📁 Project Structure

The task is divided into **five modules** inside the notebook `task-4.ipynb`:

### 🔹 Module 1: Dataset Preparation
- Load and clean Titanic dataset
- Encode categorical variables
- Handle missing values
- Train-test split
- Feature standardization

### 🔹 Module 2: Model Training
- Train a `LogisticRegression` model using Scikit-learn
- Predict labels and probabilities

### 🔹 Module 3: Evaluation
- Compute **confusion matrix**
- Calculate **precision**, **recall**, and **ROC AUC**
- Visualize the **ROC curve**

### 🔹 Module 4: Threshold Tuning
- Change the decision threshold (default is 0.5)
- Visualize the effect on confusion matrix

### 🔹 Module 5: Sigmoid Function Explanation
- Plot the sigmoid function
- Explain how it converts linear output to probabilities

## 💾 Dataset

The dataset used is the Titanic Dataset (`Titanic-Dataset.csv`) which includes passenger information and survival status.

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Vignesh190904/Elevate-Labs-task-4.git
   cd Elevate-Labs-task-4
