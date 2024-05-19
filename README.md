# Desafio Kaggle: House Prices
## Técnicas Avançadas de Regressão 
Desafio disponível em https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/

Este estudo tem como objetivo estimar o valor correto de venda para cada casa do banco de dados proposto (test.csv), através da variável SalePrice. Os resultados são classficados de acordo com o erro quadrático médio (RMSE): quanto menor, melhor. São divulgados dois arquivos de Jupyter Notebook, citadamente 'house_prices.ipynb' e 'house_prices_adv.ipynb', o primeiro sendo a programação utilizada para a obtenção dos resultados descritos abaixo.

É utilizada linguagem Python por meio de arquivo Jupyter Notebook para a programação da solução do problema proposto, com aplicação de técnicas simples de data wrangling, imputação e estimação de resultados obtidos por modelos de aprendizado de máquinas supervisionado, utilizando especificamente a biblioteca Scikit-Learn.

### Modelos de regressão utilizados

- Regressão Linear (linear regression)
- Decision Tree (árvore de decisões)
- KNN - K Nearest Neighbors (Vizinhança Próxima)
- Gradient Booster
- Logistic Regression (Modelo Logístico, 'Logit' ou ainda Classificador de Máxima Entropia)
- Ridge
- Bayesian Ridge Regression

Nesta primeira abordagem o médodo GBR (gradient booster) mostrou-se o mais eficaz, com uma pontuação de 0.14569, entrando no leaderboard mundial na posição 2227 no momento da submissão (arquivo 'resultado.csv').

A partir dessa estimativa básica o próximo objetivo é a aprimoração da metodologia e modelagem, disponibilizada no arquivo 'house_prices_adv.ipynb' (em edição contínua até o momento): análise mais aprofundada da interação das variáveis, melhorar o trabalho com as variáveis categóricas, aprimorar os métodos de imputação, trabalhar a normalização dos dados pertinentes.

### Relação dos arquivos disponibilizados
A exceção dos arquivos Jupyter Notebook e de resultados, os demais arquivos são constantes e contem todas e quaisquer informações utilizadas desde a primeira abordagem ao conteúdo. Os resultados estimados para submissão da análise simplificada ('house_prices.ipynb') encontram-se no arquivo 'resultado.csv'.
