# CSE425 Neural Networks

![Course](https://img.shields.io/badge/Course-CSE425-0d1117?style=flat-square&labelColor=0d1117&color=238636)
![Semester](https://img.shields.io/badge/Semester-Summer%202026-0d1117?style=flat-square&labelColor=0d1117&color=1f6feb)
![Institution](https://img.shields.io/badge/Institution-BRAC%20University-0d1117?style=flat-square&labelColor=0d1117&color=8957e5)
![Language](https://img.shields.io/badge/Language-Python-0d1117?style=flat-square&labelColor=0d1117&color=3178c6)
![Format](https://img.shields.io/badge/Format-PDF%20%7C%20LaTeX-0d1117?style=flat-square&labelColor=0d1117&color=f97316)

---

## Overview

Course materials, lecture notes, assignments, and practice problems for **CSE425: Neural Networks** [Summer 2026] at BRAC University. The course builds from foundational perceptron theory through backpropagation, recurrent and convolutional architectures, unsupervised learning, and modern attention-based models. This repository contains structured lecture notes from multiple instructors, curated reference slides, three graded assignments, quiz papers, practice problem sets, a paper review, and a project specification with supplementary implementation guide.

---

## Course Topics

The lecture note set spans 11 numbered modules, organized across mid and final halves of the semester:

| Module | Topic |
|--------|-------|
| 0 | Introduction to Neural Networks, Activation Functions, Loss Functions |
| 1 | Perceptron, Perceptron Learning Algorithm, XOR Problem |
| 2 | Multilayer Perceptron (MLP), Backpropagation — Derivation, Delta Rule, Scalar vs Matrix |
| 3 | Boolean Function Approximation with MLPs |
| 4 | Computation Graphs — Forward/Backward pass, 20-example problem sets, Class notes |
| 5 | Recurrent Neural Networks (RNN) — Equations, BPTT, Variants (LSTM, GRU) |
| 6 | NN Training — Overfitting, Bias-Variance, Regularization (L1/L2, Dropout), Batch Normalization, Optimization |
| 7 | Unsupervised Learning — Autoencoders (AE), Variational Autoencoders (VAE), LSTM-AE, Kohonen Neural Networks, K-Means |
| 8 | Convolutional Neural Networks (CNN) — Intro, Depthwise Separable Convolution, Backpropagation, Modern Architectures |
| 9 | Attention Mechanisms and Transformer — Positional Encoding, Masked Attention, Cross-Attention |
| 10 | Graph Neural Networks (GNN) |

---

## Assignments

| Assignment | Submission File | Description |
|------------|----------------|-------------|
| A1 & A2 | `24101406_1.pdf`, `24101406_2.pdf` | Neural network theory and problem-solving assignments |
| A3 | `24101406_3.pdf` | Written assignment with supporting figures (`A3.1.png`, `A3.2.png`) |

---

## Assessments

### Quizzes (Current Semester)

| Quiz | Instructor | Files |
|------|-----------|-------|
| Quiz 1 | MMM | Question image |
| Quiz 2 | MMM | Question + two solution documents |
| Computational Graph Quiz | — | Question image |
| Batch Normalization Quiz | — | Question image |
| Quiz 1 & 2 | RRH | Combined PDF |

### Practice Problem Sets

| Scope | Problems |
|-------|----------|
| Mid | Computation Graph (Basic & 20-example sets), XOR Problem Solution, Practice Sheets (MMM, RRH, Combined-100) |
| Final | CNN Math Problems, CNN Backprop Matrix, Attention & Transformer Math Problems, AE/VAE/LSTM Math Problems, Transformer PS, VAE Autoencoder |

### Past Quiz Papers (Reference)

- Fall 2025: Quiz 03, Quiz 04, Quiz Make-Up
- Spring 2026: Quiz 01, Quiz 03, Quiz 04, Quiz 05 / Make-Up 06

---

## Paper Writing

| File | Description |
|------|-------------|
| `Paper.pdf` | Reference research paper |
| `24101406_04_Paper Review.pdf` | Student paper review submission |

---

## Project

Project documentation for the Spring 2026 offering (foundational reference):

| File | Description |
|------|-------------|
| `Spring26 Project Details of Neural Network.pdf` | Full project specification and requirements |
| `Spring26 project Supplementary Implementation Guide.pdf` | Step-by-step implementation guidance |

---

## Reference Books

| Book | Author(s) |
|------|-----------|
| Neural Network Design | Martin T. Hagan |
| Neural Networks: A Comprehensive Foundation | Simon S. Haykin |
| Neural Networks and Deep Learning | Michael Nielsen |
| Neural Networks from Scratch in Python | Harrison Kinsley, Daniel Kukieła |
| The Deep Learning Book | Ian Goodfellow, Yoshua Bengio |
| Understanding Deep Learning | Simon J.D. Prince |

---

## Hand Notes

| File | Topic |
|------|-------|
| `AE, VAE, KL Divergence.pdf` | Handwritten notes on Autoencoders, VAE, and KL Divergence |
| `CNN.pdf` | Handwritten CNN notes |
| `Transformers, Word Embedding, Attention.pdf` | Handwritten notes on Attention and Transformers |
| `LSTM.png` | LSTM architecture diagram |
| `CSE425.pdf` | General course hand notes |

---

## Repository Structure

```
CSE425/
│
├── Assignment/
│   ├── 24101406_1.pdf                   # Assignment 1 submission
│   ├── 24101406_2.pdf                   # Assignment 2 submission
│   ├── 24101406_3.pdf                   # Assignment 3 submission
│   ├── A1 & A2.jpg                      # Assignment 1 & 2 question sheet
│   ├── A3.1.png                         # Assignment 3 supporting figure
│   └── A3.2.png
│
├── Lecture Notes/
│   ├── 01.x  Perceptron & Fundamentals
│   ├── 02.x  Activation Functions, Loss Functions
│   ├── 03.x  MLP Backpropagation (Intro, Derivation, Delta, Scalar vs Matrix)
│   ├── 04.x  Boolean Functions
│   ├── 05.x  Computation Graphs (Slides, Class Notes, 20 Examples)
│   ├── 06.x  RNN — Equations, BPTT, Variants
│   ├── 07.x  NN Training — Overfitting, Regularization, Batch Norm, Optimization
│   ├── 08.x  Unsupervised Learning — AE, VAE, LSTM-AE, KL Divergence, Kohonen NN
│   ├── 09.x  CNN — Intro, Depthwise, Stanford Slides, Backprop, Modern Architectures
│   ├── 10.x  Attention & Transformer — Positional Encoding, Masked/Cross-Attention
│   ├── 11.x  Graph Neural Networks (GNN)
│   └── Lecture PDF [RRH]/              # Instructor RRH's lecture note set (40 files)
│
├── Slides/
│   ├── Mid/                            # Mid-semester slide set (40 files)
│   └── Final/                          # Final-semester slide set (24 files)
│   └── Extra/                          # Supplementary slides (18 files)
│
├── Questions/
│   ├── Practice Sheet/                 # Mid and final practice problem sets (16 files)
│   ├── Quiz/                           # Current semester quiz papers & solutions (7 files)
│   └── Quiz [Past]/                    # Fall 2025 and Spring 2026 past quizzes (7 files)
│
├── Books/                              # Six reference textbooks (PDF)
│
├── Hand Notes/                         # Handwritten notes (PDF, PNG)
│
├── Paper Writing/
│   ├── Paper.pdf                       # Reference paper
│   └── 24101406_04_Paper Review.pdf    # Student paper review
│
├── Project Details/
│   ├── Spring26 Project Details of Neural Network.pdf
│   └── Spring26 project Supplementary Implementation Guide.pdf
│
├── Course Content.pdf
├── Course Outline.pdf
├── Discussion.pdf
├── Spring2026 Lecture Plan.pdf
└── README.md
```

---

## Technologies

- **Language:** Python 3
- **Primary Format:** PDF (lecture notes, slides, problem sets, assignments)
- **Slide Formats:** PDF, PPTX
- **Note Formats:** PDF, PNG (handwritten and typed)

---