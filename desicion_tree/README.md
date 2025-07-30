# 📊 Customer Churn Prediction using Decision Tree Classifier

This project builds a machine learning model to predict customer churn using a Decision Tree Classifier. It includes end-to-end steps from data preprocessing and visualization to hyperparameter tuning and feature importance analysis.

---

## 📁 Dataset

The dataset used is `churn.csv`, which includes customer details and a binary target column `churn` indicating whether a customer left (1) or stayed (0).

---

## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🧠 Workflow

### 1. **Data Loading and Preprocessing**
- Load data from CSV.
- Drop irrelevant columns like `customer_id`.
- Split into features (`X`) and target (`Y`).
- Apply standard scaling using `StandardScaler`.
- Perform train-test split with stratification on target.

### 2. **Model Training**
- Train a Decision Tree Classifier on the dataset.
- Use `class_weight='balanced'` to handle class imbalance.

### 3. **Model Evaluation**
- Evaluate on both train and test sets using:
  - Precision
  - Recall
  - F1-score

### 4. **Hyperparameter Tuning**
- Tune `max_depth` and `min_samples_split` using custom functions to:
  - Train multiple models with varying values.
  - Plot train/test F1-scores to visualize overfitting vs underfitting.

### 5. **Feature Importance**
- Train a final model and extract feature importances.
- Plot horizontal bar chart of important features.

---

## 📈 Visualizations

- **F1 Score vs max_depth**  
- **F1 Score vs min_samples_split**  
- **Feature Importance bar plot**

These help in understanding model behavior and which parameters/features impact performance the most.

---

## 🚀 How to Run

1. Clone this repository
2. Place your `churn.csv` file in the project directory.
3. Open the notebook in VS Code or Jupyter.
4. Run all cells in sequence.

---

## 📌 Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
