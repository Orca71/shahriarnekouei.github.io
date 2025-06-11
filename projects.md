---
layout: default
title: Projects
---

# Projects

Welcome to a collection of my most exciting projects — where machine learning, NLP, time series forecasting, and musical intelligence come together through creativity and rigor.

---

## 🏠 Colorado Housing & Rent Forecasting

**Tools**: Python, scikit-learn, statsmodels, Elastic Net, XGBoost, SARIMAX  
**Description**:  
Developed a time series modeling system to forecast rent and mortgage trends for Colorado single-family homes using Zillow and economic indicators. The models incorporate feature engineering, lag analysis, and regression diagnostics to support real-world decision-making.

**Key Highlights**:
- Achieved R² up to 0.97 on validation sets  
- Used Elastic Net and XGBoost to address multicollinearity and boost performance  
- Implemented time-series-aware data splits and transformations  
- Applied SHAP for interpretability and correlation heatmaps  
- Final code and results are documented and reproducible  
[GitHub](https://github.com/Orca71/Housing-Market-Forecasting-Time-Series-/tree/main) • [Read Report](https://github.com/Orca71/Housing-Market-Forecasting-Time-Series-/blob/main/HousingForcastReport.pdf)

---

## 🧠 Multimodal Interview Scoring with NLP

**Tools**: TF-IDF, Word2Vec, prosodic features, Random Forest, FNN, SHAP  
**Description**:  
Built a multimodal machine learning pipeline to estimate performance and excitement scores from job interviews using both language and audio features. Applied explainable ML methods to ensure interpretability and fairness.

**Key Highlights**:
- Combined TF-IDF and Word2Vec embeddings with prosodic speech features  
- Conducted 5-fold cross-validation and hyperparameter tuning  
- Multimodal models showed superior predictive power over single-modality baselines  
- Applied SHAP and EBM for transparency and feature importance  
- Based on MIT Interview corpus  
[GitHub](https://github.com/Orca71/Interview-outcome-Prediction-Multimodal-ML-) • [Read Report](https://github.com/Orca71/Interview-Outcome-Prediction-Multimodal-ML-/blob/main/Report.pdf)

---

## 📰 Fake News Detection with NLP (Completed)

**Tools**: BERT, TF-IDF, Logistic Regression, XGBoost, Gradio  
**Description**:  
Designed a binary text classification system to detect fake news using the LIAR dataset. This project explored both classic NLP pipelines and transformer-based approaches, culminating in a fine-tuned BERT model deployed with an interactive demo.

**Key Highlights**:
- Converted LIAR dataset from 6-class to binary: Real vs Fake  
- Fine-tuned BERT model achieved ~63% test accuracy with strong F1 performance  
- Compared performance with TF-IDF + Logistic Regression and XGBoost  
- Evaluated with confusion matrix, precision, recall, and F1-score  
- Deployed live Gradio demo on Hugging Face Spaces  
[GitHub Repository](https://github.com/Orca71/fake-news-detector) • [Try the Live Demo](https://huggingface.co/spaces/ShahOfData/shah_fake-news-detector)

---

## 🎼 Wolfie: AI-Powered Mood-Based Music Generator *(In Progress)*

**Tools**: Python, PrettyMIDI, FluidSynth, Symbolic AI, Music Theory  
**Description**:  
Wolfie is a personal research project that merges emotion, music theory, and machine intelligence. The system generates harmonically rich chord progressions and melodies based on user-selected moods, using a blend of symbolic AI and generative music logic.

**Key Highlights**:
- Rule-based harmonic engine based on the Circle of Fifths and classical cadences  
- Customizable emotion, tempo, key mode, and melodic contour  
- Exports expressive MIDI compositions for playback and editing  
- Inspired by expressive works of Bach, Mozart, and Beethoven  
- Currently extending with LSTMs for generative expressiveness  
[GitHub](https://github.com/Orca71/Wolfie) • [Demo coming soon](#)

---
