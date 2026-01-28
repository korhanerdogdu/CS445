# 🎓 Sabancı University — CS445 (Natural Language Processing) Course Project

Welcome! This repository contains our **CS445 (NLP)** course project at **Sabancı University**.  
In CS445, student teams select a task from the **SemEval-2026 shared tasks** and develop an NLP system by combining:
- 📚 **relevant research literature**
- 🧪 **systematic experimentation**
- 🧩 **a reproducible and runnable implementation**
- 📝 **well-structured milestone + final reports and presentations**

> SemEval is a workshop held alongside **EMNLP**, where research groups release tasks + datasets and teams build systems to solve them. :contentReference[oaicite:0]{index=0}

---

## 🧩 Project Selection

As specified in the official course project document: :contentReference[oaicite:1]{index=1}

- Each group chooses **one** of **six** SemEval tasks proposed for the course.
- Some tasks contain **multiple subtasks**:
  - The course clearly states **which subtask is mandatory** (others may be optional).
- The expectation is not only achieving a good score, but also demonstrating:
  - a clear research process,
  - thoughtful design decisions,
  - and meaningful contributions beyond copying an existing solution. :contentReference[oaicite:2]{index=2}

---

## 🌍 Our Chosen SemEval Task

We chose:

- **SemEval-2026 Task 9: Detecting Multilingual, Multicultural and Multievent Online Polarization**
- ✅ **Subtask 1 is mandatory** for Task 9 (additional subtasks are optional). :contentReference[oaicite:3]{index=3}

📌 This repository focuses on the **course project implementation and documentation** for the selected SemEval task.  
📄 Our detailed experiments and findings are provided in the **reports** included in this repo.

---

## 🗂️ Dataset & Data Curation (General Rules)

SemEval tasks provide an official dataset. In this course project: :contentReference[oaicite:4]{index=4}

- You may **use the provided dataset directly**.
- You may also **curate additional datasets** if you believe they improve your system.
- You may apply **data augmentation** techniques when appropriate.
- Since SemEval evaluations often involve a **hidden test set**, the course recommends:
  - ✅ **cross-validation**, or
  - ✅ using a **fixed random seed** for reproducible train/validation splits. :contentReference[oaicite:5]{index=5}

> ⚠️ If task organizers release test data publicly, it should be used **only for evaluation**, not for model improvement. :contentReference[oaicite:6]{index=6}

---

## 📚 Research & Literature Requirement

A core part of CS445 projects is grounding your approach in **reputable academic work**. :contentReference[oaicite:7]{index=7}

You are expected to:
- Perform a literature search early in the project
- Cite and discuss prior work that motivates your design choices
- Include a minimum number of papers in the report (see “Report Requirements” below)

✅ The course restricts acceptable papers to approved venues such as:  
**ACL, EMNLP, NeurIPS, CoNLL, NAACL, EACL, COLING, LREC**, and SCI-Expanded journals. :contentReference[oaicite:8]{index=8}

---

## 🧑‍💻 Use of Existing Code & Academic Integrity

You may use:
- external libraries (e.g., HuggingFace, Kaggle toolkits),
- open-source implementations,
- public baselines.

But the course requires: :contentReference[oaicite:9]{index=9}
- 🔍 **Clearly stating what you used**
- ✍️ **Clearly explaining your own contribution**
- 🚫 Not presenting external code as your own (plagiarism)

Importantly, the course emphasizes that:
> **Your contribution is more important than simply submitting the best F1 score.**  
You should try multiple approaches and demonstrate your journey. :contentReference[oaicite:10]{index=10}

---

## 📝 Report Requirements (Expected Structure)

The final project report is expected to include the following sections: :contentReference[oaicite:11]{index=11}

1. **Introduction** — task overview + approach summary  
2. **Related Work** — brief literature review (**≥ 5 papers**)  
3. **Methodology** — dataset choice + training details for reproducibility  
4. **Results** — required metrics, plots, and experiments tried  
5. **Discussion** — design tradeoffs, limitations, future improvements  
6. **Conclusion** — summary of key points  
7. **Individual Contributions** — who did what

📌 The course also recommends that you **show your journey**, including attempts that were not used in the final system. :contentReference[oaicite:12]{index=12}

---

## 🎤 Deliverables & Timeline (Course)

### ✅ Milestone Deliverables (November)
- 📄 **Milestone report** (max **4 pages**, excluding references/appendix)
- 🧑‍🏫 **5-minute presentation + 5-minute Q&A**
- 👥 All members must attend; Q&A contributes to individual grading :contentReference[oaicite:13]{index=13}

### ✅ Final Deliverables (January)
- 📄 **Final report** (max **8 pages**, excluding references/appendix)
- 💻 **Well-commented runnable system** (Jupyter Notebook + required files)
- 🧑‍🏫 **25-minute presentation + 5-minute Q&A**
- 👥 Everyone presents their contribution; Q&A contributes to individual grading :contentReference[oaicite:14]{index=14}

---

## 🧮 Grading (High-Level)

The course grading includes both group and individual evaluation components: :contentReference[oaicite:15]{index=15}

- Milestone presentation/report
- Final group report + code
- Submission to the task website
- **Individual performance** (presentation + Q&A + contribution)

---

## 🤖 AI Usage Policy (Course)

The course policy allows AI tools for: :contentReference[oaicite:16]{index=16}
- ✅ spell-checking
- ✅ improving writing flow *after you write the report yourself*

But does **not** allow:
- ❌ writing the report from scratch using AI
- ❌ writing the full codebase using AI (beyond permitted syllabus use)

---

## 📁 What You’ll Find in This Repository

Typical contents include:
- 📄 Milestone and Final reports (PDF)
- 📓 Jupyter notebooks / scripts to run the system


> Note: The official SemEval dataset may not be stored in this repository.  
Please obtain it from the task organizers and place it into the expected folder used by the code.

---

## 🙏 Acknowledgements

- **Sabancı University — CS445: Natural Language Processing**
- **SemEval-2026 / EMNLP** organizers and task authors for the task and dataset resources :contentReference[oaicite:17]{index=17}
