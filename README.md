# Cursos de Graduação no Brasil - Classificação e Regressão

:game_die: **Dataset Cursos de Graduação Brasil:** [Clique aqui](https://dadosabertos.mec.gov.br/indicadores-sobre-ensino-superior/item/183-cursos-de-graduacao-do-brasil)

:game_die: **Dataset Worlds Best Universities:** [Clique aqui](
https://www.kaggle.com/datasets/darrylljk/worlds-best-universities-qs-rankings-2025)


:page_facing_up: **Relatório:** [Clique aqui](/relatorio/Relatório.pdf)

:tv: **Slide:** [Clique aqui](https://www.canva.com/design/DAGL4KPcbRU/QjbD-zuC5lVUlhbTX14cHg/edit?utm_content=DAGL4KPcbRU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Resumo

Este repositório faz parte de um projeto desenvolvido na disciplina de Análise Computacional da Aprendizagem, onde o autor criou modelos de aprendizado de máquina, especialmente classificação e regressão com uma base dados extraída do portal de dados abertos do Ministério da Educação (MEC) sobre os cursos de graduação no Brasil. Além disso, é mostrado as etapas de pré-processamento, incluindo limpeza, balanceamento e transformação. Por fim, é exposto os resultados das métricas dos modelos, sendo 79% de acurácia para o modelo de classificação e um R2 de 0.63 para o modelo de regressão.

## :warning: Orientações para executar o projeto

![Imagem do projeto no Orange](/imgs/img_projeto.png)

Vamos dividir o projeto orange acima em 3 modelos:
1. **Localizado acima:** Classificação
2. **Localização inferior esquerda:** Regressão 1
3. **Localização inferior direita:** Regressão 2

Para executar os modelos, siga os passos abaixo:

1. Baixe o [arquivo](/models/projeto-u2.ows) que está dentro do diretório **models** com o nome `projeto-u2.ows`.
2. Com o software Orange devidamente instalado, carregue o arquivo `projeto-u2.ows`.

**Classificação**

1. No diretório **datasets** baixe o [arquivo](/datasets/balanced_dataset.csv) `balanced_dataset.csv`.
2. Em seguida faça o upload do `balanced_dataset.csv` no ***File*** para carregar o modelo de classificação.

**Regressão 1**

1. No diretório **datasets** baixe o [arquivo](/datasets/transformedstandardized_dataset.csv) `transformedstandardized_dataset.csv`.
2. Em seguida faça o upload do `transformedstandardized_dataset.csv` no ***File(1)*** para carregar o modelo de regressão 1.

**Regressão 2**

O modelo de Regressão 2 serve apenas de fins didáticos para analisar o que seria uma relação linearmente forte entre duas variáveis em um modelo de regressão linear. O mesmo faz uma predição do score no ranking das melhores universidades do mundo de acordo com a extensão das colaborações internacionais em pesquisa.

1. No diretório **datasets** baixe o [arquivo](/datasets/qs-world-rankings-2025-fake.csv) `qs-world-rankings-2025-fake.csv`.
2. Em seguida faça o upload do `qs-world-rankings-2025-fake.csv` no ***File(2)*** para carregar o modelo de regressão 2.