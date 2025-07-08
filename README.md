#  Fake News Detection using GANs and Source Credibility Scoring (SCS)

A hybrid machine learning system for fake news detection combining Generative Adversarial Networks (GANs) for content analysis and Source Credibility Scoring (SCS) to assess source reliability, delivering improved accuracy and explainability.

---

##  Project Overview

The rapid spread of fake news has emerged as a major threat to public trust, political stability, and social well-being. This project presents a solution that combines advanced content analysis using **Generative Adversarial Networks (GANs)** with **Source Credibility Scoring (SCS)** to improve the accuracy of fake news detection.

By evaluating both the **text content** of articles and the **credibility of sources**, this hybrid approach outperforms traditional models that focus only on content or source separately.

---

##  Key Features

-  Text Preprocessing using NLTK
-  TF-IDF Feature Extraction
-  GAN-based Fake News Detection
-  Source Credibility Scoring (SCS)
-  Decision Fusion of Content & Source Analysis
-  Explainable AI with LIME
-  Random Forest Baseline Model
-  Model Saving with Joblib

---

## Technologies Used

- Python 3
- TensorFlow / Keras
- Scikit-learn
- NLTK
- tldextract
- LIME
- Google Colab / Jupyter Notebook

---

##  How to Run

1. Upload and extract `fake.csv` and `true.csv`.
2. Preprocess the data and extract features.
3. Train GAN and/or Random Forest models.
4. Use trained models to predict new articles.
5. Apply LIME for model interpretation.

---

##  Results

The hybrid system achieved higher accuracy by combining content and source evaluations, with explainable predictions for enhanced trust.


