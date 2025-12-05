Projeto de Machine Learning — Predição de Visualizações do YouTube
Disciplina: Machine Learning
Professor: Durval Lins de Siqueira Neto
Período: 4º Período, Sala C

Integrantes:
Arthur Moraes Barbosa Silva – 01714787
João Álison Araujo de Moura – 01762578
José Gabriel Ferreira Alves – 01700051

Dataset utilizado: youtube_views.csv
Repositório do projeto: [https://github.com/Alvesz4/Machine-Learning](https://github.com/Alvesz4/Machine-Learning)

Objetivo do Projeto
Este projeto teve como objetivo desenvolver um modelo de Machine Learning capaz de prever a quantidade de visualizações de vídeos no YouTube utilizando variáveis presentes no dataset youtube_views.csv, como categoria, título, duração, engajamento e outras características do vídeo.
O repositório contém todas as etapas do pipeline completas: análise exploratória dos dados (EDA), pré-processamento, modelagem, otimização, avaliação final e geração do relatório técnico.

Estrutura do Repositório
.
├── README.md                     Descrição do projeto
├── data/
│   ├── raw/                      Dados originais
│   └── processed/                Dados tratados
├── notebooks/
│   ├── 01_EDA.ipynb              Análise exploratória
│   ├── 02_Preprocessamento.ipynb Preparação dos dados
│   ├── 03_Modelagem.ipynb        Treinamento dos modelos
│   └── 04_Otimizacao.ipynb       Ajuste de hiperparâmetros
├── models/
│   └── modelo_final.joblib       Modelo final treinado
├── docs/
│   └── RELATORIO_FINAL.md        Relatório final completo
└── requirements.txt              Dependências do projeto

Tecnologias Utilizadas
Python 3.10 ou superior
Pandas
NumPy
Scikit-learn
Matplotlib e Seaborn
Joblib
Jupyter Notebook

Como Executar o Projeto

1. Clonar o repositório:
   git clone [https://github.com/Alvesz4/Machine-Learning](https://github.com/Alvesz4/Machine-Learning)
   cd Machine-Learning

2. Instalar as dependências:
   pip install -r requirements.txt

3. Executar os notebooks:
   jupyter notebook notebooks/

4. Executar os arquivos na seguinte ordem:
   01_EDA.ipynb
   02_Preprocessamento.ipynb
   03_Modelagem.ipynb
   04_Otimizacao.ipynb

Resultado Final
O modelo que apresentou melhor desempenho foi o Random Forest Regressor otimizado utilizando RandomizedSearchCV.