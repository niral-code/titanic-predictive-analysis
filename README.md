# titanic-predictive-analysis
Titanic survival prediction using Decision Tree and Random Forest
# 🚢 Titanic Survival Prediction using Machine Learning

This project focuses on building and comparing **Decision Tree** and **Random Forest** classification models to predict whether a passenger survived the Titanic shipwreck. It is a supervised learning task using Python and popular data science libraries.

## 📊 Objective

- Explore the Titanic dataset and understand its structure
- Perform data preprocessing (handling missing values, encoding, feature engineering)
- Build a Decision Tree Classifier
- Build a Random Forest Classifier
- Compare and evaluate model performance on test data
- Visualize results and extract insights

---

## 🧠 Machine Learning Models Used

- **Decision Tree Classifier**
- **Random Forest Classifier**

---

## 📁 Dataset

- `titanic_train.csv` – Training dataset used to train the models
- `titanic_test.csv` – Unseen dataset used to evaluate model performance

Dataset fields include:

- `Survived` – Target variable (0 = No, 1 = Yes)
- `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked` – Features used for prediction

---

## ⚙️ Technologies and Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Results

- **Random Forest Classifier** performed better in terms of accuracy and generalization compared to the Decision Tree.
- Feature importance showed that `Sex`, `Fare`, and `Pclass` were among the top predictors for survival.

---

## 📷 Visualizations

- Bar plots for categorical feature distributions
- Heatmaps for correlation
- Confusion matrices for model evaluations
- Feature importance plots for both classifiers

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/niral-code/titanic-predictive-analysis.git
