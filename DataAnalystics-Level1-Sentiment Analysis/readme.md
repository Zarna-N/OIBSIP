# 🧠 Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project was developed as **Task 4** of the **Oasis Infobyte Data Analytics Internship**.

The objective of this project is to build a **multi-class sentiment analysis model** that automatically classifies text into different sentiment categories using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

The dataset consists of preprocessed text comments labeled into three sentiment classes.

---

## 🎯 Objective

- Perform sentiment classification on text data.
- Convert textual data into numerical features using **TF-IDF Vectorization**.
- Train and compare multiple machine learning models.
- Evaluate model performance using standard classification metrics.
- Visualize sentiment distribution and frequently occurring words.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- WordCloud
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains:

- Preprocessed text comments
- Multi-class sentiment labels
- Missing value handling
- Ready-to-use cleaned text

---

## 📊 Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Handle Missing Values
5. Visualize Sentiment Distribution
6. Inspect Sample Reviews
7. TF-IDF Feature Extraction
8. Train-Test Split (80:20)
9. Train Naive Bayes Model
10. Evaluate Naive Bayes
11. Train Logistic Regression Model
12. Evaluate Logistic Regression
13. Model Comparison
14. WordCloud Visualization
15. Error Analysis
16. Business Value
17. Conclusion

---

## 🤖 Machine Learning Models

### 1️⃣ Multinomial Naive Bayes

Used as a baseline model for text classification.

### 2️⃣ Logistic Regression

Used for improved sentiment prediction and comparison.

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Multinomial Naive Bayes | **66.93%** |
| Logistic Regression | **78.90%** ✅ |

### Best Performing Model

🏆 **Logistic Regression**

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📉 Visualizations

The project includes:

- Sentiment Distribution Bar Chart
- Confusion Matrix
- WordCloud for Negative Sentiment
- WordCloud for Neutral Sentiment
- WordCloud for Positive Sentiment

---

## 🔍 Error Analysis

Five misclassified reviews were analyzed to understand prediction errors.

The major reasons behind incorrect predictions include:

- Ambiguous wording
- Mixed sentiments
- Short text with limited context
- Similar vocabulary across multiple sentiment classes

---

## 💼 Business Value

This sentiment analysis system can help organizations:

- Understand public opinion automatically.
- Analyze large volumes of textual feedback.
- Detect negative opinions quickly.
- Improve products and services.
- Support data-driven decision making.
- Reduce manual effort required for sentiment analysis.

---

## 📌 Conclusion

This project successfully implemented a complete **Sentiment Analysis pipeline** using Natural Language Processing and Machine Learning.

Among the two models, **Logistic Regression** achieved the highest accuracy (**78.90%**) and demonstrated better overall performance than Naive Bayes.

The developed model can be applied to automatically classify textual opinions and assist organizations in understanding user sentiment efficiently.

---



## 👩‍💻 Author

**Zarna Namojwar**

Data Analytics Intern – Oasis Infobyte

GitHub: https://github.com/Zarna-N

LinkedIn: https://www.linkedin.com/in/zarna-namojwar/
