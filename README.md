# K-Nearest Neighbors Classification on Iris Dataset

This project demonstrates the implementation of a **K-Nearest Neighbors (KNN)** classifier using the classic **Iris flower dataset**. The goal is to classify iris flowers into three species based on their sepal and petal measurements.

---

# Dataset Description

The Iris dataset is a multivariate dataset introduced by Ronald Fisher. It contains 150 samples with the following features:

- **sepal length (cm)**  
- **sepal width (cm)**  
- **petal length (cm)**  
- **petal width (cm)**  
- **target** (0 = Setosa, 1 = Versicolor, 2 = Virginica)

---

#  Project Workflow

### 1. Data Loading & Exploration
- Loaded the Iris dataset using `sklearn.datasets.load_iris()`
- Converted it into a `pandas DataFrame`
- Mapped target values to their respective flower names

### 2. Data Visualization
- **Sepal Length vs Sepal Width** (Setosa vs Versicolor)  
- **Petal Length vs Petal Width** (Setosa vs Versicolor)  
- Used `matplotlib` for scatter plots to visually explore the separability of classes

### 3. Model Building
- Split the data using `train_test_split()` (80% training, 20% testing)
- Used `KNeighborsClassifier` with `n_neighbors=3`
- Trained the model using `fit()` and evaluated using `score()`

### 4. Evaluation
- Achieved **95% accuracy** on training data
- Evaluated performance on test data using:
  - **Confusion Matrix**
  - **Classification Report**
  - **Heatmap using Seaborn**

---

#  Confusion Matrix
 This indicates that the model performs very well in predicting the correct flower species.

---





