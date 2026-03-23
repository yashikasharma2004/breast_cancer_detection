# 🩺 Breast Cancer Detection using Logistic Regression

## 📌 Project Overview

This project builds a **Machine Learning model** using **Logistic Regression** to classify breast cancer as:

* **Malignant (Cancerous)**
* **Benign (Non-cancerous)**

The dataset is fetched directly from Kaggle using the Kaggle API, making the project clean and reproducible without manually uploading data files.

---

## 🎯 Objectives

* Build a Logistic Regression model for classification
* Use Kaggle API to download dataset
* Perform basic data cleaning and preprocessing
* Evaluate model performance

---

## 📂 Dataset

* **Source:** Kaggle
* **Dataset Name:** Breast Cancer Wisconsin (Diagnostic) Dataset
* **Link:** https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

📌 The dataset is automatically downloaded in the code using Kaggle API.

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Scikit-learn
* Google Colab

---

## 🚀 Steps to Run the Project

### 1️⃣ Setup Kaggle API

* Download `kaggle.json` from your Kaggle account
* Upload it in Google Colab

```python
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
```

---

### 2️⃣ Download Dataset

```python
!kaggle datasets download -d uciml/breast-cancer-wisconsin-data
!unzip breast-cancer-wisconsin-data.zip
```

---

### 3️⃣ Run the Model

* Execute the Python code provided in the notebook/script
* The model will train and display accuracy

---

## 🧠 Model Used

* **Logistic Regression**

  * Simple and effective for binary classification
  * Works well for this dataset

---

## 📊 Output

* Model Accuracy (typically around **95%+**)
* Classification of cancer as:

  * `1 → Malignant`
  * `0 → Benign`

---

## 📌 Key Features

* No need to upload dataset manually
* Clean and beginner-friendly implementation
* Suitable for academic projects and evaluations

---

## 🔮 Future Improvements

* Use advanced models (Decision Tree, Random Forest)
* Add visualization (graphs, confusion matrix)
* Deploy as a web app

---

## 🙌 Author

yashika sharma

---

## ⭐ Note

This project uses Kaggle API to fetch the dataset dynamically, so no dataset files are included in this repository.
