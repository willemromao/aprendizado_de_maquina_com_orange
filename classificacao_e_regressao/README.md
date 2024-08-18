# Classificação e Regressão

:game_die: **Dataset Cursos de Graduação Brasil:** [Clique aqui](https://dadosabertos.mec.gov.br/indicadores-sobre-ensino-superior/item/183-cursos-de-graduacao-do-brasil)

:game_die: **Dataset Worlds Best Universities:** [Clique aqui](
https://www.kaggle.com/datasets/darrylljk/worlds-best-universities-qs-rankings-2025)


:page_facing_up: **Relatório:** [Clique aqui](/relatorio/Relatório.pdf)

## Resumo

Este repositório faz parte de um projeto, onde o autor criou modelos de aprendizado de máquina, especialmente classificação e regressão com uma base dados extraída do portal de dados abertos do Ministério da Educação (MEC) sobre os cursos de graduação no Brasil e outra base do QS World University Rankings. Os resultados das métricas dos modelos, sendo 79% de acurácia para o modelo de classificação e um R2 de 0.91 para o modelo de regressão.

## :warning: Orientações para executar o projeto

Para executar os modelos, siga os passos abaixo:

1. Baixe os seguintes arquivos:
    - Projeto classificação: [clique aqui](/classificacao_e_regressao/modelos/projeto_orange/classificacao.ows).
    - Projeto regressão: [clique aqui](/classificacao_e_regressao/modelos/projeto_orange/regressao.ows).
2. Com o software Orange devidamente instalado, carregue esses arquivos clicando em `Open`.

**Classificação**

<img src="/classificacao_e_regressao/imgs/projeto_classificacao.png" alt="projeto_classificacao" width="825" height="350">

1. No diretório **datasets** baixe o [arquivo](/classificacao_e_regressao/datasets/cursos_graduacao_brasil_balanceado.csv) `cursos_graduacao_brasil_balanceado.csv`.
2. Em seguida faça o upload do `cursos_graduacao_brasil_balanceado.csv` no ***File*** para carregar o modelo de classificação.

**Regressão**

<img src="/classificacao_e_regressao/imgs/projeto_regressao.png" alt="projeto_regressao" width="450" height="350">

1. No diretório **datasets** baixe o [arquivo](/classificacao_e_regressao/datasets/qs_world_rankings_2025_fake.csv) `qs_world_rankings_2025_fake.csv`.
2. Em seguida faça o upload do `qs_world_rankings_2025_fake.csv` no ***File*** para carregar o modelo de regressão.
