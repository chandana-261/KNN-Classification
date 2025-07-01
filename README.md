# Task 6: K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
To understand and implement K-Nearest Neighbors (KNN) for solving classification problems using the Iris dataset.

## 🛠 Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 📁 Dataset Used
**Iris Dataset**  
This dataset includes measurements of iris flowers from three different species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

### Features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

### Target:
- Species (Flower type)

## 🔍 Workflow Summary

### 1. Data Preprocessing
- Dropped the unnecessary `Id` column.
- Normalized feature values using `StandardScaler`.

### 2. Model Building
- Used `KNeighborsClassifier` from `sklearn.neighbors`.
- Trained the model with values of K from 1 to 20.

### 3. Model Evaluation
- Evaluated performance using accuracy and confusion matrix.
- Identified the optimal `K` value using accuracy comparison.
- Achieved **100% accuracy** on the test set with `K=3`.

### 4. Visualization
- Plotted Accuracy vs K to select the best `K`.
- Plotted Confusion Matrix using `Seaborn`.

## ✅ Results
- **Best K value:** 3
- **Test Set Accuracy:** 100%
- **Confusion Matrix:** Perfect classification

## ▶️ How to Run

1. Make sure you have Python installed.
2. Install required libraries using pip:
```bash
pip install pandas scikit-learn matplotlib seaborn
