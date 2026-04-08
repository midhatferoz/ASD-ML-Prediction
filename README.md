# ASD-ML-Prediction
ML based Autism Prediction using SHAP
#Autism Spectrum Disorder (ASD) Prediction using Machine Learning & SHAP

# Overview

This project focuses on predicting the likelihood of **Autism Spectrum Disorder (ASD)** using machine learning models. In addition to classification, the project integrates **SHAP (SHapley Additive Explanations)** to provide interpretability and explain model decisions.

---

##  Objectives

* Build machine learning models to predict ASD
* Compare performance of different classifiers
* Use SHAP for explainable AI (XAI)
* Identify key features influencing predictions

---

##  Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib / Seaborn
* SHAP

---

## Machine Learning Models

The following models were implemented and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

##  Results & Visualizations

The project includes the following key visualizations:

* 📈 Model Performance Comparison (Accuracy, Precision, Recall, F1-score)
* 🔲 Confusion Matrix (Best Performing Model)
* 🌐 SHAP Summary Plot (Feature Impact)
* 📊 Feature Importance Graph

---

##  Explainability with SHAP

SHAP (SHapley Additive Explanations) is used to:

* Understand feature contributions
* Visualize impact of each feature on predictions
* Improve trust and transparency in the model

---

## Project Structure

```
ASD-ML-Prediction/
│── dataset.csv
│── model.ipynb
│── graphs/
│   ├── model_comparison.png
│   ├── confusion_matrix.png
│   ├── shap_summary.png
│   └── feature_importance.png
│── requirements.txt
│── README.md
```

---

## Installation & Setup

1. Clone the repository:

```
git clone https://github.com/your-username/ASD-ML-Prediction.git
cd ASD-ML-Prediction
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the project:

* Open the Jupyter Notebook:

```
jupyter notebook
```

* Run all cells in `model.ipynb`

---

## Key Insights

* Random Forest performed best among all models
* SHAP analysis revealed the most influential features
* Model predictions are interpretable and transparent

---

## Future Improvements

* Use larger and more diverse datasets
* Try advanced models (XGBoost, Neural Networks)
* Deploy as a web application
* Improve model accuracy and generalization

---

##  License

This project is for academic and educational purposes.

---

## Acknowledgements

* Scikit-learn documentation
* SHAP library documentation
* Dataset sources (if applicable)

---
