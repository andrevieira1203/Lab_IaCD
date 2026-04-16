# Lab IaCD : Laboratório de Introdução à IA e Ciência de Dados

## Descrição

Este repositório reúne os trabalhos práticos desenvolvidos no âmbito da cadeira de **Introdução à Inteligência Artificial e Ciência de Dados (IaCD)**. Os projetos cobrem duas grandes áreas: **aprendizagem por reforço** com uma implementação inspirada no AlphaZero, e **classificação médica** com machine learning aplicado ao cancro do pulmão.

---

## Estrutura do Repositório

```
Lab_IaCD/
│
├── AlphaZero/                    # Implementação de agente com aprendizagem por reforço
│   └── ...
│
└── LungCancerClassification/     # Classificação de cancro do pulmão com ML
    └── ...
```

---

## Projetos

### AlphaZero

Implementação de um agente de inteligência artificial inspirado no **AlphaZero** da DeepMind, que combina **Monte Carlo Tree Search (MCTS)** com redes neurais profundas para aprender a jogar jogos de tabuleiro sem conhecimento prévio — apenas através de auto-jogo (*self-play*).

**Conceitos abordados:**
- Aprendizagem por reforço (*Reinforcement Learning*)
- Monte Carlo Tree Search (MCTS)
- Redes neurais convolucionais (CNN) para avaliação de estados
- Self-play e treino iterativo

---

### LungCancerClassification

Projeto de **classificação de cancro do pulmão** utilizando técnicas de machine learning e/ou deep learning. O objetivo é prever o diagnóstico (benigno/maligno) ou o tipo de cancro com base em dados clínicos ou de imagem.

**Conceitos abordados:**
- Pré-processamento e limpeza de dados
- Análise exploratória (EDA)
- Treino e avaliação de modelos de classificação
- Métricas de avaliação: accuracy, precision, recall, F1-score, AUC-ROC

---

## Tecnologias Utilizadas

- **Python 3**
- **Jupyter Notebook**
- Bibliotecas prováveis:
  - `numpy`, `pandas` — manipulação de dados
  - `matplotlib`, `seaborn` — visualização
  - `scikit-learn` — modelos de ML clássicos
  - `tensorflow` / `pytorch` — redes neurais (AlphaZero)
  - `scipy` — análise estatística

---

## Como Executar

1. Clona o repositório:
   ```bash
   git clone https://github.com/andrevieira1203/Lab_IaCD.git
   cd Lab_IaCD
   ```

2. Instala as dependências:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter
   ```

3. Abre o projeto pretendido:
   ```bash
   # Para o AlphaZero
   jupyter notebook AlphaZero/

   # Para a Classificação do Cancro do Pulmão
   jupyter notebook LungCancerClassification/
   ```

---

## Linguagens

| Linguagem | Percentagem |
|---|---|
| Jupyter Notebook | 75.2% |
| Python | 24.8% |

---
