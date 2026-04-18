# 💳 Bank Transaction Category Prediction

## 📌 Project Overview

This project develops a **machine learning model** to automatically classify bank transactions into categories using both structured data and textual transaction descriptions.

By combining **Natural Language Processing (NLP)** with machine learning, the model captures deeper insights from transaction data.

Key enhancements include:

* Text preprocessing using NLTK
* Dimensionality reduction for high-dimensional features
* Sampling techniques to address class imbalance

---

## 🚀 Key Features

* 📊 Data preprocessing and cleaning
* 📝 NLP-based text preprocessing (NLTK)
* 🧠 Feature engineering from structured and text data
* 📉 Dimensionality reduction (PCA)
* ⚖️ Sampling techniques (imbalanced data handling)
* ⚡ High-performance LightGBM model
* 📈 Model evaluation with classification metrics

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas
  * NumPy
  * Scikit-learn
  * LightGBM
  * NLTK 
* **Environment:** Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Loading

* Import transaction and user datasets

### 2. Data Understanding

* Perform Exploratory Data Analysis (EDA)
* Analyze distributions and missing values

### 3. Data Preprocessing

* Handle missing values
* Encode categorical variables
* Normalize features

### 4. Feature Engineering
* Create meaningful features from raw data

### 5. 📝 Text Preprocessing (NLP)

Using **NLTK**, transaction descriptions are processed through:

* Removing Punctuation & Isolating Words
* Stopword Removal
* Stemming
* Text Vectorization (TF-IDF)

### 6. 📉 Dimensionality Reduction

* Reduce high-dimensional text features using PCA
* Improve computational efficiency

### 7. ⚖️ Sampling Techniques

* Handle class imbalance using:

  * SMOTE 
  * Random Undersampling

### 8. Model Training

* Train a **LightGBM Classifier**

### 9. Model Evaluation

* Evaluate using:

  * Accuracy
  * Precision
  * Recall
  * F1-score

---

## 📊 Model Details

**Model Used:** LightGBM Classifier

### Why LightGBM?

* Efficient for large tabular datasets
* Handles mixed feature types well
* Fast training with strong performance

---

## 📈 Results

<img width="1394" height="1486" alt="Model Results" src="https://github.com/user-attachments/assets/c48da5b1-5b8b-4900-9918-a82df277f4bc" />

---

## 🔮 Future Improvements

* 🤖 Advanced NLP models (BERT)
* 🌐 API deployment (FastAPI / Flask)
* ⚡ Real-time classification system
