# 🛒 Fake Product Review Detection Using Machine Learning  
A Machine Learning project that identifies **fake vs. genuine product reviews** using Natural Language Processing (NLP), TF-IDF feature extraction, and classification models such as **Logistic Regression, Random Forest, and XGBoost**.

Fake reviews mislead customers, manipulate product ratings, and harm trust on e-commerce platforms. This system helps detect fraudulent reviews by analyzing text patterns, sentiment, and linguistic behavior.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Project Workflow](#project-workflow)
- [Source Code Summary](#source-code-summary)
- [Model Performance](#model-performance)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

---

## 📝 Overview  
Fake reviews on platforms like Amazon, Yelp, and TripAdvisor influence consumer decisions and distort product ratings.  
According to your project description (PDF pp. 1–2) :contentReference[oaicite:1]{index=1}:

- Fake reviews may be posted by bots or paid individuals.  
- Traditional moderation is slow and ineffective.  
- ML + NLP provide an automated and scalable solution.

This project builds a **classification model** that uses linguistic features extracted from review text to classify each review as **real or fake**.

---

## ⭐ Key Features  
From the *Proposed System Features* section (PDF page 1–2) :contentReference[oaicite:2]{index=2}:

✔ Automated fake review detection  
✔ Text preprocessing + NLP  
✔ TF-IDF based feature extraction  
✔ Machine Learning classifiers  
✔ Performance metrics  
✔ Visualizations (word cloud, confusion matrix, class distribution)

---

## 🧾 Dataset  
As shown in the *Source Code* section (PDF page 5) :contentReference[oaicite:3]{index=3}:

- Dataset includes **review text**, **rating**, **category**, and **label** (0 = real, 1 = fake).  
- Loaded from a zipped CSV file:  
# Fake-Product-Detector
