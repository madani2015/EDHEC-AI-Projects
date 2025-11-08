# Machine Learning – Advanced Classification

This project was developed as part of my **AI and Data Science teaching and research activities** at **EDHEC Business School (Nice, France)**.  
It focuses on **supervised learning for classification problems** using structured, real-world datasets such as **Titanic** and **Wine Quality (red and white)**.  
The goal is to design, train, and evaluate models that balance **accuracy**, **interpretability**, and **robustness**.

---

## 📘 Overview

The notebook collection explores advanced classification tasks, including:
- Binary classification (Titanic survival prediction)
- Multiclass classification (Wine quality prediction)
- Train/test workflows and evaluation metrics
- Model comparison and optimization

Each notebook demonstrates practical, reproducible data science pipelines — from data cleaning and visualization to feature engineering, model tuning, and performance interpretation.

---

## 🧠 Learning Objectives

1. Implement **machine learning classification algorithms** with real datasets.  
2. Perform **data preprocessing**, including encoding, normalization, and missing-value handling.  
3. Compare baseline and tuned models using appropriate metrics.  
4. Interpret and visualize results to ensure explainability.  
5. Connect feature insights to business and decision-making contexts.

---

## 🧩 Project Structure

| File / Notebook | Description |
|-----------------|--------------|
| **Titanic.ipynb** | Binary classification to predict passenger survival. Includes EDA, preprocessing, feature encoding, and logistic regression. |
| **train / test files** | Pre-split datasets used for training and evaluation. |
| **wine-quality.ipynb** | Multiclass classification using Wine Quality datasets (red and white). Compares models such as Decision Tree, Random Forest, and Logistic Regression. |
| **winequality-red.csv / winequality-white.csv** | Datasets containing physicochemical attributes and quality ratings. |
| **winequality.names** | Metadata describing dataset features. |

---

## 🧰 Tools and Libraries

- **Python 3**
- **pandas**, **NumPy**
- **scikit-learn**
- **matplotlib**, **seaborn**
- **Jupyter Notebook**

---

## ⚙️ Methods and Models

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors  
- Support Vector Machine (SVM)  
- Grid Search and Cross-Validation  
- Feature Importance and Confusion Matrix Visualization  

---

## 📊 Key Results

- **Titanic Dataset:**  
  Feature importance analysis shows strong influence from *gender*, *class*, and *age* on survival probability.  
  Logistic regression and tree-based models achieve high interpretability with competitive accuracy.

- **Wine Quality Dataset:**  
  Classifiers capture quality variation based on physicochemical indicators (*alcohol*, *acidity*, *chlorides*).  
  Random Forest achieved best performance with balanced precision and recall.

---

## 💡 Insights and Relevance

This project demonstrates advanced practical ML skills:
- Full supervised-learning pipeline construction  
- Model interpretability and explainability  
- Balanced evaluation with accuracy, recall, F1, and ROC curves  
- Realistic dataset management (multiple domains)  

These are essential capabilities for **data-driven decision systems** and **AI risk modeling**, aligning closely with industrial applications such as those at **Reciproc-IT**.

---

## 👩‍💻 Author

**Maryam Madani**  
MSc Digital Security – EURECOM (Sophia Antipolis)  
Teaching Assistant – AI & Data Science, EDHEC Business School  
[GitHub Profile](https://github.com/madani2015)
