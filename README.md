# 🧠 Introvert vs Extrovert Personality Prediction

Welcome to the Personality Prediction project!  
In this notebook, we explore and model a dataset to distinguish between **Introverts** and **Extroverts** based on behavioral and social attributes using various **Machine Learning algorithms**.

---

## 📌 Project Overview

This notebook demonstrates an end-to-end machine learning workflow for predicting whether a person is an **Introvert** or **Extrovert**. We:
- Explore and clean the dataset
- Perform preprocessing and feature analysis
- Train multiple classification models
- Evaluate their performance
- Select the best-performing model

---

## 📁 Dataset Description

The dataset contains behavioral data collected from individuals, including their social habits and personality type.  
Each row represents a person, and the features include:

| Feature | Description |
|--------|-------------|
| `id` | Unique identifier |
| `Time_spent_Alone` | Hours spent alone per day |
| `Stage_fear` | Does the person fear public speaking? (Yes/No) |
| `Social_event_attendance` | Frequency of attending events |
| `Going_outside` | Frequency of going outside |
| `Drained_after_socializing` | Do they feel drained after socializing? (Yes/No) |
| `Friends_circle_size` | Number of close friends |
| `Post_frequency` | Frequency of posting on social media |
| `Personality` | 🧍 Target: Introvert or Extrovert |

### Source: [Kaggle Competition.](https://www.kaggle.com/competitions/playground-series-s5e7/data) 

---

## 🛠️ Technologies Used

- **Python** 🐍  
- **Pandas, NumPy** for data manipulation  
- **Matplotlib, Seaborn** for data visualization  
- **Scikit-learn, XGBoost** for machine learning models  
- **GridSearchCV** for hyperparameter tuning

---

## 📊 Models Applied

I have evaluated several classification models:

- ✅ Logistic Regression  
- 🌲 Random Forest Classifier  
- 📈 XGBoost  
- 🤖 Support Vector Machine  
- 🌐 K-Nearest Neighbors  
- 🌿 Decision Tree  
- 📉 Naive Bayes  
- 🚀 Gradient Boosting Classifier

Each model was tested using accuracy score.

---

## 🔍 Key Steps

1. **Data Loading & Exploration**  
2. **Handling Missing Values**  
3. **Feature Encoding & Scaling**  
4. **Model Training & Comparison**  
5. **Model Evaluation using Metrics**

---

## 📈 Results

- **Top Model**: Logistic Regression
- **Accuracy Achieved**: 96.92% on training set and 97.4% on Unseen test data set
📌 All models were evaluated on unseen test data to ensure generalizability.

---

## 📦 Future Improvements
 
- Use feature selection techniques to reduce dimensionality.

---


---

## 🙌 Acknowledgements

Thanks to the creators of the dataset and the open-source ML community.  
Inspired by the challenge to explore personality traits using data science! 🔍🧬

---

## 💡 Author

**Aman Sagar**  
*Aspiring Data Scientist | ML Enthusiast | Lifelong Learner*

