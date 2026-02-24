# 🧠 Breast Cancer Classification using Support Vector Machines (SVM)

## 📌 Project Overview
This project implements **Support Vector Machines (SVM)** for binary classification using the **Breast Cancer Wisconsin dataset**. Both **linear and non-linear (RBF) kernels** are applied, followed by **hyperparameter tuning, decision boundary visualization, and cross-validation** to achieve high prediction accuracy and model robustness.

The project demonstrates **industry-grade machine learning practices** and explainable AI concepts.

---

## 🎯 Objectives
- Implement SVM with linear and RBF kernels  
- Perform feature scaling for optimal model performance  
- Tune hyperparameters (C and gamma)  
- Visualize decision boundaries using PCA  
- Evaluate model using cross-validation  

---

## 🛠️ Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Dataset
**Dataset:** Breast Cancer Wisconsin Dataset  

**Classification Type:** Binary  

**Classes:**
- 0 → Malignant  
- 1 → Benign  

**Total Samples:** 569  
**Features:** 30 numeric medical attributes  

---

## ⚙️ Project Workflow
1. Data Loading & Exploration  
2. Feature Scaling (Standardization)  
3. Train-Test Split  
4. Linear Kernel SVM Training  
5. RBF Kernel SVM Training  
6. Hyperparameter Tuning using GridSearchCV  
7. Decision Boundary Visualization using PCA  
8. Cross Validation Evaluation  

---

## 🔧 Hyperparameter Tuning
GridSearchCV is used to optimize **C and gamma** values for the RBF kernel, improving model generalization and classification accuracy.

---

## 🎯 Decision Boundary Visualization
Principal Component Analysis (PCA) is used to reduce feature dimensions to 2D for visualization, enabling clear observation of how SVM separates benign and malignant samples.

---

## 🏆 Results
- High classification accuracy  
- Excellent class separation  
- Robust generalization using cross-validation  
- Reliable medical classification performance  

---

## 📁 Repository Structure

```
breast-cancer-classification-using-SVM/
│
├── data/
│   └── breast cancer dataset.csv
│
├── notebooks/
│   └── Task7_Breast_Cancer_Classification_using_SVM.ipynb
│
├── reports/
│   └── Task7_Breast_Cancer_SVM_Report.pdf
│
├── README.md

```

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/diyab6804-gh/breast-cancer-classification-using-SVM.git
   
2. Install dependencies
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook
   ```
   jupyter notebook

---

## 🏁 Conclusion

This project demonstrates the effective use of Support Vector Machines with linear and RBF kernels, achieving high classification accuracy through hyperparameter tuning, decision boundary visualization, and cross-validation.

---

## 👩‍💻 Author

Patel Diya B

AI/ML Intern
