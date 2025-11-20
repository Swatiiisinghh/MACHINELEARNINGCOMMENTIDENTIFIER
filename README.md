# Toxic Comment Classification – Multi-Label NLP

## 📌 Overview
In this project, I built a **multi-label text classification model** to detect toxic behavior in online comments. The dataset contains Wikipedia comments that have been manually labeled by human raters. My goal was to predict the probability of each toxicity category for every input comment.

### 🎥 Tutorial I Followed
https://youtu.be/lbmzacBDOew

---

## 🧠 Problem Background
Online communities often deal with abusive or harmful comments that discourage users from expressing their opinions. Many platforms struggle to moderate such content effectively.

To understand how multi-label NLP systems work, I implemented a toxicity detection model that can classify comments into multiple categories at once.

---

## 🗂️ Dataset Information
I used the dataset from the **Jigsaw Toxic Comment Classification Challenge** on Kaggle. Each comment can belong to more than one toxicity category, which makes this a **multi-label classification task**.

The labels include:

- toxic  
- severe_toxic  
- obscene  
- threat  
- insult  
- identity_hate  

📥 Dataset link:  
https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data?select=train.csv.zip

---

## 🛠️ Libraries Used
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

## 🤖 Algorithms Implemented
I experimented with the following models:

- **Logistic Regression** (One-vs-Rest scheme)
- **Naive Bayes** (MultinomialNB)

---

## 📊 Model Performance
The results I achieved:

- **ROC_AUC:** 0.9794  
- **Accuracy:** 0.9187  

These metrics show that the model performs well in identifying toxic vs non-toxic behavior across different labels.

---

## 📝 What I Learned
Working on this project helped me understand:

- multi-label text classification  
- NLP preprocessing techniques  
- applying classical ML models to large text datasets  
- evaluating model performance using ROC_AUC and accuracy  

This project gave me hands-on experience in building practical NLP systems that can support safer online interactions.


# Libraries

<li>pandas
<li>matplotlib
<li>seaborn
<li>scikit-learn

# Algorithms

<li>Logistic Regression
<li>Naive Bayes
  
# Metrics

- ROC_AUC: 0.9794
- Accuracy: 0.9187
