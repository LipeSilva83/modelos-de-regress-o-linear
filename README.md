# modelos-de-regress-o-linear

Este projeto contém um notebook de exemplo para análise e comparação de modelos de regressão linear aplicados a um conjunto de dados tabulares. O objetivo aqui é transformar este repositório em um artefato de portfólio profissional: instrutivo, reproduzível e com interpretações claras dos resultados.

Principais arquivos
- analise_modelos_regressao.ipynb  - notebook original (mantido)
- analise_modelos_regressao_portfolio.ipynb - notebook preparado para portfólio (novo)
- Preços_de_casas.csv             - dataset fornecido

O que acrescentei
- README mais completo (este arquivo).
- requirements.txt com dependências usadas no notebook de portfólio.
- notebook de portfólio (analise_modelos_regressao_portfolio.ipynb) que:
  - carrega o dataset Preços_de_casas.csv
  - faz limpeza e engenharia básica de features
  - divide em treino/teste
  - treina um LinearRegression (scikit-learn) e apresenta métricas: RMSE, MAE, R²
  - mostra um summary de OLS via statsmodels para interpretação estatística
  - inclui visualizações (predito x real, resíduos) e células de interpretação

Como executar (passo-a-passo curto)
1) Criar e ativar um ambiente virtual (opcional mas recomendado):

```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
.venv\Scripts\activate    # Windows
```

2) Instalar dependências:

```bash
pip install -r requirements.txt
```

3) Abrir o notebook:

```bash
jupyter lab
# abrir analise_modelos_regressao_portfolio.ipynb
```

Observações importantes
- O notebook novo lê o arquivo `Preços_de_casas.csv` que está no repositório. Garanta que o nome do arquivo permaneça exatamente com o acento (ou ajuste o caminho no notebook).
- Mantive o notebook original sem modificações — assim você preserva sua versão de trabalho.

Sugestões futuras para melhorar a apresentação no portfólio
- Adicionar um resumo executivo no README com as principais conclusões e métricas finais.
- Incluir uma seção "Conjunto de dados" com estatísticas descritivas e possíveis limitações (viés, dados faltantes, outliers).
- Demonstrar uma comparação entre modelos (Ridge/Lasso/RandomForest) com validação cruzada e tabela sumarizada com métricas.
- Adicionar um notebook "slides" (nbconvert) ou uma apresentação PDF com os principais gráficos e conclusões para facilitar leitura pelo time de RH.

Licença
- Use uma licença apropriada (por exemplo MIT) se você pretende compartilhar publicamente.
