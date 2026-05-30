# 📱 Spam SMS Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge\&logo=python)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge\&logo=googlecolab)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge\&logo=scikitlearn)
![Gradio](https://img.shields.io/badge/Gradio-UI-green?style=for-the-badge)

## CodSoft Internship Project

### Task 4 - Spam SMS Detection

This project is developed as part of the **CodSoft Artificial Intelligence Internship Program**.

The objective of this project is to build a Machine Learning model capable of classifying SMS messages as **Spam** or **Legitimate (Ham)** using Natural Language Processing (NLP) techniques and Machine Learning algorithms.

---

## 📌 Project Overview

Spam messages are unwanted messages that often contain advertisements, phishing links, scams, or fraudulent content.

This project uses:

* Text Preprocessing
* TF-IDF Vectorization
* Machine Learning Classification
* Interactive User Interface

to automatically detect whether an SMS is Spam or Legitimate.

---

## 🛠️ Technologies Used

| Technology        | Purpose                    |
| ----------------- | -------------------------- |
| Python            | Programming Language       |
| Google Colab      | Development Environment    |
| Pandas            | Data Processing            |
| NumPy             | Numerical Computation      |
| Scikit-Learn      | Machine Learning           |
| TF-IDF Vectorizer | Text Feature Extraction    |
| Gradio            | Interactive User Interface |
| Matplotlib        | Visualization              |

---

## 📂 Dataset

The dataset contains SMS messages labeled as:

* Ham (Legitimate Message)
* Spam (Unwanted Message)

Example:

| Label | Message                                           |
| ----- | ------------------------------------------------- |
| Ham   | Hi, are we meeting today?                         |
| Spam  | Congratulations! You have won ₹50,000 cash prize. |

---

## 🔄 Project Workflow

```text
Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
TF-IDF Vectorization
        │
        ▼
Model Training
(Naive Bayes / Logistic Regression / SVM)
        │
        ▼
Model Evaluation
        │
        ▼
Best Model Selection
        │
        ▼
Gradio User Interface
        │
        ▼
Spam / Legitimate Prediction
```

---

## 🤖 Algorithms Used

### 1️⃣ Naive Bayes

* Probability-based classifier
* Fast training speed
* Efficient for text classification

### 2️⃣ Logistic Regression

* Linear classification model
* Balanced performance
* Good prediction accuracy

### 3️⃣ Support Vector Machine (SVM)

* Creates optimal decision boundaries
* Excellent for text classification
* Highest accuracy among tested models

---

## 📊 Algorithm Comparison

| Algorithm           | Accuracy  | Speed     | Performance |
| ------------------- | --------- | --------- | ----------- |
| Naive Bayes         | High      | Very Fast | Good        |
| Logistic Regression | Very High | Fast      | Better      |
| SVM                 | Highest   | Medium    | Best        |

### 🏆 Best Algorithm

**Support Vector Machine (SVM)**

Reason:

* High classification accuracy
* Excellent performance on text datasets
* Better spam detection capability

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Formulae

**Accuracy**

Accuracy = (TP + TN) / Total Predictions

**Precision**

Precision = TP / (TP + FP)

**Recall**

Recall = TP / (TP + FN)

**F1 Score**

F1 = 2 × (Precision × Recall) / (Precision + Recall)

---

## 🎨 User Interface

The project includes a Gradio-based User Interface built directly in Google Colab.

### Features

✅ Simple and Interactive UI

✅ Real-Time SMS Prediction

✅ User-Friendly Design

✅ Instant Spam Detection

### Example

Input:

Congratulations! You have won a free iPhone. Click here to claim now.

Output:

🚨 SPAM MESSAGE

---

## 📷 Results

The trained model successfully classifies SMS messages into:

* Spam Messages
* Legitimate Messages

using TF-IDF feature extraction and SVM classification.

---

## 📌 Future Enhancements

* Deep Learning Models (LSTM)
* BERT-based Text Classification
* Real-Time SMS API Integration
* Mobile Application Deployment
* Multi-language Spam Detection

---

## 💻 How to Run

### Step 1

Clone the Repository

```bash
git clone https://github.com/yourusername/Spam-SMS-Detection.git
```

### Step 2

Install Dependencies

```bash
pip install pandas numpy scikit-learn gradio matplotlib
```

### Step 3

Open Google Colab

Upload:

* Dataset (spam.csv)
* Project Notebook

### Step 4

Run all cells

### Step 5

Launch the Gradio Interface

---

## 📚 Learning Outcomes

Through this project, I learned:

* Natural Language Processing (NLP)
* TF-IDF Feature Extraction
* Machine Learning Classification
* Model Evaluation Techniques
* UI Development with Gradio
* End-to-End AI Project Development

---

## 👨‍💻 Author

### Sourav Biswal

B.Tech – CSE(CyberSecurity-iot)
C. V. Raman Global University, Odisha

---

## 🙏 Acknowledgement

This project was completed as part of the **CodSoft Artificial Intelligence Internship Program**.
Special thanks to **CodSoft** for providing the opportunity to work on real-world AI and Machine Learning projects.
#CodSoft #MachineLearning #ArtificialIntelligence #Python #NLP #SpamDetection #GoogleColab #ScikitLearn #Gradio #InternshipProject
