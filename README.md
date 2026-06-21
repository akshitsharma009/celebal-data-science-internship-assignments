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
├── week-5-text-generation-rnn-lstm-gru/
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

## Performance Comparison

| Model                   | Test Accuracy |
| ----------------------- | ------------- |
| ANN                     | 42.79%        |
| CNN                     | 67.93%        |
| CNN (20 Epochs)         | 69.11%        |
| CNN + Early Stopping    | 71.26%        |
| CNN + Data Augmentation | 64.24%        |

## Key Findings

* CNN significantly outperformed ANN on image classification tasks.
* Early Stopping achieved the best performance.
* CNN effectively captured spatial image features.
* Data augmentation improved robustness but required additional training.

## Libraries Used

* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib

---

# Week 5 — Text Generation using RNN, LSTM & GRU ✅

## Project Overview

Built and compared three sequence learning architectures: Vanilla RNN, LSTM, and GRU for next-word prediction and text generation.

The project focuses on understanding how recurrent neural networks learn language patterns, grammar, contextual dependencies, and sequence information from text data.

## Objectives

* Build a Vanilla RNN model
* Build an LSTM model
* Build a GRU model
* Compare sequence learning capabilities
* Generate text using trained models
* Analyze training loss behavior

## Dataset

### Custom Text Corpus

A custom text corpus was used for:

* Tokenization
* Sequence Creation
* Next Word Prediction
* Text Generation

## Models Implemented

### Vanilla RNN

* Embedding Layer
* SimpleRNN Layer
* Dense Output Layer

### LSTM

* Embedding Layer
* LSTM Layer
* Dense Output Layer

### GRU

* Embedding Layer
* GRU Layer
* Dense Output Layer

## Beginner Tasks Completed

### Task 1

* Replaced the original corpus with a custom paragraph

### Task 2

* Increased embedding dimension from 32 to 64

### Task 3

* Increased training epochs from 100 to 200

### Task 4

* Increased hidden units from 64 to 128

### Task 5

* Generated 10 words instead of 5 during text generation

## Key Findings

* Vanilla RNN learned basic sequential patterns but struggled with long-term memory.
* LSTM generated more coherent text by preserving contextual information.
* GRU achieved performance similar to LSTM with fewer parameters.
* Increasing embedding dimensions improved word representations.
* Higher epochs reduced training loss and improved learning.
* Larger hidden layers improved model capacity.
* LSTM and GRU handled long-term dependencies significantly better than Vanilla RNN.

## Libraries Used

* TensorFlow
* Keras
* NumPy
* Matplotlib
* Pandas

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
* Recurrent Neural Networks (RNN)
* Long Short-Term Memory (LSTM)
* Gated Recurrent Units (GRU)
* Natural Language Processing (NLP)
* Text Generation
* Sequence Modeling
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
