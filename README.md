# Machine Learning Labs

> Practical machine learning labs completed as part of the Computer Science (AI Concentration) program at Effat University.

---

## Labs Overview

### Lab 1 — Linear Regression: NO2 Pollution Prediction
**File:** `ML_Lab1.ipynb`

Built a linear regression model to predict nitrogen dioxide (NO2) concentration from atmospheric and traffic data using the OpenML NO2 dataset (500 samples). Explored the full supervised learning pipeline from data loading to model evaluation.

**Key techniques:**
- Feature exploration: cars per hour, temperature, wind speed, time of day
- Train/test split and model fitting with Scikit-learn
- Residual analysis and prediction visualization

**Tools:** Python · Scikit-learn · Pandas · Matplotlib · OpenML

---

### Lab 5 — Logistic Regression: Diabetes Classification
**File:** `ML_Lab5.ipynb`

Applied logistic regression to classify patient diabetes outcomes using the Pima Indians Diabetes dataset. Compared model performance before and after feature scaling.

**Key techniques:**
- StandardScaler preprocessing
- Logistic Regression with increased max_iter for convergence
- Evaluation: accuracy, confusion matrix, classification report

**Tools:** Python · Scikit-learn · Pandas · NumPy

---

### Lab 5 — PyTorch Neural Networks: Binary Classification
**File:** `Lab5.py`

Designed and trained multi-layer feedforward neural networks from scratch using PyTorch on a synthetic classification dataset (1,000 samples, 20 features).

**Key techniques:**
- Custom `SimpleNeuralNetwork` and `ImprovedNetwork` classes with Dropout regularization
- `BinaryClassifier` with 3 hidden layers (64 → 32 → 2)
- Early stopping with configurable patience and delta
- Learning rate scheduling: `StepLR` and `ReduceLROnPlateau`
- Full evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Model persistence: saving/loading weights, full model, and training checkpoints

**Tools:** Python · PyTorch · Scikit-learn · NumPy

---


## Skills Demonstrated

| Area | Skills |
|------|--------|
| Supervised Learning | Linear Regression, Logistic Regression, SGD, Naive Bayes |
| Deep Learning | PyTorch, Custom NN architecture, Dropout, Early Stopping |
| Data Preprocessing | StandardScaler, TF-IDF, CountVectorizer, missing value handling |
| Model Evaluation | Accuracy, F1, Precision, Recall, Confusion Matrix |
| Data Quality | HTML noise detection, data-centric AI improvement |

---

## Course
**CS3072 / CS4083** — Machine Learning & Foundations of Data Science  
Effat University · College of Engineering · Department of Computer Science

## Author
**Jouri Aldaghma**  
Computer Science (AI Concentration) · Effat University  
[LinkedIn](https://linkedin.com/in/jouri-aldaghma-b7a8b8307) · [GitHub](https://github.com/Jourialdagh)
