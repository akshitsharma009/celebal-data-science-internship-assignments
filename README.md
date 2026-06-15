# Celebal Data Science Internship Assignments

This repository contains my weekly assignments, projects, and practical implementations completed during the **Celebal Technologies Data Science Internship**.

---

# Repository Structure

```text
celebal-data-science-internship-assignments/
│
├── week-1-ML-Foundations/
├── week-2-ml-pipeline/
├── week-3-customer-intelligence/
├── week-4-cifar10-image-classification/
├── README.md
└── requirements.txt
```

---

# Week 1 — ML Foundations ✅

## Topics Covered

* Python Fundamentals
* NumPy
* Pandas
* Linear Algebra
* Statistics
* Probability Theory
* Model Monitoring Concepts

## Key Work Completed

* Implemented Python functions, control flow, exception handling, and lambda functions
* Worked with NumPy arrays, reshaping, indexing, slicing, and matrix operations
* Performed data analysis using Pandas
* Applied Linear Algebra concepts including vectors, matrix multiplication, eigenvalues, eigenvectors, and Singular Value Decomposition (SVD)
* Performed descriptive and inferential statistical analysis
* Implemented hypothesis testing and correlation analysis
* Explored Central Limit Theorem and probability distributions
* Implemented Population Stability Index (PSI) for model monitoring
* Applied Bayes’ Theorem and conditional probability concepts

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* SciPy
* Statsmodels

---

# Week 2 — Machine Learning Pipeline (Tesla Deliveries Forecasting) ✅

## Project Overview

Built a complete Machine Learning pipeline using Tesla vehicle delivery data from 2015–2025.

The project demonstrates the complete workflow from data preprocessing to model training and evaluation.

## Key Work Completed

* Data loading and validation
* Missing value handling
* Exploratory Data Analysis (EDA)
* Feature engineering
* Data preprocessing pipeline
* Train-test split
* Model training
* Cross-validation
* Performance evaluation
* Model comparison
* Result visualization

## Dataset

Tesla Deliveries Dataset (2015–2025)

## Libraries Used

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

# Week 3 — Customer Intelligence System Using Clustering ✅

## Project Overview

Developed a Customer Intelligence System using clustering techniques to segment countries based on socio-economic and health indicators.

The objective was to identify meaningful country groups and generate actionable insights.

## Techniques Implemented

### K-Means Clustering

* Elbow Method
* Cluster Formation
* Silhouette Score Evaluation

### DBSCAN

* Density-Based Clustering
* Outlier Detection

### PCA

* Dimensionality Reduction
* Cluster Visualization

## Key Work Completed

* Data Cleaning
* Exploratory Data Analysis
* Correlation Analysis
* Feature Scaling
* K-Means Clustering
* DBSCAN Clustering
* PCA Visualization
* Cluster Profiling
* Insight Generation

## Key Findings

### Cluster 0

* High income countries
* High GDP per capita
* High life expectancy
* Low child mortality

### Cluster 1

* Underdeveloped countries
* Low income
* Low GDP per capita
* High child mortality

### Cluster 2

* Developing countries
* Moderate income levels
* Average socio-economic indicators

## Dataset

Country Data Dataset

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

# Week 4 — CIFAR-10 Image Classification (ANN vs CNN) ✅

## Project Overview

Built and compared Artificial Neural Network (ANN) and Convolutional Neural Network (CNN) models on the CIFAR-10 image classification dataset.

The project focuses on understanding how different deep learning architectures perform on image data and how training strategies influence model performance.

## Objectives

* Build an ANN model for image classification
* Build a CNN model for image classification
* Compare ANN and CNN performance
* Analyze learning curves and validation accuracy
* Experiment with training optimization strategies
* Understand the importance of feature extraction in image recognition

## Dataset

### CIFAR-10 Dataset

Classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

Dataset Size:

* 50,000 Training Images
* 10,000 Test Images
* Image Size: 32 × 32 × 3

## Models Implemented

### Artificial Neural Network (ANN)

Features:

* Dense Layers
* ReLU Activation
* Dropout Regularization
* Softmax Output Layer

Result:

* Test Accuracy: **42.79%**

### Convolutional Neural Network (CNN)

Features:

* Convolution Layers
* Batch Normalization
* Max Pooling Layers
* Dropout Regularization
* Dense Classification Layer

Result:

* Test Accuracy: **67.93%**

## Advanced Training Experiments

### CNN with Increased Epochs (20 Epochs)

Result:

* Test Accuracy: **69.11%**

### CNN with Early Stopping

Result:

* Test Accuracy: **71.26%**

### CNN with Data Augmentation

Techniques Used:

* Random Flip
* Random Rotation
* Random Zoom

Result:

* Test Accuracy: **64.24%**

## Performance Comparison

| Model                   | Test Accuracy |
| ----------------------- | ------------- |
| ANN                     | 42.79%        |
| CNN                     | 67.93%        |
| CNN (20 Epochs)         | 69.11%        |
| CNN + Early Stopping    | 71.26%        |
| CNN + Data Augmentation | 64.24%        |

## Key Findings

* ANN treats images as flattened vectors and struggles to capture spatial information.
* CNN automatically learns image features through convolution operations.
* CNN significantly outperformed ANN on CIFAR-10 classification.
* Increasing epochs improved performance but also increased training time.
* Early Stopping achieved the best overall generalization performance.
* Data Augmentation improved model robustness but required additional training for optimal results.

## Libraries Used

* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib

---

# Skills Demonstrated

* Python Programming
* Data Analysis
* Statistics
* Probability Theory
* Machine Learning
* Deep Learning
* Artificial Neural Networks (ANN)
* Convolutional Neural Networks (CNN)
* Computer Vision
* Data Preprocessing
* Feature Engineering
* Model Evaluation
* Clustering
* PCA
* Data Visualization
* End-to-End ML Pipelines

---

# Tools Used

* Python
* Jupyter Notebook
* Google Colab
* VS Code
* Git
* GitHub
* Anaconda

---

# Author

**Akshit Sharma**

Data Science Intern

Celebal Technologies
