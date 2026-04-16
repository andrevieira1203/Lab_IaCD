# Lab IaCD : Introduction to AI and Data Science

## Description

This repository contains the practical work developed for the course **Introduction to Artificial Intelligence and Data Science (IaCD)**. The projects cover two main areas: **reinforcement learning** with an AlphaZero-inspired implementation, and **medical classification** with machine learning applied to lung cancer detection.

---

## Repository Structure

```
Lab_IaCD/
│
├── AlphaZero/                    # Reinforcement learning agent implementation
│   └── ...
│
└── LungCancerClassification/     # Lung cancer classification with ML
    └── ...
```

---

## Projects

### AlphaZero

Implementation of an AI agent inspired by **DeepMind's AlphaZero**, combining **Monte Carlo Tree Search (MCTS)** with deep neural networks to learn to play board games from scratch — purely through self-play, with no prior domain knowledge.

**Key concepts:**
- Reinforcement Learning
- Monte Carlo Tree Search (MCTS)
- Convolutional Neural Networks (CNN) for state evaluation
- Self-play and iterative training

---

### LungCancerClassification

A **lung cancer classification** project using machine learning and/or deep learning techniques. The goal is to predict the diagnosis (benign/malignant) or cancer type based on clinical or imaging data.

**Key concepts:**
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Training and evaluation of classification models
- Evaluation metrics: accuracy, precision, recall, F1-score, AUC-ROC

---

## Technologies & Libraries

- **Python 3**
- **Jupyter Notebook**
- Likely libraries:
  - `numpy`, `pandas` — data manipulation
  - `matplotlib`, `seaborn` — visualization
  - `scikit-learn` — classical ML models
  - `tensorflow` / `pytorch` — neural networks (AlphaZero)
  - `scipy` — statistical analysis

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/andrevieira1203/Lab_IaCD.git
   cd Lab_IaCD
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
   ```

3. Open the desired project:
   ```bash
   # AlphaZero
   jupyter notebook AlphaZero/

   # Lung Cancer Classification
   jupyter notebook LungCancerClassification/
   ```

---

## Languages

| Language | Percentage |
|---|---|
| Jupyter Notebook | 75.2% |
| Python | 24.8% |

---
