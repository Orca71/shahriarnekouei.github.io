---
layout: default
title: Projects
---

# Projects

A collection of my most exciting work — blending machine learning, NLP, multimodal reasoning, and creative AI into real-world, expressive systems.

---

## 🧩 Abductive Reasoning Research *(In Development)*

**Tools**: Python, PyTorch, Transformers, Contrastive Learning  
**Description**:  
An ongoing research project exploring abductive inference — the process of identifying the most plausible explanation for a given observation. This work investigates how LLMs handle subtle causal distinctions and hypothesis selection when semantic similarity causes classical training signals to collapse.

**Key Highlights**:
- Designed hypothesis-generation and reasoning pipeline based on the SemEval-2026 Task 12 framework  
- Analyzed encoder collapse in embedding space (semantic similarity ≈ 0.94 across hypotheses)  
- Experimented with contrastive objectives (InfoNCE, difference-based losses)  
- Investigating new encoder architectures for causal sensitivity  
- Aim: build models capable of distinguishing tightly overlapping hypotheses  

*(Code & preprint coming soon)*

---

## 🧠 Multimodal Interview Scoring with NLP

**Tools**: TF-IDF, Word2Vec, prosodic features, Random Forest, FNN, SHAP, EBM  
**Description**:  
Built a multimodal ML pipeline to estimate job interview performance and excitement scores using both textual and acoustic features. Combined traditional feature engineering with explainable machine learning for fairness and insight.

**Key Highlights**:
- Fused text (TF-IDF, Word2Vec) and prosodic features (pitch, energy)  
- Performed 5-fold cross-validation with extensive model tuning  
- Achieved higher predictive performance vs unimodal baselines  
- Interpreted results using SHAP and Explainable Boosting Machines  
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
Wolfie explores the intersection of emotion, harmony, and AI. It generates expressive chord progressions and motifs based on user-selected moods using rule-based logic and symbolic musical structures.

**Key Highlights**:
- Harmonic engine built on Circle of Fifths & expressive cadences  
- Emotion-driven mood → scale → chord logic  
- Generates customizable MIDI compositions with tempo, contour, and mode  
- Inspired by expressive works of Bach, Mozart, and Beethoven  
- Ongoing expansion: LSTMs, NLP-to-music pipeline  
[GitHub](https://github.com/Orca71/Wolfie) • *Demo Coming Soon*

---

## 💡 Lantern: AI Accounting Assistant *(SaaS – In Development)*

**Tools**: Python, FastAPI, QuickBooks API, OAuth2  
**Description**:  
Lantern is a secure SaaS product that connects with QuickBooks to help small businesses manage accounting tasks. The platform uses a multi-agent NLP interface, modular intent routing, and secure token handling.

*(Not public yet – Demo coming soon)*
