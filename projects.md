---
layout: default
title: Projects
---

<div class="section" style="margin-bottom: 32px;">
  <div class="hero-label">Selected Work</div>
  <h1 style="font-size: clamp(2rem, 3.5vw, 2.8rem); margin-bottom: 16px;">Projects</h1>
  <p style="max-width: 600px;">Each project here started with a question about where current AI systems fall short — and an attempt to build something that actually addresses it.</p>
</div>

<hr>

<div class="project-detail">
  <div class="project-detail-header">
    <div class="project-index">01 / 06</div>
    <h2>Lantern Intelligence</h2>
    <div class="project-status demo">Demo on Request</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">RAG</span><span class="tag">ChromaDB</span><span class="tag">Ollama</span><span class="tag">SQLite</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>Most financial AI either hallucinates numbers or ignores the actual data entirely. Lantern solves that by grounding every response in SQL execution before the LLM is ever involved — making outputs auditable and trustworthy for real business decisions.</p>
  <p>A multi-agent AI accounting assistant that lets small businesses query their financial data in plain English. The system runs three simulated company databases simultaneously — the same question produces different, grounded answers across each one.</p>
  <ul class="project-highlights">
    <li>SQL-first architecture: deterministic computation runs before any LLM call</li>
    <li>ChromaDB with all-MiniLM-L6-v2 embeddings for semantic document retrieval</li>
    <li>Eight financial metrics: net profit margin, DSO, burn rate, churn rate, and more</li>
    <li>Fully self-hosted: llama3.1:8b on RunPod A100 — no external API dependency</li>
    <li>Browser-side conversation memory with runtime SQL file loading</li>
  </ul>
  <div class="project-note">Available for live demo upon request</div>
</div>

<hr>

<div class="project-detail">
  <div class="project-detail-header">
    <div class="project-index">02 / 06</div>
    <h2>Lumen</h2>
    <div class="project-status in-dev">In Development</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">LLM Eval</span><span class="tag">LLM-as-judge</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>Most teams deploying LLMs have no systematic way to know when their model regresses, drifts, or fails on edge cases. Lumen treats evaluation as ongoing infrastructure, not a one-time check — because the real risk isn't the first deployment, it's the tenth.</p>
  <p>A blackbox LLM evaluation system that tests any model through inputs and outputs alone — no access to model internals required. Works with any provider, requires no infrastructure changes from the user.</p>
  <ul class="project-highlights">
    <li>Blackbox-only approach: input/output evaluation works across any LLM provider</li>
    <li>Three-part scoring engine: LLM-as-judge, reference scoring, and behavioral probing</li>
    <li>Ingestion layer capturing input/output pairs from production traffic</li>
    <li>Result aggregation tracking trends, regressions, and performance over time</li>
    <li>Alert and reporting engine serving both technical and non-technical stakeholders</li>
    <li>Version and history store for longitudinal model comparison</li>
  </ul>
  <div class="project-note">In development</div>
</div>

<hr>

<div class="project-detail">
  <div class="project-detail-header">
    <div class="project-index">03 / 06</div>
    <h2>Abductive Reasoning with LLMs</h2>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Python</span><span class="tag">PyTorch</span><span class="tag">Transformers</span><span class="tag">Contrastive Learning</span><span class="tag">RST</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>LLMs are surprisingly bad at choosing the most plausible explanation for an event — they pattern-match rather than reason causally. When two hypotheses look nearly identical in embedding space, models can't reliably pick the right one. This research identifies exactly where that failure begins.</p>
  <p>A research project exploring abductive inference through a dual-hypothesis framework — contrasting gold explanations, evidence-derived hypotheses, and deliberately inverted hypotheses to probe the geometry of abductive space. Submitted to SemEval 2026 Task 12. Co-authored with Yifei Zhang and Echo Canaday at CU Boulder.</p>
  <ul class="project-highlights">
    <li>RST-guided hypothesis construction using nucleus-satellite discourse relations</li>
    <li>Frozen BGE-small encoder with contrastive and ranking objectives: triplet loss, margin ranking, InfoNCE, and difference-vector variants</li>
    <li>Key finding: cosine similarity between gold, evidence-derived, and inverted hypotheses collapses to ≈0.93–0.94 — frozen encoders cannot recover abductive structure regardless of training objective</li>
    <li>Conclusion: abductive plausibility is not linearly recoverable from semantic embedding space and requires joint encoder fine-tuning or discourse-grounded architectures</li>
  </ul>
  <div class="project-links">
    <a href="/semeval-report.pdf" target="_blank">Read Paper ↗</a>
    <a href="https://github.com/Orca71/Task-12-Abductive-Event-Reasoning" target="_blank">GitHub ↗</a>
  </div>
</div>

<hr>

<div class="project-detail">
  <div class="project-detail-header">
    <div class="project-index">04 / 06</div>
    <h2>Housing Price Forecasting</h2>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Time-series Regression</span><span class="tag">XGBoost</span><span class="tag">Elastic Net</span><span class="tag">Python</span><span class="tag">Zillow API</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>Housing affordability is one of the most consequential financial decisions people make, yet most analysis is surface-level. This project treats the buy vs. rent question as a rigorous forecasting problem — modeling the macroeconomic drivers that actually move prices, not just the prices themselves.</p>
  <p>A time-series study predicting rent and mortgage costs across Denver, Boulder, and Fort Collins using macroeconomic indicators from Zillow, the Federal Reserve, and the Bureau of Labor Statistics. Twelve models were developed and compared; XGBoost and Elastic Net emerged as the strongest performers.</p>
  <ul class="project-highlights">
    <li>Dual model architecture: separate regression pipelines for mortgage and rent prediction</li>
    <li>Full assumption validation: linearity, homoscedasticity, independence of errors, normality — with documented corrections for each violation</li>
    <li>Applied log transformation, polynomial terms, and lag features to resolve heteroskedasticity and autocorrelation</li>
    <li>Elastic Net R² of 0.97 on test data for rent; XGBoost R² of 0.96 for mortgage — both without overfitting</li>
    <li>Feature importance analysis identifying number of listings and heat index as primary price drivers</li>
    <li>Data sourced from Zillow Housing Database, FRED, and Bureau of Labor Statistics (2018–2024)</li>
  </ul>
  <div class="project-links">
    <a href="/housing-forecast.pdf" target="_blank">Read Report ↗</a>
  </div>
</div>

<hr>

<div class="project-detail">
  <div class="project-detail-header">
    <div class="project-index">05 / 06</div>
    <h2>Multimodal Interview Outcome Predictor</h2>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">TF-IDF</span><span class="tag">Word2Vec</span><span class="tag">Prosodic Features</span><span class="tag">Random Forest</span><span class="tag">SHAP</span><span class="tag">EBM</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>Prediction accuracy alone isn't enough when the decision affects people. This project was built around interpretability from the start — understanding exactly which signals drive each prediction so the model's behavior can be audited and trusted.</p>
  <ul class="project-highlights">
    <li>Text features (TF-IDF, Word2Vec) combined with prosodic signals — pitch and energy</li>
    <li>SHAP and Explainable Boosting Machines for feature-level interpretability on every prediction</li>
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
    <div class="project-index">06 / 06</div>
    <h2>Wolfie — Emotion-Aware Music Generation</h2>
    <div class="project-status deferred">In Design</div>
  </div>
  <div class="tags" style="margin-bottom: 20px;">
    <span class="tag">Generative AI</span><span class="tag">Deep Learning</span><span class="tag">Emotion Modeling</span><span class="tag">Music</span>
  </div>
  <p class="why-label-text">Why it matters</p>
  <p>Most generative music AI optimizes for statistical plausibility — it sounds like music, but it doesn't feel like anything in particular. Wolfie is built around the opposite goal: emotional coherence first, with harmonic structure serving the feeling rather than the other way around.</p>
  <ul class="project-highlights">
    <li>Emotion-to-harmony mapping as the core generative mechanism</li>
    <li>Sequence modeling for melody and chord progression generation</li>
    <li>Focused on expressive, emotionally coherent output over generic MIDI patterns</li>
  </ul>
  <div class="project-note">Deferred pending hardware — design phase complete</div>
</div>
