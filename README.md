<h1 align="center">AI Learning Journey 🚀</h1>

<p align="center">
  <i>From <code>print("Hello, World")</code> to systems that see, read, reason, and answer.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Phase-1%20Foundations-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.9+-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/Learning-In%20Public-orange?style=for-the-badge" />
</p>

---

## 🧭 The Story

I come from the **SAP / ERP world**, where I write ABAP and support business systems that real companies depend on every day.
On the side, I built an **AI referee** that decides *"goal or no goal"* using **CNN + YOLO**.

That project taught me something uncomfortable: **I could make a model work without fully understanding why it worked.**

This repo is my answer to that. I'm rebuilding my foundation from the ground up, so that every model I touch from now on is something I can explain, debug, and improve, not just run.

> **I don't know Transformers yet. I don't know how RAG really works yet. This repo is where that changes, in public.**

---

## 🎯 The Mission

By the end of this journey I want to be able to build, from scratch and explain line by line:

- 👁️ **A vision system**: CNN-based image recognition
- 📖 **An NLP pipeline**: tokenization → embeddings → Transformers
- 🧠 **An LLM application**: prompting, fine-tuning, evaluation
- 🔎 **A RAG system**: an assistant that answers questions over my own documents (and, eventually, ERP documentation 👀)

---

## 🗺️ The Road Ahead

| Phase | What I'll learn | What I'll build | Status |
|-------|-----------------|-----------------|--------|
| 🟢 **1. Foundations** | Python, NumPy, Pandas, Matplotlib | Data cleaning + visualization mini-projects | 🔨 In progress |
| 🔵 **2. Machine Learning** | Regression, classification, overfitting, evaluation metrics | A model I train and evaluate end-to-end | ⬜ Next |
| 🟣 **3. Deep Learning** | Backprop, optimizers, PyTorch, **CNNs** | An image classifier, then rebuild my referee properly | ⬜ Planned |
| 🟠 **4. NLP** | Tokenization, embeddings, attention, **Transformers** | A text classifier and a tiny Transformer | ⬜ Planned |
| 🔴 **5. LLMs & RAG** | Prompting, fine-tuning, vector databases, **RAG** | A chatbot over my own documents | ⬜ Planned |
| ⚫ **6. Capstone** | Deployment, evaluation, monitoring | An end-to-end AI app, live | ⬜ Dream big |

---

## 🧠 Phase 1, Week 1: Python Fundamentals

**What I practiced:**

| Concept | Details |
|---------|---------|
| Variables & types | `int`, `float`, `str`, `isinstance()` |
| Conversion | `int()`, `float()` |
| Validation | `assert` to test my own answers |
| Loops | `for`, `range()`, `enumerate()`, `zip()`, nested loops for 2D data |
| Lists | `append`, comprehensions, `sum`, `len`, `min`, `max` |
| Functions | parameters, return values, docstrings |
| Debugging | breakpoints, stepping, watching variables in VS Code |

### 🔬 ML exercises (the reason Python matters)

I didn't just learn syntax. I wrote the building blocks that ML libraries hide:

- **Classification accuracy** from predictions vs. true labels
- **Column means** of a small dataset
- **Min-max normalization**, scaling features into [0, 1]:

```
x_normalized = (x - min) / (max - min)
```

### 💭 What I learned

- Normalization looks trivial, but it is the first thing that makes models train properly.
- Writing `assert` before trusting my code caught mistakes I would have missed.
- Debugging line by line taught me more than reading solutions.

---

## 🧪 How I Learn (My Rules)

1. **Understand before I import.** Implement the idea by hand first, then use the library.
2. **Break things on purpose.** Change inputs, remove lines, see what fails.
3. **Commit every session.** Small, honest progress beats big, rare progress.
4. **Write what I learned.** If I can't explain it simply, I haven't learned it.
5. **Ship small projects.** Every phase ends with something that runs.

---

## 📁 Repository Structure

```
.
├── week1_python_fundamentals.ipynb   # Week 1 exercises and solutions
├── new.py                            # Debugging practice
└── README.md
```

---

## 🚀 Run It Yourself

```bash
git clone https://github.com/Abdelrahman-mostafa-s4/ai-learning-journey.git
cd ai-learning-journey
pip install notebook
jupyter notebook
```

Or open the notebook directly in **Google Colab**. No setup needed.

---

## 🛠️ Tools

Python · Jupyter / Google Colab · VS Code · Git & GitHub
*(PyTorch, TensorFlow, and more will be added as I reach them.)*

---

## 🤝 Learn With Me

If you're also starting out, or you're further along and see something I'm doing wrong:

- ⭐ **Star** the repo to follow the journey
- 🐛 **Open an issue** if you spot a mistake. I genuinely want to be corrected
- 💬 **Connect with me** on LinkedIn

---

## 👤 Author

**Abdelrahman Mostafa**, SAP ABAP developer learning to build AI.

[![GitHub](https://img.shields.io/badge/GitHub-Abdelrahman--mostafa--s4-181717?style=flat&logo=github)](https://github.com/Abdelrahman-mostafa-s4)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdelrahman%20Mostafa-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelrahman-mostafa-55a540249/)

<p align="center"><i>Day 1 of many. Let's see how far this goes. ⚡</i></p>
