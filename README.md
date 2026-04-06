scratch-to-llm 🤖
Learn AI and Machine Learning from Scratch — Pure Python to Frontier LLM
Python Jupyter License Beginner Friendly Stars

The fastest path from zero to understanding AI. No frameworks, no black boxes — just Python, NumPy, and honest explanations of what is actually happening inside every algorithm.

What Is This?
scratch-to-llm is a beginner-friendly machine learning tutorial built entirely in one Jupyter notebook. You will build five working AI systems from absolute scratch, starting with a 10-line linear model and ending with a live conversation with Claude — a frontier large language model.

Every cell is self-contained. Every algorithm is explained line by line. No prior experience with AI or machine learning required — just Python basics.

Who Is This For?
Complete beginners who want to understand AI, not just use it
Developers who use AI tools but want to know what is happening inside them
Students who need working code alongside the theory
Anyone who has asked "how does a neural network actually learn?" and never got a satisfying answer
What You Will Build
#	Section	What You Build	Core Concept
1	Hello, AI!	Study-hours exam predictor	Supervised learning, prediction
2	Linear Regression	House price model	Gradient descent, loss function
3	Classification	Spam detector	Naive Bayes, word probabilities
4	Neural Network	XOR solver in NumPy	Backpropagation, hidden layers
5	LLM API	Live chat with Claude	Large language models, API calls
Quick Start
# Clone the repository
git clone https://github.com/tarunjaswani/scratch-to-llm.git
cd scratch-to-llm

# Install dependencies (only numpy + matplotlib needed for sections 1-4)
pip install -r requirements.txt

# Open the notebook
jupyter notebook notebooks/intro_walkthrough.ipynb
No Jupyter? Run it instantly in your browser: Open in Colab

What Makes This Different
Most machine learning tutorials give you a framework and tell you to trust it. This one does the opposite.

You will see:

Gradient descent implemented as a 6-line loop — not a model.fit() call
Backpropagation written in NumPy with every derivative shown
Naive Bayes built from a Python dictionary, not a sklearn import
A neural network that solves XOR — with a visualised decision boundary — using zero ML libraries
By the time you reach Section 5 and call the Claude API, you understand what the model you are talking to is built from. That understanding is the point.

Prerequisites
Python 3.9 or higher
Basic Python syntax (variables, loops, functions)
That is it
You do not need to know linear algebra, calculus, or any ML framework before starting. The notebook explains the math as it is needed.

Installation
# Core dependencies (sections 1–4)
pip install numpy matplotlib

# Optional: for the LLM API section
pip install anthropic


Concepts Covered
Machine Learning Fundamentals

What supervised learning actually is
Training data, features, and labels
Overfitting, underfitting, and generalisation
Algorithms (implemented from scratch)

Linear regression with least squares
Gradient descent and learning rate
Naive Bayes classification with Laplace smoothing
Feedforward neural network with backpropagation
ReLU and Sigmoid activation functions
Binary cross-entropy loss
Working with Real AI

How LLM API calls work (no SDK magic)
System prompts and conversation history
Multi-turn chat with memory
Results You Will See
# Section 4 — Neural Network solves XOR
  A     B   Expected   Predicted   Rounded   Correct?
  0     0          0      0.0021         0       ✅
  0     1          1      0.9997         1       ✅
  1     0          1      0.9997         1       ✅
  1     1          0      0.0002         0       ✅

🎉 Perfect score! XOR solved.
Frequently Asked Questions
Do I need a GPU? No. Everything in sections 1–4 runs on CPU in under a minute. Section 5 calls an API so you need an internet connection, not compute.

Can I use this without the API key? Yes. Sections 1–4 are fully self-contained. Section 5 has a built-in demo mode that shows you exactly what the output looks like.

What libraries does this use? Sections 1–3 use zero external libraries — pure Python only. Section 4 uses NumPy. Section 5 uses the urllib standard library (no SDK required).

Is this suitable for a university course? Yes. Each section maps cleanly to a lecture topic. The code is heavily commented and the math is shown step by step.

What Next?
After completing this notebook, these resources are the best next steps:

Resource	Why It Is Good
fast.ai Practical Deep Learning	Best top-down applied DL course, free
Andrej Karpathy — makemore	Build a language model from scratch
PyTorch Tutorials	Industry-standard deep learning framework
3Blue1Brown — Neural Networks	Best visual intuition for how NNs work
Kaggle	Practice on real datasets and competitions
Contributing
Found a bug? Have a clearer explanation for a concept? Pull requests are welcome.

Fork the repository
Create a branch: git checkout -b improve/section-name
Make your changes with clear comments
Open a pull request with a description of what you changed and why
License
MIT — use freely, adapt freely, credit appreciated.

Author
Tarun Jaswani AI Researcher · Machine Learning Engineer
