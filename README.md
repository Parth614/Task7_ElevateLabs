# 🧠 Task 7: Support Vector Machines (SVM) – Breast Cancer Classification

## 📌 Objective

The objective of this task was to implement Support Vector Machines (SVM) for binary classification using both linear and non-linear (RBF) kernels. The goal was to compare model performance, tune hyperparameters, and visualize the decision boundary.

---

## 📂 Dataset

* Dataset Used: Breast Cancer Dataset
* Type: Binary Classification (Malignant / Benign)
* Features: Multiple medical diagnostic measurements

---

## 🛠 Tools & Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔎 Steps Performed

1. Loaded and preprocessed the dataset.
2. Applied feature scaling using StandardScaler.
3. Trained SVM with:

   * Linear Kernel
   * RBF Kernel
4. Evaluated model using:

   * Accuracy Score
   * Classification Report
   * Confusion Matrix
5. Performed Hyperparameter Tuning using GridSearchCV.
6. Applied 5-fold Cross Validation.
7. Visualized decision boundary using PCA (2D transformation).

---

## 📊 Results

* Linear Kernel Accuracy: **95.6%**
* RBF Kernel Accuracy: **97.3%**
* Tuned RBF Model Accuracy: **98.24%**

The RBF kernel performed better, indicating the presence of non-linear patterns in the dataset.

Cross-validation confirmed that the model generalizes well and does not show signs of overfitting.

---

## 📈 Key Learnings

* Understanding margin maximization in SVM
* Difference between Linear and RBF kernels
* Importance of hyperparameter tuning (C and gamma)
* Use of cross-validation for reliable evaluation
* Visualizing decision boundaries using PCA

---

## 🎯 Conclusion

The SVM model successfully classified breast cancer cases with high accuracy.
Hyperparameter tuning improved performance further, and the RBF kernel proved more effective for non-linear data separation.

---

## 👨‍💻 Author

**Parth Gupta**

---
