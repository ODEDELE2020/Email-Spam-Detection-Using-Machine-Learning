# 🚀 **Project 15: Email Spam Detection Using Machine Learning** 📧🤖

We all receive countless emails every day. Some are meaningful, while others are irrelevant or malicious—commonly referred to as **spam**. This project focuses on **detecting spam emails** using machine learning algorithms and analyzing their performance.

---

## 🎯 **Project Overview**

The goal of this project is to automatically classify emails into **spam** or **ham (non-spam)**. By training models on real-world email datasets, the system can predict whether an incoming email is legitimate or unwanted.

---

## 🗂️ **Dataset**

The dataset consists of two classes:

* **Ham (Non-spam)**: 4,825 emails
* **Spam**: 747 emails

The dataset is heavily **imbalanced**, which makes it important to carefully evaluate models.

### **WordCloud Visualizations**

* **Spam emails**:

<p align="center"> 
<img src="https://user-images.githubusercontent.com/81585804/177145653-a8f04fd5-3983-4283-bc6f-93d372e6d5c4.png" width="410" height="350">
</p>

* **Ham emails**:

<p align="center">
<img src="https://user-images.githubusercontent.com/81585804/177145809-459c17b8-f064-4ae3-8c9c-3b0c51f61133.png" width="410" height="350">
</p>

---

## 🧠 **Model Training**

The dataset was trained using the following **Machine Learning algorithms**:

* **Naive Bayes**
* **Support Vector Machine (SVM)**
* **K-Nearest Neighbors (KNN)**
* **Decision Tree**
* **Random Forest**

### **Model Accuracy Comparison**

<p align="center"> 
<img src="https://user-images.githubusercontent.com/81585804/177146582-ba4661f5-d6c1-4f41-801c-5829414f614e.png" width="450" height="350">
</p>

---

## 🔍 **Prediction Example**

You can make predictions for individual emails using the trained models. Example outputs:

```python
MultinomialNB()               # Output: This is a Real email
SVC(C=1000, gamma=0.001)      # Output: This is a Real email
KNeighborsClassifier(n_neighbors=3) # Output: This is a Real email
DecisionTreeClassifier()       # Output: This is a Real email
RandomForestClassifier()       # Output: This is a Real email
```

---

## 🛠️ **Tech Stack**

* **Python**
* **Scikit-Learn** (Naive Bayes, SVM, KNN, Decision Tree, Random Forest)
* **Pandas / NumPy** (Data processing)
* **Matplotlib / WordCloud** (Visualization)

---

## 🔗 **GitHub Repository**

👉 https://github.com/ODEDELE2020/Email-Spam-Detection-Using-Machine-Learning.git

---

## ✅ **Key Learnings**

* Handling **imbalanced datasets** in classification tasks
* Text preprocessing and feature extraction for email data
* Comparing multiple machine learning algorithms for accuracy
* Visualizing patterns in text data using WordClouds


