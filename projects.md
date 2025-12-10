---
layout: default
title: Projects
---

# Projects

A selection of my works, combining machine learning, NLP, reasoning, and creative AI into systems that are practical, expressive, and thoughtfully designed.

---

## 🧩 Abductive Reasoning Research *(In Development)*

**Tools**: Python, PyTorch, Transformers, Contrastive Learning  
**Description**:  
A research project exploring abductive inference — how an AI system chooses the most plausible explanation for an event. I’m studying where current LLMs struggle, especially when different hypotheses look almost identical in the embedding space. The long-term goal is to build reasoning models that are more sensitive, discriminative, and grounded in causal structure.

This work is part of my ongoing preparation for submitting to the **SemEval 2026 Task 12 competition**, where abductive reasoning and causal hypothesis selection are the central challenges.

**Key Highlights**:
- Developed a custom hypothesis-generation and reasoning pipeline inspired by the SemEval Task 12 structure  
- Experimented with contrastive objectives to separate closely related hypotheses  
- Exploring encoder designs that better capture causal nuance  
- Aim: a model that can genuinely “choose the best explanation,” not just the closest paraphrase  

*(Code & preprint coming soon)*

---

## 🧠 Multimodal Interview Scoring with NLP

**Tools**: TF-IDF, Word2Vec, prosodic features, Random Forest, FNN, SHAP, EBM  
**Description**:  
A project that brings together text analysis and acoustic features to estimate interview performance and excitement levels. The focus was not only on prediction, but also transparency — making sure the model could be interpreted and its behavior explained.

**Key Highlights**:
- Combined linguistic features with prosodic ones such as pitch and energy  
- Performed extensive cross-validation and model comparison  
- Used SHAP and EBM to understand how specific cues influence predictions  
- Built on the MIT Interview dataset  
[GitHub](https://github.com/Orca71/Interview-outcome-Prediction-Multimodal-ML-) • [Read Report](https://github.com/Orca71/Interview-Outcome-Prediction-Multimodal-ML-/blob/main/Report.pdf)

---

## 📰 Fake News Detection with NLP

**Tools**: BERT, TF-IDF, Logistic Regression, XGBoost, Hugging Face, Gradio  
**Description**:  
An end-to-end NLP system for identifying fake and real news articles. The project compares classical text-based models with modern transformer approaches, showing how different techniques behave on deceptive content.

**Key Highlights**:
- Prepared a clean binary version of the LIAR dataset  
- Compared traditional pipelines with transformer fine-tuning  
- Built an interactive web demo on Hugging Face Spaces  
[GitHub](https://github.com/Orca71/fake-news-detector) • [Try the Demo](https://huggingface.co/spaces/ShahOfData/shah_fake-news-detector)

---

## 🎼 Wolfie: Emotion-Aware Music Generation *(In Progress)*

**Tools**: Python, PrettyMIDI, FluidSynth, symbolic AI, music theory  
**Description**:  
Wolfie is a personal and artistic exploration of emotion in music. The system generates expressive chord progressions and motifs based on a user’s chosen mood, blending symbolic rules with classical harmony.

**Key Highlights**:
- Built a harmonic engine inspired by the Circle of Fifths and expressive cadences  
- Converts emotional intent into musical structures (scale, mode, progression)  
- Produces MIDI files with adjustable tempo and contour  
- Future plans include LSTM-based composition and NLP-to-music translation  
[GitHub](https://github.com/Orca71/Wolfie) • *Demo Coming Soon*

---

## 💡 Lantern: AI Accounting Assistant *(SaaS – In Development)*

**Tools**: Python, FastAPI, QuickBooks API, OAuth2  
**Description**:  
Lantern is a multi-agent AI assistant designed to help small businesses understand and manage their accounting workflows. It combines secure QuickBooks integration with modular intent routing and a natural-language interface tailored for accounting tasks.

*(Not public yet – Demo coming soon)*
