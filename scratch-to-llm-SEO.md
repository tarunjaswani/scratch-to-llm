# ═══════════════════════════════════════════════════════
# GITHUB REPO DESCRIPTION  (paste into the About field)
# ─ Under 350 characters ─ Primary keyword first ─
# ═══════════════════════════════════════════════════════

DESCRIPTION:
"Learn AI and machine learning from scratch with Python — pure math to neural networks to LLM API in one Jupyter notebook. No frameworks, no black boxes. Built for absolute beginners. ⚡"

CHARACTER COUNT: 188 ✅  (limit is 350)


# ═══════════════════════════════════════════════════════
# GITHUB TOPICS  (paste all 20 into the Topics field)
# ─ Mix: broad + specific + long-tail ─
# ═══════════════════════════════════════════════════════

TOPICS (copy each one):
machine-learning
deep-learning
artificial-intelligence
python
neural-network
jupyter-notebook
beginner-friendly
gradient-descent
numpy
llm
ai-tutorial
learn-ai
backpropagation
classification
linear-regression
naive-bayes
llm-api
claude-api
ai-for-beginners
data-science


# ═══════════════════════════════════════════════════════
# README.md  (full SEO-optimised version)
# ═══════════════════════════════════════════════════════

---

# scratch-to-llm 🤖
### Learn AI and Machine Learning from Scratch — Pure Python to Frontier LLM

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Beginner Friendly](https://img.shields.io/badge/Level-Beginner%20Friendly-brightgreen)]()
[![Stars](https://img.shields.io/github/stars/tarunjaswani/scratch-to-llm?style=social)]()

> **The fastest path from zero to understanding AI.** No frameworks, no black boxes — just Python, NumPy, and honest explanations of what is actually happening inside every algorithm.

---

## What Is This?

**scratch-to-llm** is a beginner-friendly machine learning tutorial built entirely in one Jupyter notebook. You will build five working AI systems from absolute scratch, starting with a 10-line linear model and ending with a live conversation with Claude — a frontier large language model.

Every cell is self-contained. Every algorithm is explained line by line. No prior experience with AI or machine learning required — just Python basics.

---

## Who Is This For?

- **Complete beginners** who want to understand AI, not just use it
- **Developers** who use AI tools but want to know what is happening inside them
- **Students** who need working code alongside the theory
- **Anyone** who has asked *"how does a neural network actually learn?"* and never got a satisfying answer

---

## What You Will Build

| # | Section | What You Build | Core Concept |
|---|---------|---------------|--------------|
| 1 | Hello, AI! | Study-hours exam predictor | Supervised learning, prediction |
| 2 | Linear Regression | House price model | Gradient descent, loss function |
| 3 | Classification | Spam detector | Naive Bayes, word probabilities |
| 4 | Neural Network | XOR solver in NumPy | Backpropagation, hidden layers |
| 5 | LLM API | Live chat with Claude | Large language models, API calls |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/tarunjaswani/scratch-to-llm.git
cd scratch-to-llm

# Install dependencies (only numpy + matplotlib needed for sections 1-4)
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/intro_walkthrough.ipynb
```

> **No Jupyter?** Run it instantly in your browser:
> [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarunjaswani/scratch-to-llm/blob/main/notebooks/intro_walkthrough.ipynb)

---

## What Makes This Different

Most machine learning tutorials give you a framework and tell you to trust it. This one does the opposite.

**You will see:**
- Gradient descent implemented as a 6-line loop — not a `model.fit()` call
- Backpropagation written in NumPy with every derivative shown
- Naive Bayes built from a Python dictionary, not a sklearn import
- A neural network that solves XOR — with a visualised decision boundary — using zero ML libraries

By the time you reach Section 5 and call the Claude API, you understand what the model you are talking to is built from. That understanding is the point.

---

## Prerequisites

- Python 3.9 or higher
- Basic Python syntax (variables, loops, functions)
- That is it

You do not need to know linear algebra, calculus, or any ML framework before starting. The notebook explains the math as it is needed.

---

## Installation

```bash
# Core dependencies (sections 1–4)
pip install numpy matplotlib

# Optional: for the LLM API section
pip install anthropic

# Full install
pip install -r requirements.txt
```

**For Section 5 (LLM API):** Get a free API key at [console.anthropic.com](https://console.anthropic.com). The notebook runs in demo mode without one — you can see what the output looks like before signing up.

---

## Repository Structure

```
scratch-to-llm/
│
├── notebooks/
│   └── intro_walkthrough.ipynb   ← The main notebook (start here)
│
├── examples/                     ← Standalone .py scripts per section
│   ├── 01_hello_ai.py
│   ├── 02_linear_regression.py
│   ├── 03_classification.py
│   ├── 04_neural_network.py
│   └── 05_llm_api.py
│
├── utils/
│   └── helpers.py                ← Shared utilities
│
├── requirements.txt
└── README.md
```

---

## Concepts Covered

**Machine Learning Fundamentals**
- What supervised learning actually is
- Training data, features, and labels
- Overfitting, underfitting, and generalisation

**Algorithms (implemented from scratch)**
- Linear regression with least squares
- Gradient descent and learning rate
- Naive Bayes classification with Laplace smoothing
- Feedforward neural network with backpropagation
- ReLU and Sigmoid activation functions
- Binary cross-entropy loss

**Working with Real AI**
- How LLM API calls work (no SDK magic)
- System prompts and conversation history
- Multi-turn chat with memory

---

## Results You Will See

```
# Section 4 — Neural Network solves XOR
  A     B   Expected   Predicted   Rounded   Correct?
  0     0          0      0.0021         0       ✅
  0     1          1      0.9997         1       ✅
  1     0          1      0.9997         1       ✅
  1     1          0      0.0002         0       ✅

🎉 Perfect score! XOR solved.
```

---

## Frequently Asked Questions

**Do I need a GPU?**
No. Everything in sections 1–4 runs on CPU in under a minute. Section 5 calls an API so you need an internet connection, not compute.

**Can I use this without the API key?**
Yes. Sections 1–4 are fully self-contained. Section 5 has a built-in demo mode that shows you exactly what the output looks like.

**What libraries does this use?**
Sections 1–3 use zero external libraries — pure Python only. Section 4 uses NumPy. Section 5 uses the `urllib` standard library (no SDK required).

**Is this suitable for a university course?**
Yes. Each section maps cleanly to a lecture topic. The code is heavily commented and the math is shown step by step.

---

## What Next?

After completing this notebook, these resources are the best next steps:

| Resource | Why It Is Good |
|----------|---------------|
| [fast.ai Practical Deep Learning](https://course.fast.ai) | Best top-down applied DL course, free |
| [Andrej Karpathy — makemore](https://github.com/karpathy/makemore) | Build a language model from scratch |
| [PyTorch Tutorials](https://pytorch.org/tutorials) | Industry-standard deep learning framework |
| [3Blue1Brown — Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk) | Best visual intuition for how NNs work |
| [Kaggle](https://kaggle.com) | Practice on real datasets and competitions |

---

## Contributing

Found a bug? Have a clearer explanation for a concept? Pull requests are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b improve/section-name`
3. Make your changes with clear comments
4. Open a pull request with a description of what you changed and why

---

## License

MIT — use freely, adapt freely, credit appreciated.

---

## Author

**Tarun Jaswani**
AI Researcher · Machine Learning Engineer · Cybersecurity Consultant

[Medium](https://medium.com/@tarunjaswani) · [LinkedIn](https://linkedin.com/in/tarunjaswani)

*If this notebook helped you understand AI better, a ⭐ on GitHub means a lot and helps others find it.*

---

*Keywords: machine learning tutorial python, learn ai from scratch, neural network numpy tutorial, deep learning beginner, gradient descent python, backpropagation tutorial, AI jupyter notebook, LLM API python, Claude API tutorial, artificial intelligence for beginners*
