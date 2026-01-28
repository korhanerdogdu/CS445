# 🎓 Sabancı University — CS445 (Natural Language Processing) Course Project  
## 🌍 SemEval-2026 Task 9 — Detecting Online Polarization (Subtask 1)

Welcome! This repository contains our **CS445 (NLP)** course project at **Sabancı University**. In CS445, student teams select a **SemEval-2026 shared task** and develop an NLP system grounded in **academic literature**, supported by **systematic experimentation**, and delivered as a **reproducible implementation** along with milestone and final reports/presentations.

We chose **SemEval-2026 Task 9: Detecting Multilingual, Multicultural & Multievent Online Polarization**, and focused on the **mandatory Subtask 1**, which is a **binary text classification** problem: given a text sample in multiple languages, the system predicts whether it is **Polarized** or **Non-Polarized**. Since polarization datasets can exhibit **class imbalance**, we emphasize evaluation practices that reflect performance fairly across classes (e.g., **Macro-F1** rather than only accuracy), and we designed our experiments accordingly.

### 🧠 What We Did (High-Level)
Our work follows a progressive modeling pipeline—from simple, interpretable baselines to advanced multilingual architectures—so that each step adds meaningful value and helps us understand what improves the task:

- 🧱 **Classical baseline:** We implemented a strong traditional approach using **TF-IDF features + Logistic Regression** to establish a reliable baseline and validate the end-to-end pipeline quickly.
- 🧬 **Neural baselines:** We explored sequence models such as **(C)LSTM / BiLSTM** and **BiLSTM + Attention**, which learn richer representations than sparse features. We also experimented with additional signals like **language identity features** to better support multilingual learning.
- 🤗 **Transformer fine-tuning (multilingual):** We fine-tuned several transformer-based multilingual encoders commonly used for cross-lingual classification, including **XLM-R (base/large)**, **InfoXLM**, **mDeBERTa-v3**, and **RemBERT**, comparing their behavior across multilingual settings.
- ⚖️ **Class imbalance handling:** To reduce bias toward majority classes and improve robustness, we experimented with imbalance-aware strategies such as **Focal Loss** and **weighted sampling / inverse-frequency weighting**.
- 🧩 **Ensembling for robustness:** Because different models can excel on different languages and linguistic patterns, we built an **ensemble** approach (soft voting / weighted combination) to mitigate model-specific weaknesses and improve stability across languages.
- 🧠 **Parameter-efficient tuning (additional exploration):** As an extra direction, we also explored efficient fine-tuning techniques (e.g., **QLoRA-style tuning**) for decoder-style models under compute/memory constraints.

### 🧪 Evaluation & Reproducibility
SemEval-style tasks often rely on **hidden test sets**, so reliable validation is essential. We used reproducible **train/validation splits** (fixed seed) and reported standard classification analyses in our documentation (e.g., macro-focused metrics and diagnostic plots such as confusion matrices and PR-style visualizations). Full methodological details, experimental settings, and qualitative/quantitative analyses are provided in the project reports included in this repository.

### 📚 CS445 Course Expectations (How This Repo Fits)
This project aligns with CS445 requirements by:
- 📖 following a **literature-driven** approach (related work from reputable venues),
- 🧪 demonstrating an **iterative experimentation process** across multiple model families,
- 🧠 clearly emphasizing **contribution and engineering/research journey**, not only leaderboard score,
- 📝 delivering milestone + final **reports and presentations**, and a runnable system (notebook/scripts) as required by the course.

### 📁 Repository Contents
This repository typically includes:
- 📄 **Milestone Report** and **Final Report** and presentations 
- 💻 Source code and/or notebooks for baselines, neural models, transformer fine-tuning, and ensembling




