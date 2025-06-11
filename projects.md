---
layout: default
title: Projects
---

# Projects

A collection of my most exciting work — blending machine learning, NLP, time series forecasting, and creative AI into real-world, expressive systems.

---

## 🏠 Colorado Housing & Rent Forecasting

**Tools**: Python, scikit-learn, statsmodels, Elastic Net, XGBoost, SARIMAX  
**Description**:  
Developed a robust time series modeling pipeline to forecast rent and mortgage trends for Colorado single-family homes using Zillow and macroeconomic indicators. Models incorporate feature engineering, lag structure, and regression diagnostics to support practical decision-making.

**Key Highlights**:
- Achieved up to R² = 0.97 on validation sets  
- Applied Elastic Net and XGBoost to tackle multicollinearity and improve generalization  
- Engineered time-aware features and used SARIMAX for economic seasonality  
- Visualized SHAP values and heatmaps for interpretability  
- Fully reproducible code and documented insights  
[GitHub](https://github.com/Orca71/Housing-Market-Forecasting-Time-Series-/tree/main) • [Read Report](https://github.com/Orca71/Housing-Market-Forecasting-Time-Series-/blob/main/HousingForcastReport.pdf)

---

## 🧠 Multimodal Interview Scoring with NLP

**Tools**: TF-IDF, Word2Vec, prosodic features, Random Forest, FNN, SHAP, EBM  
**Description**:  
Built a multimodal ML pipeline to estimate job interview performance and excitement scores using both textual and acoustic features. Combined traditional feature engineering with explainable machine learning for fairness and insight.

**Key Highlights**:
- Fused text (TF-IDF, Word2Vec) and prosodic features (pitch, energy)  
- Performed 5-fold cross-validation with model tuning  
- Achieved higher predictive performance vs unimodal baselines  
- Interpreted results using SHAP and Explainable Boosting Machines (EBM)  
- Dataset: MIT Interview corpus  
[GitHub](https://github.com/Orca71/Interview-outcome-Prediction-Multimodal-ML-) • [Read Report](https://github.com/Orca71/Interview-Outcome-Prediction-Multimodal-ML-/blob/main/Report.pdf)

---

## 📰 Fake News Detection with NLP

**Tools**: BERT, TF-IDF, Logistic Regression, XGBoost, Hugging Face, Gradio  
**Description**:  
Designed and deployed a binary classification system to detect fake news using the LIAR dataset. Compared classic pipelines with transformer-based methods, fine-tuning BERT for optimal results and hosting a public demo.

**Key Highlights**:
- Reformatted LIAR dataset into binary: Fake vs Real  
- Fine-tuned BERT model reached 76% F1 and 63% test accuracy  
- Benchmarked against TF-IDF + Logistic Regression and XGBoost  
- Evaluated using precision, recall, confusion matrix, and F1-score  
- Live demo hosted on Hugging Face Spaces  
[GitHub](https://github.com/Orca71/fake-news-detector) • [Try the Demo](https://huggingface.co/spaces/ShahOfData/shah_fake-news-detector)

---

## 🎼 Wolfie: Emotion-Aware Music Generation *(In Progress)*

**Tools**: Python, PrettyMIDI, FluidSynth, symbolic AI, music theory  
**Description**:  
Wolfie is a personal project exploring the intersection of emotion, harmony, and AI. It generates expressive chord progressions and motifs based on user-selected moods using rule-based logic and symbolic musical structures.

**Key Highlights**:
- Harmonic engine grounded in Circle of Fifths and expressive cadences  
- Emotion-driven mood → scale → chord logic  
- Generates customizable MIDI compositions with tempo, contour, and mode  
- Inspired by expressive works of Bach, Mozart, and Beethoven  
- Ongoing expansion with LSTMs and NLP-to-music pipeline  
[GitHub](https://github.com/Orca71/Wolfie) • [Demo Coming Soon](#)

---

## 💡 Lantern: AI Accounting Assistant *(SaaS – In Development)*

**Tools**: Python, FastAPI, QuickBooks API, OAuth2  
**Description**:  
Lantern is a secure SaaS product that connects with QuickBooks to help small businesses manage accounting tasks. The platform features modular design and secure token handling, with an NLP-based query system currently in development.

*(Not Public yet – Demo coming soon)*
