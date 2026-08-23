[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LipeSilva83/modelos-de-regress-o-linear/blob/main/analise_modelos_regressao_portfolio.ipynb)

# modelos-de-regress-o-linear

Este repositório contém notebooks que demonstram análise exploratória e modelagem usando regressão linear. O objetivo desta versão é transformar o trabalho em um artefato de portfólio profissional — reproduzível, documentado e com interpretação clara dos resultados.

Principais arquivos
- `analise_modelos_regressao.ipynb` - notebook original (mantido)
- `analise_modelos_regressao_portfolio.ipynb` - notebook preparado para portfólio (novo)
- `Preços_de_casas.csv` - dataset original (mantido, com acento)
- `Precos_de_casas.csv` - *apelido sem acento* (o notebook tenta criar este arquivo automaticamente a partir do original)
- `requirements.txt` - dependências com versões travadas

Resumo das alterações
- Adicionado notebook voltado a portfólio com: carregamento robusto de dados, limpeza, divisão treino/teste, treinamento de LinearRegression (scikit-learn), avaliação (RMSE, MAE, R²), summary OLS (statsmodels) e visualizações com interpretação.
- Adicionado `requirements.txt` com versões fixas para garantir reprodutibilidade.
- Inserido badge "Open in Colab" para visualização rápida do notebook.

Como rodar (curto)
1) Criar e ativar um virtualenv (opcional):

```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.venv\Scripts\activate    # Windows
```

2) Instalar dependências:

```bash
pip install -r requirements.txt
```

3) Abrir o notebook `analise_modelos_regressao_portfolio.ipynb` com Jupyter Lab/Notebook ou abrir diretamente no Colab usando o badge acima.

Nota sobre o arquivo de dados
- O repositório contém `Preços_de_casas.csv` (com acento). O notebook tenta detectar e criar automaticamente `Precos_de_casas.csv` (sem acento) para evitar problemas de encoding/compatibilidade em alguns ambientes CI/OS. Se preferir, você pode renomeá-lo manualmente.

Próximos passos sugeridos
- Adicionar um resumo executivo no início do README com as principais métricas finais.
- Comparar modelos (Ridge, Lasso, RandomForest) com validação cruzada e tabela sumarizada.
- Exportar um relatório/PDF com os gráficos principais para apresentar no seu portfólio.

Licença
- Considere adicionar uma licença (ex.: MIT) se pretende compartilhar publicamente.
