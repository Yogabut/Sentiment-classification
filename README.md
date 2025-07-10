# 📊 Sentiment Classification using LSTM – Cryptocurrency Users' Sentiment Analysis

## 📌 Project Description

This project focuses on performing sentiment analysis and classification on user opinions related to **cryptocurrency** from platform X (e.g., Twitter, forums, or other social media). The classification is done using the **Long Short-Term Memory (LSTM)** algorithm, which is well-suited for processing sequential text data such as comments and reviews.

---

## ⚙️ Tools & Development Environment

* **IDE**: Google Colab
* **Language**: Python
* **Libraries Used**:

  * `pandas` – data manipulation and analysis
  * `numpy` – numerical operations
  * `matplotlib`, `seaborn` – data visualization
  * `sklearn` – preprocessing and model evaluation
  * `tensorflow` – building the LSTM model
  * `wordcloud` – word visualization
  * `stopwords`, `Sastrawi` – text preprocessing for Indonesian language
  * `re`, `string`, and others – text processing utilities

---

## 🧠 Algorithm

The main model used in this project is **LSTM (Long Short-Term Memory)**, a type of Recurrent Neural Network (RNN) that is capable of learning long-term dependencies in sequential data, making it ideal for understanding the context in user sentiment analysis.

---

## 📝 Project Workflow

1. **Data Collection**
   Gather user sentiment data from platform X related to cryptocurrency (in `.csv` format or via API).

2. **Text Preprocessing**

   * Case folding (convert text to lowercase)
   * Cleaning (remove symbols, numbers, URLs)
   * Tokenization
   * Stopword removal
   * Stemming (using Sastrawi for Indonesian)

3. **Exploratory Data Analysis (EDA)**

   * Sentiment distribution visualization
   * WordClouds for positive and negative sentiment
   * Word frequency analysis

4. **Data Splitting**

   * Split data into training and testing sets

5. **Embedding & LSTM Model**

   * Tokenization and padding
   * Build the LSTM model using TensorFlow/Keras

6. **Training & Evaluation**

   * Evaluate the model using accuracy, precision, recall, and confusion matrix

---

## 📈 Expected Outcomes

* Sentiment classification of user opinions into **positive**, **negative**, or **neutral**
* WordCloud visualizations and sentiment distribution graphs
* A well-performing and generalizable LSTM model

---

