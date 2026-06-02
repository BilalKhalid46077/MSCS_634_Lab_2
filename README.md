# MSCS_634_Lab_2

# K-Nearest Neighbors (KNN) and Radius Neighbors Classification Lab

## Project Overview
This project demonstrates the implementation and analysis of two machine learning classification algorithms: **K-Nearest Neighbors (KNN)** and **Radius Neighbors Classifier (RNN)** using the Wine Dataset from sklearn.

The goal of this lab is to understand how different parameter values (K in KNN and radius in RNN) affect model performance and accuracy.

---

## Dataset Used
The Wine dataset from sklearn contains chemical properties of different wine samples and classifies them into three categories.

- Number of classes: 3  
- Number of features: 13  
- Type: Multiclass classification dataset  

---

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Steps

### 1. Data Loading & Exploration
- Loaded Wine dataset using `sklearn.datasets`
- Converted dataset into Pandas DataFrame
- Explored dataset using:
  - `head()`
  - `value_counts()`
  - basic structure analysis

---

### 2. Data Preprocessing
- Split dataset into:
  - 80% Training data
  - 20% Testing data
- Applied feature scaling using **StandardScaler** to normalize data for distance-based algorithms

---

### 3. K-Nearest Neighbors (KNN)
- Implemented KNN classifier
- Tested different values of K:
  - 1, 5, 11, 15, 21
- Measured accuracy for each K value
- Observed how model performance changes with different neighbors

---

### 4. Radius Neighbors Classifier (RNN)
- Implemented Radius Neighbors Classifier
- Tested different radius values:
  - 350, 400, 450, 500, 550, 600
- Evaluated accuracy for each radius
- Compared performance across different radius settings

---

### 5. Data Visualization
- Plotted accuracy trends for KNN vs K values
- Plotted accuracy trends for RNN vs radius values
- Visualized how parameter tuning affects model performance

---

## Key Insights
- The value of K significantly affects KNN accuracy
- Too small K may cause noise, while large K may oversmooth results
- RNN performance depends heavily on the selected radius
- Proper parameter tuning improves model accuracy
- Feature scaling is essential for distance-based models

---

## Challenges Faced
- Selecting optimal values for K and radius
- Understanding effect of scaling on model performance
- Interpreting accuracy trends from graphs

---

## Results Summary
- Best performing K value varies depending on dataset distribution
- RNN shows sensitivity to radius selection
- KNN generally provides more stable performance compared to RNN

---
