# Breast Cancer Big Data & Machine Learning Project

# Overview

This project is a complete Machine Learning and Big Data solution for Breast Cancer classification using both traditional Machine Learning algorithms and Apache Spark Big Data technologies.

The project demonstrates the full Data Science workflow starting from:

- Data collection
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Machine Learning model building
- Model evaluation
- ROC-AUC analysis
- Big Data processing with PySpark
- Distributed Machine Learning using Spark MLlib

The notebook is divided into multiple sections to explain each stage step-by-step in a practical and educational way.

---

# Objectives

The main goals of this project are:

- Understand Breast Cancer datasets and medical classification problems
- Apply Data Science preprocessing techniques
- Build Machine Learning classification models
- Evaluate model performance using advanced metrics
- Understand Big Data processing using Apache Spark
- Compare Scikit-learn models with Spark MLlib models
- Visualize classification performance using ROC Curve and Confusion Matrix

---

# Dataset Information

The project uses the Breast Cancer Wisconsin Dataset available from Scikit-learn.

Dataset characteristics:

| Property | Value |
|---|---|
| Type | Classification |
| Classes | Benign / Malignant |
| Features | 30 numerical features |
| Samples | 569 |
| Source | Scikit-learn datasets |

Target classes:

- Malignant (Cancerous)
- Benign (Non-cancerous)

The dataset contains several medical measurements extracted from breast mass images.

---

# Technologies Used

## Programming Language
- Python 3

## Libraries
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PySpark
- Jupyter Notebook

## Big Data Framework
- Apache Spark
- Spark MLlib

---

# Project Structure

```text
├── Breast_Cancer_BigData_ML_Project_4Parts_Final.ipynb
├── README.md
├── requirements.txt
```

---

# Machine Learning Workflow

# 1. Data Loading

The dataset is loaded using Scikit-learn datasets module.

Main steps:
- Import dataset
- Convert dataset into Pandas DataFrame
- Display features and target values

---

# 2. Exploratory Data Analysis (EDA)

The project explores:
- Dataset shape
- Missing values
- Feature distributions
- Statistical summaries
- Target class balance

EDA helps understand the dataset before model training.

---

# 3. Data Preprocessing

Several preprocessing techniques are applied:

## Feature Scaling
Using:
- StandardScaler

Purpose:
- Normalize feature values
- Improve model performance
- Prevent feature dominance

## Train/Test Split
The dataset is divided into:
- Training set
- Testing set

Typical split ratio:
- 80% training
- 20% testing

---

# 4. Machine Learning Model

The project uses:

## Random Forest Classifier

Random Forest is an ensemble Machine Learning algorithm based on multiple decision trees.

Advantages:
- High accuracy
- Handles overfitting well
- Works efficiently with classification problems
- Suitable for medical datasets

---

# 5. Model Training

The model is trained using:
- Scikit-learn RandomForestClassifier

Training steps:
1. Fit the model on training data
2. Predict test data
3. Evaluate predictions

---

# 6. Model Evaluation

The project evaluates performance using several important metrics.

## Accuracy

Measures total correct predictions.

## Precision

Measures how many predicted positive cases are actually positive.

## Recall

Measures how many actual positive cases are correctly detected.

## F1-Score

Harmonic mean of Precision and Recall.

## ROC-AUC Score

Measures classification quality across multiple thresholds.

## Confusion Matrix

Shows:
- True Positives
- True Negatives
- False Positives
- False Negatives

---

# ROC Curve Analysis

The notebook includes ROC Curve visualization to analyze classification performance.

ROC analysis helps:
- Compare model thresholds
- Measure sensitivity vs specificity
- Evaluate overall classifier quality

---

# Big Data Processing Using PySpark

The project also demonstrates Big Data concepts using Apache Spark.

Main Spark tasks:
- Create SparkSession
- Convert data into Spark DataFrame
- Feature Vector Assembling
- Distributed model training
- Spark MLlib classification

---

# Spark MLlib Workflow

## SparkSession Creation

SparkSession initializes the Spark environment.

## Vector Assembler

Combines features into a single vector column for Spark MLlib.

## Random Forest in Spark

Uses:
- pyspark.ml.classification.RandomForestClassifier

Advantages:
- Distributed processing
- Handles larger datasets
- Faster scalable computation

---

# Visualizations Included

The notebook contains visualizations such as:

- Confusion Matrix
- ROC Curve
- Classification metrics
- Data distribution analysis

Visualization helps better understand:
- Model performance
- Data patterns
- Prediction quality

---

# Installation Guide

# Step 1: Clone Repository

```bash
git clone <repository-url>
```

# Step 2: Navigate to Project Folder

```bash
cd <project-folder>
```

# Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running The Project

# Open Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```bash
Breast_Cancer_BigData_ML_Project_4Parts_Final.ipynb
```

Run all notebook cells sequentially.

---

# Requirements

The required libraries are:

```txt
numpy
pandas
matplotlib
scikit-learn
pyspark
jupyter
notebook
```

---

# Expected Outputs

After running the notebook successfully, you will obtain:

- Trained Machine Learning model
- Prediction results
- Classification reports
- Accuracy metrics
- ROC-AUC score
- Confusion Matrix visualization
- Spark MLlib results
- Big Data workflow demonstration

---

# Educational Value

This project is useful for learning:

## Machine Learning
- Classification algorithms
- Model evaluation
- Feature scaling
- Data preprocessing

## Data Science
- Exploratory Data Analysis
- Visualization techniques
- Performance metrics

## Big Data
- Apache Spark fundamentals
- PySpark DataFrames
- Distributed Machine Learning

---

# Possible Future Improvements

Future enhancements may include:

- Deep Learning implementation
- Hyperparameter tuning
- Cross-validation
- Feature selection
- Model comparison
- Streamlit deployment
- Real-time prediction API

---

# Author

## Abdo Khater

Machine Learning & Data Science Project

