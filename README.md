# 🎓 Student Performance Prediction – Classification Models (Google Colab)

This project aims to predict whether a student is likely to pass or fail based on their demographic background and test preparation status. It explores the impact of various student characteristics on exam performance using classic machine learning models, all developed and analyzed in a Jupyter Notebook on Google Colab.

## 📊 Dataset

- **Source**: [Kaggle – Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- Features include gender, race/ethnicity, parental education, lunch type, and test preparation course
- Target label is based on average score threshold: **Pass** or **Fail**

## 🧠 Models

- **Decision Tree Classifier**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

### Data Preprocessing:
- Label encoding (**OneHotEncoder**) for categorical features  
- Feature scaling (**StandardScaler**) for numerical features (used in Logistic Regression and SVM)  
- Creation of a binary target (`Pass` if average score ≥ 50)

### Evaluation Metrics:
- Accuracy
- Precision
- f1 score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- AUC and ROC

## 🛠 Technologies Used

- Google Colab (Python 3, Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## 📈 Results

- **Best accuracy achieved**: *98* 
- Insights into the influence of test preparation and parental education on student success

## 🚀 How to Run

You can open and run the notebook in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MatoKamenicky/student-performance-prediction/blob/main/Student_Performance_Classifier.ipynb)

Or clone this repository and run locally:

```bash
git clone https://github.com/MatoKamenicky/student-performance-prediction.git
cd student-performance-prediction
jupyter notebook
