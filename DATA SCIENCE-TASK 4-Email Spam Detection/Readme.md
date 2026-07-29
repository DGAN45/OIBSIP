# 📧 Email Spam Detection with Machine Learning

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

A Natural Language Processing (NLP) project that classifies SMS/Email messages into **Spam** or **Ham (Legitimate)** using **TF-IDF Vectorization** and Machine Learning algorithms.

---

# 📖 Table of Contents

- Project Overview
- Features
- Dataset
- Technologies Used
- Project Workflow
- Machine Learning Models
- Results
- Project Structure
- Installation
- Usage
- Future Improvements
- License
- Author

---

# 📌 Project Overview

Spam messages are unwanted messages that often contain advertisements, phishing attempts, scams, or malicious links.

This project develops a Machine Learning model capable of automatically identifying spam messages using Natural Language Processing techniques.

The notebook demonstrates the complete Machine Learning workflow from data preprocessing to model evaluation.

---

# 🎯 Features

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Class Distribution

✔ Text Preprocessing

✔ Stopword Removal

✔ Stemming

✔ TF-IDF Vectorization

✔ Multinomial Naive Bayes

✔ Logistic Regression

✔ Confusion Matrix

✔ Classification Report

✔ Accuracy, Precision, Recall, F1-score

✔ WordCloud

✔ Custom Message Prediction

---

# 📂 Dataset

Dataset Used:

**SMS Spam Collection Dataset**

Number of Records

- 5572 Messages

Target Classes

- Ham
- Spam

Columns

| Column | Description |
|---------|-------------|
| v1 | Message Label |
| v2 | Message Text |

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- NLTK
- WordCloud
- Regular Expressions
- Jupyter Notebook

---

# 🔄 Project Workflow

```text
Dataset
     │
     ▼
Data Cleaning
     │
     ▼
EDA & Visualization
     │
     ▼
Text Preprocessing
     │
     ▼
TF-IDF Vectorization
     │
     ▼
Train-Test Split
     │
     ▼
Machine Learning Models
     │
     ▼
Model Evaluation
     │
     ▼
WordCloud
     │
     ▼
Prediction
```

---

# 🤖 Machine Learning Models

### Multinomial Naive Bayes

Industry-standard algorithm for text classification.

---

### Logistic Regression

A supervised learning algorithm that performs extremely well with TF-IDF features.

---

# 📊 Evaluation Metrics

The models are evaluated using

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix

---

# 📈 Results

Among two machine learning models, Multinomial Naive Bayes and Logistic Regression, were evaluated for spam detection.
Multinomial Naive Bayes achieved the best overall performance with an accuracy of 96.71%, precision of 98.02%, recall of 75.57%, and an F1-score of 85.34%.
Therefore, it was selected as the final model because it provides the best balance between identifying spam messages and minimizing false predictions.
---

# ☁️ Visualizations

The notebook contains

- Count Plot
- Pie Chart
- Spam WordCloud
- Ham WordCloud
- Naive Bayes Confusion Matrix
- Logistic Regression Confusion Matrix
- Model Comparison Chart

---

# ⚙ Installation

Clone the repository

```bash
git clone https://github.com/DGAN45/OIBSIP.git
```

Move to project folder

```bash
cd OIBSIP/DATA SCIENCE-TASK 4-Email Spam Detection
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# ▶ Usage

Run every notebook cell from top to bottom.

The notebook automatically

- Cleans the dataset
- Extracts TF-IDF features
- Trains both models
- Evaluates models
- Displays visualizations
- Predicts custom messages

---

# 🔮 Future Improvements

- Support Vector Machine (SVM)
- Random Forest
- LSTM
- BERT
- Flask Deployment
- Streamlit Web App
- Real Email Dataset

---

# 📜 License

This project is licensed under the MIT License.

See the LICENSE file for more information.

---

# 👨‍💻 Author

**Debangan Halder**

Computer Science & Technology Student

Machine Learning • Python • NLP • Data Science

---

## ⭐ If you like this project, give it a Star on GitHub!
