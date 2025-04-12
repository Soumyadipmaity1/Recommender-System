# 📊 Recommender System

## 📝 Abstract

In modern e-commerce, customer reviews hold deep, nuanced insights into product features that go far beyond overall ratings. Traditional recommendation systems often overlook low-rated or negative reviews, labeling them as non-informative. However, some of these reviewers—especially consistent negative users—offer reliable, quality-driven feedback that can significantly improve recommendation accuracy.

This project aims to **bridge sentiment analysis with user reliability assessment**, using **attention mechanisms** to extract **aspect-level preferences** and **viewpoints** from customer reviews. By identifying genuine dissatisfaction and filtering biased input, this system enhances the **interpretability**, **personalization**, and **context-awareness** of product recommendations.

## 🚀 Features

- 🎯 **Aspect-Level Sentiment Analysis**
- 🧠 **Attention-Based Deep Learning Models**
- 📌 **Reliable Negative User Identification**
- 📚 **Natural Language Processing (NLP)**
- 📈 **Matrix Factorization using SVD**
- 📊 **Hit Ratio for Ranking Accuracy**
- 🧹 **Advanced Text Preprocessing and Normalization**
- ⚙️ **Context-Aware Personalized Recommendations**

## 📖 Table of Contents

1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
   - Tools and Technologies Used
3. [Problem Statement](#problem-statement)
   - Project Planning & Analysis
   - System Architecture
4. [Implementation](#implementation)
   - Methodology
   - Dataset Aggregation
   - Preprocessing & Normalization
   - Matrix Formation & SVD
   - Training & Evaluation
5. [Standards Adopted](#standards-adopted)
6. [Conclusion & Future Scope](#conclusion--future-scope)
## 📚 Literature Review

Recent advancements in attention-based deep learning models have revolutionized sentiment analysis, particularly at the aspect level. However, there's a gap when it comes to capturing the **individual user perspective**, especially from **low-rated but insightful reviews**.

**Tools & Technologies Used:**
- Python
- NumPy / Pandas
- Scikit-learn
- NLTK / spaCy
- TensorFlow / PyTorch
- SVD (Singular Value Decomposition)

## ⚠️ Problem Statement

Despite the advancements in recommender systems, users who consistently provide **low ratings** are often disregarded. Many of these users are actually **reliable reviewers** who highlight **quality concerns**. This system aims to identify such users and incorporate their opinions into the recommendation process.

## 🛠️ Implementation

### 🔁 Methodology
- Attention-based aspect extraction from reviews.
- Reliability scoring via sentiment-rating alignment.
- Matrix Factorization using SVD for preference prediction.

### 📦 Dataset Aggregation
- User-generated product reviews.
- Attributes: Review text, Ratings, User IDs.

### 🧹 Preprocessing
- Tokenization, Lemmatization
- Stopword Removal & Normalization

### 🧮 Matrix Formation & SVD
- User-Item matrix construction
- Dimensionality reduction and latent feature extraction

### 📈 Evaluation
- Accuracy via **Hit Ratio**
- Validation using real-world test data

## ✅ Standards Adopted

- **Design Standards:** Modular, Scalable, Reusable
- **Coding Standards:** PEP8 Compliance
- **Testing Standards:** Unit & Integration Testing with assertion checks

## 🏁 Conclusion & Future Scope

### ✔️ Conclusion
The proposed recommender system significantly improves **recommendation accuracy** and **user trustworthiness analysis** by integrating **aspect-based sentiment analysis** with **user reliability scoring**.

### 🔮 Future Scope
- Integrating real-time review streams.
- Multi-language support for global e-commerce platforms.
- Visual recommendation insights using explainable AI (XAI).

## 📌 How to Run

```bash
git clone https://github.com/Soumyadipmaity1/Recommender-System.git
cd recommender-system
pip install -r arts.txt
python main.ipynb
```

## 🤝 Contributors

| Name               | GitHub Profile | Email |
|--------------------|----------------|-------|
| [Soumyadip Maity](https://github.com/soumyadipmaity1) | [@soumyadipmaity1](https://github.com/soumyadipmaity1) | [22053029@kiit.ac.in](mailto:22053029@kiit.ac.in) |
| [Sudeep Kumar Manna](https://github.com/sudeep2704) | [@sudeep2704](https://github.com/sudeep2704) | [22053032@kiit.ac.in](mailto:22053032@kiit.ac.in) |
| [Rahul Ghosh](https://github.com/rahulghosh111111) | [@rahulghosh111111](https://github.com/rahulghosh111111) | [22052660@kiit.ac.in](mailto:22052660@kiit.ac.in) |
