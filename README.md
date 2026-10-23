# Previsão de Sobrevivência no Titanic — Machine Learning

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

Este projeto implementa um modelo de **Árvore de Decisão** (`DecisionTreeClassifier`) em Python para prever quais passageiros teriam probabilidade de sobreviver ao naufrágio do Titanic, utilizando o famoso dataset do Kaggle/DataScienceDojo.

## Funcionalidades
- **Análise Exploratória de Dados (EDA):** Carregamento, limpeza e visualização estatística dos dados.
- **Tratamento de Dados:** Tratamento de valores ausentes (missing values) com medianas e mapeamento de variáveis categóricas para numéricas (`Sex`, `Pclass`, `Age`, `Fare`, etc.).
- **Engenharia de Recursos:** Seleção de *features* preditoras relevantes para o modelo.
- **Divisão de Dados:** Separação do dataset em conjuntos de treinamento (70%) e teste (30%) de forma estratificada.
- **Treinamento e Visualização:** Treinamento do classificador de Árvore de Decisão com limitação de profundidade (`max_depth`) para evitar *overfitting* e plotagem gráfica da árvore gerada.

## Tecnologias Utilizadas
- **Python** (Linguagem principal)
- **Pandas & NumPy** (Manipulação e estruturação de dados)
- **Matplotlib & Seaborn** (Visualização de dados e gráficos estatísticos)
- **Scikit-Learn** (Construção do modelo de Machine Learning e métricas)

## Estrutura do Repositório

```text
classificacao-titanic-python/
├── dataset/                 # Dados utilizados (carregados via API/URL)
├── titanic_model.py         # Código principal do modelo e EDA
└── README.md                # Documentação do projeto
