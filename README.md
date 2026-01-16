# Tech Challenge 2 
Pós graduação em Data Analytics: Projeto da fase 2.
Tema: Machine Learning e Time Series.

---

## Índice

- [Contexto do Projeto](#contexto-do-projeto)
- [Arquivos no Repositório](#arquivos-no-repositório)
- [Ferramentas e Tecnologias Utilizadas](#ferramentas-e-tecnologias-utilizadas)
- [Autores](#autores)

## Contexto do Projeto

Você foi recentemente alocado em uma equipe de cientistas de dados de
um grande fundo de investimentos brasileiro. Sua missão inicial é desenvolver
um modelo preditivo capaz de prever se o índice IBOVESPA vai fechar em alta
ou baixa no dia seguinte, com base em dados históricos do próprio índice. Esse
modelo será usado como insumo para alimentar dashboards internos de tomada
de decisão dos analistas quantitativos da empresa.

Os dados devem ser extraídos do https://br.investing.com/indices/bovespa-historical-data

Criar um modelo que preveja se o fechamento do IBOVESPA do dia
seguinte será maior ou menor que o do dia atual, ou seja, se o valor fechará em Alta (1) ou Queda (0).

Seu modelo deve prever a tendência (↑ ou ↓) com acuracidade mínima de 75% em um conjunto de teste. 
O conjunto de testes deverá conter o último mês (30 dias) de dados disponíveis.

## Arquivos no Repositório

- `previsao_ibovespa.ipynb`: Notebook com todo o processo de análise e criação dos modelos utilizados para previsão do Ibovespa.
- `dados_ibovespa.csv`: Base de dados extraída do site oficial que será utilizada para alimentar os modelos desenvolvidos.
- `requirements.txt`: Arquivo de texto com as bibliotecas necessárias para executar o código.

## Ferramentas e Tecnologias Utilizadas

- **Python**: Linguagem de programação principal utilizada no projeto.
- **Scikit-Learn**: Utilizado para a construção e avaliação dos modelos de Machine Learning.
- **Seaborn**: para criação de visualizações
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib/Seaborn**: Para a criação de gráficos e visualizações de dados.
- **Jupyter Notebook**: Ambiente utilizado para o desenvolvimento e execução do código.

## Autores

- **Pedro Lopes de Lucena** - RM 367572
- **Guilherme Nascimento** - RM 367283
- **Jonas Sena Silva** - RM 367569
- **Rafael Santos** - RM 368581