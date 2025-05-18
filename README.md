# Animal Classification using K-Nearest Neighbours (KNN)

This project demonstrates classification of animal types using the K-Nearest Neighbours algorithm. It includes full preprocessing, model training, evaluation, and decision boundary visualization using PCA.

---

## 🎯 Objective

To implement and evaluate the **K-Nearest Neighbours (KNN)** algorithm for classification on a dataset of animals based on features like hair, feathers, milk, and more.

---

## 📁 Dataset Description

- Each row represents an animal with various binary features.
- Target column: `type` (animal category like mammal, bird, reptile, etc.)
- Feature column: `animal name` (used only for reference, not for training)

---

## 🧭 Project Workflow

### 1. Data Analysis & Visualization
- Visualized feature distributions using **boxplots** and **heatmaps**
- Checked for **missing values** and **outliers**

### 2. Data Preprocessing
- Dropped the non-numeric `animal name` column
- Standardized feature values using `StandardScaler`

### 3. Train-Test Split
- 80% for training, 20% for testing using `train_test_split`

### 4. KNN Model Implementation
- Trained KNN using `KNeighborsClassifier` from scikit-learn
- Set `n_neighbors=5` and `metric='euclidean'`

### 5. Model Evaluation
- Evaluated predictions using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**
  - **Confusion Matrix**

### 6. Decision Boundary Visualization
- Applied PCA to reduce features to 2D
- Visualized the decision boundary learned by KNN on the PCA-reduced test set

---

## ✅ Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (KNN, scaling, PCA, metrics)

---

## 👤 Author

**Teerth Gupta**  
Master’s Student – Statistics and Data Science  
Uppsala University, Sweden  
