[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LipeSilva83/modelos-de-regress-o-linear/blob/main/analise_modelos_regressao_portfolio.ipynb)

# modelos-de-regress-o-linear

# :computer: Projeto de Previsão de Preços de Imóveis com Regressão Linear e Ensembles
Este projeto de machine learning tem como objetivo analisar características estruturais de imóveis (como área, número de banheiros, qualidade da cozinha e capacidade da garagem) para construir e comparar modelos de regressão capazes de realizar previsões precisas de preços de venda.

# ⚙️ Tecnologias Utilizadas ⚙️
O projeto foi desenvolvido inteiramente em Python, aproveitando o ecossistema de bibliotecas de Data Science e Machine Learning para a manipulação, visualização de dados e construção dos modelos.

Linguagem de Programação: Python 
<img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/python.png" alt="Python" width="30" height="50"/>

Bibliotecas: 

Pandas: <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/pandas.png" alt="Pandas" width="30" height="50"/>

NumPy: <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/numpy.png" alt="NumPy" width="30" height="50"/> 

Scikit-learn: <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/scikit_learn.png" alt="Scikit-learn" width="50" height="50"/>

Matplotlib: <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/matplotlib.png" alt="Matplotlib" width="40" height="60"/>

Seaborn: <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Logo-seaborn.png" alt="Seaborn" width="40" height="60"/>

# 🎯 Objetivo do Projeto 

🧠 Algoritmos Implementados
O cerne deste projeto é a aplicação de Análise Exploratória de Dados (EDA) e a comparação de múltiplos modelos preditivos otimizados via validação cruzada (`GridSearchCV`).

Linear Regression: Modelo baseline linear supervisionado para estabelecer a métrica inicial de desempenho.

Ridge & Lasso Regression: Modelos lineares com regularização L2 e L1 para evitar overfitting e selecionar atributos relevantes.

Random Forest Regressor: Algoritmo baseado em árvores de decisão aleatórias para capturar relações não lineares e complexas nos dados.

# 📊 Resultados e Análise
Os modelos foram avaliados e comparados utilizando validação cruzada (`GridSearchCV`) com base em métricas de desempenho para regressão. Os resultados completos das métricas foram salvos no arquivo `models_comparison.csv` e as previsões no `predicoes_test.csv`.

A inclusão do algoritmo Random Forest Regressor e o ajuste fino de hiperparâmetros permitiram capturar melhor as nuances do dataset, superando a regressão linear simples em precisão.

# 🚀 Como Rodar o Projeto
Para replicar a análise e os modelos localmente, siga os passos abaixo.

📢 Você pode rodar a análise diretamente no Google Colab ou abrir o notebook localmente:
1. Certifique-se de instalar as dependências com `pip install -r requirements.txt`.
2. Execute o notebook de portfólio (`analise_modelos_regressao_portfolio.ipynb`) para visualizar o pipeline e a EDA.
3. Execute o notebook de comparação (`compare_models_cv.ipynb`) para rodar a validação cruzada e gerar as métricas finais.

# ✒️ Autor
[Filipe Silva] - [https://github.com/LipeSilva83]
