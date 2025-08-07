#  Titanic Classification: Logistic Regression vs Random Forest

This project was created as part of the **Technical Programming 2** module, focusing on building and evaluating classification models using Python and real-world data.

##  Student Info

- **Name:** Mhle L.  
- **Student Number:** 22322987  
- **Module:** Technical Programming 2  
- **Assessment:** Classification Models (Logistic Regression vs Random Forest)  
- **Due Date:** 8 August 2025  
- **Collaborator:** xpiyose@gmail.com  

---

##  Project Overview

We use the Titanic dataset from Kaggle to compare two machine learning classification models:

1. **Logistic Regression**
2. **Random Forest Classifier**

This dataset is **multi-relational** — it includes features of various types and levels:

- **Numerical features**: Age, Fare, SibSp (number of siblings/spouses), Parch (parents/children)
- **Categorical features**: Sex, Embarked, Pclass (passenger class)
- **Derived binary label**: Survived (0 = No, 1 = Yes)

These diverse feature types make it well-suited for comparing classification models.

###  Evaluation Metrics:
- Accuracy
- Confusion Matrix
- F1 Score

---

##  Files

- `Classification_Models.ipynb`: Main notebook containing the full implementation.
- `README.md`: This file, explaining the project structure and purpose.

---

##  Dataset

The dataset used is from Kaggle:  
[Titanic - Machine Learning from Disaster](https://www.kaggle.com/datasets/dwiuzila/titanic-machine-learning-from-disaster)

---

## 🔧 Technologies Used

- Python 3
- Google Colab
- Scikit-learn
- Pandas
- Matplotlib / Seaborn

---

##  Results Summary

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 81.3%    |
| Random Forest       | 78.3%    |

Logistic Regression slightly outperformed Random Forest on this dataset, likely due to the linear separability of the features.

---

##  Notes

- The dataset is **multi-relational**, with mixed data types and feature interactions.
- This project demonstrates end-to-end supervised learning: preprocessing, training, evaluation, and comparison.


---

