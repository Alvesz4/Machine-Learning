#  Projeto de Machine Learning 

**Disciplina:** Machine Learning
**Professor:** Durval Lins de Siqueira Neto
**Período:** 4º Período --- Sala C

### 👥 Integrantes do Grupo

-   **Arthur Moraes Barbosa Silva** -- 01714787
-   **João Álison Araujo de Moura** -- 01762578
-   **José Gabriel Ferreira Alves** -- 01700051

## 📌 Objetivo do Projeto

Este projeto tem como finalidade desenvolver um modelo de **Machine
Learning capaz de prever a quantidade de visualizações de vídeos do
YouTube**, utilizando variáveis como categoria, título, duração,
engajamento e outras características do vídeo.

O repositório contém todas as etapas do pipeline completas: - Análise
exploratória (EDA)
- Pré-processamento
- Treinamento de modelos
- Otimização de hiperparâmetros
- Avaliação final
- Relatório técnico

## 📂 Estrutura do Repositório

    ├── README.md
    ├── data/
    │   ├── raw/
    │   └── processed/
    ├── notebooks/
    │   ├── 01_EDA.ipynb
    │   ├── 02_Preprocessamento.ipynb
    │   ├── 03_Modelagem.ipynb
    │   └── 04_Otimizacao.ipynb
    ├── models/
    │   └── modelo_final.joblib
    ├── docs/
    │   └── RELATORIO_FINAL.md
    └── requirements.txt

## 🧪 Tecnologias Utilizadas

-   Python 3.10+
-   Pandas
-   NumPy
-   Scikit-learn
-   Matplotlib
-   Seaborn
-   Joblib
-   Jupyter Notebook

## 🚀 Como Executar

### 1️⃣ Clonar o repositório

    git clone https://github.com/Alvesz4/Machine-Learning
    cd Machine-Learning

### 2️⃣ Instalar dependências

    pip install -r requirements.txt

### 3️⃣ Executar notebooks

    jupyter notebook notebooks/

### 4️⃣ Ordem de execução

1.  01_EDA.ipynb
2.  02_Preprocessamento.ipynb
3.  03_Modelagem.ipynb
4.  04_Otimizacao.ipynb

## 🏆 Resultado Final

O modelo com melhor desempenho foi o **Random Forest Regressor**
otimizado com **RandomizedSearchCV**.

## 📎 Repositório

https://github.com/Alvesz4/Machine-Learning
