[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LipeSilva83/modelos-de-regress-o-linear/blob/main/analise_modelos_regressao_portfolio.ipynb)

# modelos-de-regress-o-linear

## Resumo Executivo
Este repositório apresenta uma análise comparativa de modelos de regressão para prever o preço de venda de imóveis a partir de características estruturais (área do primeiro andar, existência de segundo andar, área do segundo andar, número de banheiros, capacidade da garagem, qualidade da cozinha, etc.).

- Objetivo: demonstrar EDA, limpeza de dados, modelagem linear e comparação entre modelos com validação cruzada.\n
- O notebook principal de portfólio (`analise_modelos_regressao_portfolio.ipynb`) mostra um pipeline reprodutível com LinearRegression. A branch de comparação adiciona `compare_models_cv.ipynb` que executa GridSearchCV para Ridge, Lasso e RandomForest, salvando os resultados em `models_comparison.csv` e as previsões de teste em `predicoes_test.csv`.

- Conclusão (sintética): o repositório fornece ferramentas para reproduzir rapidamente a comparação; execute `compare_models_cv.ipynb` para gerar métricas finais e tabelas resumidas e consulte o PR associado para detalhes dos hyperparâmetros testados.

---

Este repositório contém notebooks que demonstram análise exploratória e modelagem usando regressão linear. O objetivo desta versão é transformar o trabalho em um artefato de portfólio profissional — reproduzível, documentado e com interpretação clara dos resultados.

Principais arquivos
- `analise_modelos_regressao.ipynb` - notebook original (mantido)
- `analise_modelos_regressao_portfolio.ipynb` - notebook preparado para portfólio (novo)
- `Preços_de_casas.csv` - dataset original (mantido, com acento)
- `Precos_de_casas.csv` - *apelido sem acento* (o notebook tenta criar este arquivo automaticamente a partir do original)
- `requirements.txt` - dependências com versões travadas

