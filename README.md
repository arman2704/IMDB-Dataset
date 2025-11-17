# Comparative Sentiment Analysis of IMDB Movie Reviews: LSTM vs. Logistic Regression

This capstone project implements, evaluates, and compares two distinct models—a traditional **Logistic Regression** classifier and a **Long Short-Term Memory (LSTM)** deep learning network—to classify the sentiment (positive or negative) of 50,000 movie reviews from the IMDB dataset.

The project successfully meets all academic requirements by focusing on advanced data preprocessing, rigorous exploratory data analysis (EDA), and a clear comparative analysis of model performance.

## ✅ Objective Fulfillment Summary

| Objective | Status | Implementation Details |
| :--- | :--- | :--- |
| **1. Cleaning & Transformation** | **COMPLETE** | Custom preprocessing included **HTML removal**, **Stopword filtering**, and **Lemmatization** (an advanced technique) to reduce vocabulary and improve semantic clarity. |
| **2. Rigorous EDA & Cleaning** | **COMPLETE** | Exploratory Data Analysis was performed to visualize **Sentiment Balance** and **Review Length Distribution**, which guided the optimal padding length (200 words) for the LSTM model. |
| **3. Implement Two Distinct Models** | **COMPLETE** | Compared **Model 2: Logistic Regression (TF-IDF Baseline)** against **Model 1: LSTM Deep Learning** to analyze trade-offs between speed, complexity, and accuracy. |

## 🧠 Model Comparison and Results

| Model | Feature Engineering | Test Accuracy (Approx.) | Key Advantage |
| :--- | :--- | :--- | :--- |
| **Model 2: Logistic Regression** | TF-IDF | ~89.0% | Fastest training time; serves as a strong, interpretable baseline. |
| **Model 1: LSTM Deep Learning** | Embeddings | **~90.2%** | Achieves the highest accuracy by capturing long-term sequential dependencies and context within the review text. |

## 💻 Technical Requirements

This project utilizes Python 3.x and was executed efficiently using the **T4 GPU runtime** in Google Colab.

**Required Libraries:** `pandas`, `numpy`, `tensorflow`, `keras`, `scikit-learn`, and `nltk`.
