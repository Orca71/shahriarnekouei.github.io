---
layout: default
title: Projects
---

<div class="section" style="margin-bottom: 32px;">
  <div class="hero-label">Selected Work</div>
  <h1 style="font-size: clamp(2rem, 3.5vw, 2.8rem); margin-bottom: 16px;">Projects</h1>
  <p style="max-width: 600px;">A selection of work combining machine learning, NLP, reasoning, and creative AI — systems that are practical, expressive, and thoughtfully designed.</p>
</div>

<hr>

<div class="project-detail">

  <div class="project-detail-header">
    <div class="project-index">01 / 04</div>
    <h2>Lantern Intelligence</h2>
    <div class="project-status in-dev">In Development</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">RAG</span><span class="tag">ChromaDB</span><span class="tag">Ollama</span><span class="tag">SQLite</span>
  </div>
  <p>A multi-agent AI accounting assistant designed to help small businesses understand and manage their financial data through natural language. Lantern combines SQL-first deterministic computation with RAG pipelines, grounding every response in real company data rather than model assumptions.</p>
  <p>The system runs three simulated service company databases simultaneously — the same question produces different, grounded answers across each one, demonstrating how context-aware AI should behave in enterprise settings.</p>
  <ul class="project-highlights">
    <li>FastAPI backend with keyword-based query routing — no LLM overhead for intent classification</li>
    <li>ChromaDB vector store with all-MiniLM-L6-v2 embeddings for semantic document retrieval</li>
    <li>Eight financial SQL queries: net profit margin, DSO, burn rate, revenue per employee, churn rate, and more</li>
    <li>Ollama running llama3.1:8b on RunPod A100 — fully self-hosted, no external API dependency</li>
    <li>Browser-side conversation memory with runtime SQL file loading</li>
  </ul>
  <div class="project-note">Demo coming soon</div>

</div>

<hr>

<div class="project-detail">

  <div class="project-detail-header">
    <div class="project-index">02 / 04</div>
    <h2>Abductive Reasoning with LLMs</h2>
    <div class="project-status in-dev">In Development</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Python</span><span class="tag">PyTorch</span><span class="tag">Transformers</span><span class="tag">Contrastive Learning</span>
  </div>
  <p>A research project exploring how AI systems choose the most plausible explanation for an event. Current LLMs struggle when competing hypotheses look nearly identical in embedding space — they pattern-match rather than reason causally. This work investigates where that failure begins and what architectural changes can address it.</p>
  <p>Prepared for submission to <strong>SemEval 2026 Task 12</strong>, where abductive reasoning and causal hypothesis selection are the central challenges.</p>
  <ul class="project-highlights">
    <li>Custom hypothesis-generation and reasoning pipeline modeled on the SemEval Task 12 structure</li>
    <li>Contrastive learning objectives to discriminate between semantically similar but causally distinct hypotheses</li>
    <li>Finding: frozen encoder embeddings cannot recover causal structure regardless of downstream training objective</li>
    <li>Goal: a model that selects the best explanation — not just the closest paraphrase</li>
  </ul>
  <div class="project-note">Code &amp; preprint coming soon</div>

</div>

<hr>

<div class="project-detail">

  <div class="project-detail-header">
    <div class="project-index">03 / 04</div>
    <h2>Multimodal Interview Outcome Predictor</h2>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">TF-IDF</span><span class="tag">Word2Vec</span><span class="tag">Prosodic Features</span><span class="tag">Random Forest</span><span class="tag">SHAP</span><span class="tag">EBM</span>
  </div>
  <p>A system that combines linguistic and acoustic signals to estimate interview performance and excitement levels. The project prioritized not just prediction accuracy, but interpretability — understanding exactly which cues drive each decision.</p>
  <ul class="project-highlights">
    <li>Combined text features (TF-IDF, Word2Vec) with prosodic signals including pitch and energy</li>
    <li>Extensive cross-validation and model comparison across Random Forest and feedforward architectures</li>
    <li>SHAP and Explainable Boosting Machines to surface feature-level influence on predictions</li>
    <li>Built on the MIT Interview dataset</li>
  </ul>
  <div class="project-links">
    <a href="https://github.com/Orca71/Interview-outcome-Prediction-Multimodal-ML-" target="_blank">GitHub ↗</a>
    <a href="https://github.com/Orca71/Interview-Outcome-Prediction-Multimodal-ML-/blob/main/Report.pdf" target="_blank">Read Report ↗</a>
  </div>

</div>

<hr>

<div class="project-detail">

  <div class="project-detail-header">
    <div class="project-index">04 / 04</div>
    <h2>Wolfie — Emotion-Aware Music Generation</h2>
    <div class="project-status deferred">In Design</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Generative AI</span><span class="tag">Deep Learning</span><span class="tag">Emotion Modeling</span><span class="tag">Music</span>
  </div>
  <p>A generative system that produces harmonically expressive music driven by emotional state input. The goal is to bridge affective computing and music theory — generating compositions that feel emotionally coherent, not just statistically plausible.</p>
  <ul class="project-highlights">
    <li>Emotion-to-harmony mapping as the core generative mechanism</li>
    <li>Sequence modeling for melody and chord progression generation</li>
    <li>Focused on expressive output over generic MIDI patterns</li>
  </ul>
  <div class="project-note">Deferred pending hardware — design phase complete</div>

</div>
