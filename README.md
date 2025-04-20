# 🧠 Breast Cancer Classification

This project uses the **Breast Cancer Wisconsin (Diagnostic)** dataset to classify tumors as **benign** or **malignant** using different machine learning models.

---

## 🎯 Project Objective

The goal is to apply essential data science and machine learning skills to:

- Load and explore real-world medical data
- Train and evaluate multiple classification models
- Compare model performances
- Interpret results with a focus on critical metrics like **recall**

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `breast_cancer_classification.ipynb` | Main Jupyter Notebook with all model training and evaluation |
| `README.md` | Project overview and usage guide |
| `requirements.txt` | List of required Python packages |

---

## 🤖 Models Used

Three supervised machine learning models were trained and compared:

1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

---

## 📊 Performance Metrics

For each model, the following metrics were calculated:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

> 💡 **Recall** is especially critical in medical diagnoses to avoid missing actual cancer cases.

---

## 🔍 Model Comparison

| Model | Accuracy | Recall | Precision | F1-Score |
|-------|----------|--------|-----------|----------|
| Logistic Regression | 0.95 | 0.99 | 0.95 | 0.97 |
| Decision Tree | 0.91 | 0.94 | 0.91 | 0.92 |
| Random Forest | 0.96 | 0.99 | 0.96 | 0.97 |

> 🥇 **Random Forest** performed best overall with high precision and recall.

---

## ⚙️ How to Run

### 1. Install dependencies:
```bash
pip install -r requirements.txt

