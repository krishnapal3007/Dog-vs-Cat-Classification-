# 🐶🐱 Cats vs Dogs Image Classification using Support Vector Machine (SVM)

## 📌 Overview
This project implements a **Support Vector Machine (SVM)** model to classify images of **cats** and **dogs**. The images are preprocessed using OpenCV by resizing and flattening them before training the classifier.

This project was completed as **Task-03** of the **Prodigy InfoTech Machine Learning Internship**.

---

## 🚀 Features
- Image preprocessing using OpenCV
- Image resizing (64 × 64)
- Flattening images into feature vectors
- Train-Test Split
- Image classification using Linear SVM
- Model evaluation
- Confusion Matrix
- Classification Report
- Save trained model using Joblib
- Predict class for a new image

---

## 🛠️ Technologies Used
- Python
- NumPy
- OpenCV
- Scikit-learn
- Matplotlib
- Joblib

---

## 📂 Dataset
**Dogs vs Cats Dataset (Kaggle)**

https://www.kaggle.com/c/dogs-vs-cats/data

---

## 📊 Model
- Algorithm: **Linear Support Vector Machine (LinearSVC)**
- Image Size: **64 × 64**
- Training Images: **3200**
- Testing Images: **800**

---

## 📈 Results
- Accuracy: **54%**
- Model successfully predicts whether an image is a **Cat** or **Dog**.

---

## 📁 Project Structure

```
PRODIGY_ML_03/
│── Dataset/
│   ├── train/
│   │   ├── cats/
│   │   └── dogs/
│   └── test1/
│
│── svm_cat_dog_classifier.ipynb
│── cat_dog_svm_model.pkl
│── requirements.txt
│── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/krishnapal3007/PRODIGY_ML_03.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook svm_cat_dog_classifier.ipynb
```

4. Run all cells.

---

## 📌 Internship
**Prodigy InfoTech – Machine Learning Internship**

**Task-03:** Implement a Support Vector Machine (SVM) to classify images of cats and dogs.

---

## 👨‍💻 Author

**Krishna**

GitHub:
https://github.com/krishnapal3007