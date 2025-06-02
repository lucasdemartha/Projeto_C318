# 🧠 Predição de Vitórias no League of Legends com Machine Learning

Este projeto aplica técnicas de **análise de dados** e **modelos de aprendizado supervisionado** para prever a vitória do time azul em partidas ranqueadas de League of Legends, com base nas estatísticas acumuladas até os **10 primeiros minutos de jogo**.

---

## 🎯 Objetivo

> Descobrir se é possível prever o resultado de uma partida apenas com informações dos 10 primeiros minutos.

---

## 📊 Etapas do Projeto

### 1. **Análise Exploratória (EDA)**
- Distribuição das principais métricas (ouro, XP, kills)
- Correlação entre variáveis
- Boxplots comparando times vencedores e perdedores

### 2. **Engenharia de Features**
- Criação de novas variáveis como:
  - `blueGoldPerKill`
  - `blueAssistRate`
  - `blueEfficiency`

### 3. **Modelos de Machine Learning**
- Árvore de Decisão (DecisionTreeClassifier)
- Random Forest (com análise de importância e Curva ROC)
- Comparação entre os modelos

### 4. **Visualizações**
- Árvore de decisão interpretável
- Fluxograma simplificado
- Gráficos de importância de variáveis

---

## 🧠 Principais Descobertas

- A **diferença de ouro (blueGoldDiff)** é a variável mais impactante.
- Com apenas 10 minutos de dados, o modelo atinge:
  - **Árvore de Decisão**: ~72% de acurácia
  - **Random Forest**: ~75% de acurácia
- Variáveis como XP, abates e objetivos também influenciam fortemente.

---

## 🗂️ Estrutura do Projeto

```
📁 Projeto
│
├── 📄 lol_10min_predicao.ipynb
├── 📊 images/
├── 📄 requirements.txt
└── 📘 README.md
```

---

## ▶️ Como Rodar

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Execute o notebook:
```bash
jupyter notebook lol_10min_predicao.ipynb
```

---

## 🛠️ Tecnologias Usadas

- Python 3.11
- Pandas, Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📌 Dataset

- Kaggle: [League of Legends Diamond Ranked Games (10 min)](https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min)

---

## 👨‍💻 Autores

- [Lucas de Martha](https://github.com/lucasdemartha)
- [Nicholas Siecola](https://github.com/NSiecola)

