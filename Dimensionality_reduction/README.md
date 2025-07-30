
# 🔍 Diabetes Prediction using Feature Selection Techniques

This project demonstrates the end-to-end process of predicting diabetes using the **Pima Indians Diabetes Dataset**, with a focus on **feature selection** techniques such as **Forward Selection** and **Backward Elimination**. It is designed to showcase clean machine learning workflows and strong model-building practices to potential recruiters.

---

## 📌 Problem Statement

Early detection of diabetes is critical in clinical treatment. However, not all medical indicators contribute equally to accurate predictions. This project explores which features are most influential using **sequential feature selection** and builds a logistic regression classifier to predict diabetes effectively.

---

## 🧠 Core Concepts Demonstrated

✅ Clean and readable **end-to-end ML pipeline**  
✅ Real-world **dataset handling & preprocessing**  
✅ **Forward and backward feature selection**  
✅ **Model evaluation** with accuracy, precision, recall, and ROC AUC  
✅ **ROC Curve Visualization**  
✅ **Scikit-learn best practices** for reproducible results  

---

## 📂 Project Structure

```
diabetes-feature-selection/
│
├── diabetes.csv                 # Dataset (Pima Indians Diabetes Dataset)
├── diabetes_feature_selection.ipynb  # Jupyter Notebook with full code
├── README.md                    # You’re reading it!
```

---

## 🧪 Feature Selection Techniques Used

### 🔼 Forward Selection  
Incrementally adds the most useful features to improve model accuracy.

### 🔽 Backward Elimination  
Starts with all features and removes the least useful ones based on performance drop.

These help identify the most **predictive medical indicators** such as *Glucose*, *BMI*, and *Age*, reducing noise and improving generalization.

---

## ⚙️ Technologies & Libraries

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib (for ROC curves)

---

## 🚀 How to Run

1. Clone the repo or open the notebook in [Google Colab](https://colab.research.google.com/):
    ```
    git clone https://github.com/your-username/diabetes-feature-selection.git
    ```

2. Install required libraries:
    ```
    pip install pandas numpy scikit-learn matplotlib
    ```

3. Open and run the Jupyter Notebook:
    ```
    jupyter notebook diabetes_feature_selection.ipynb
    ```

---

## 📊 Results Snapshot

- Accuracy: ~78%  
- ROC AUC Score: ~84%  
- Most impactful features: **Glucose**, **BMI**, **Age**, **Pregnancies**

---

## 📌 Why This Project Matters

This project reflects:
- Real-world application of **feature selection**  
- Deep understanding of **model evaluation metrics**  
- Ability to write **clean, modular, and well-commented code**  
- Practical ML problem-solving skills that go beyond just model fitting

-
