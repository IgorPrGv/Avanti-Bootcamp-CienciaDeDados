# Predição de Inadimplência em Cartões de Crédito

## Resumo

Este projeto tem como objetivo explorar e analisar um conjunto de dados relacionado à inadimplência em cartões de crédito e desenvolver um modelo de aprendizado de máquina para prever essas inadimplências. Utilizando o conjunto de dados "Default of Credit Card Clients", inclui diversas variáveis, como limite de crédito, sexo, idade e histórico de pagamentos, e o objetivo é desenvolver insights que possam ser úteis na previsão de inadimplência em clientes de cartões de crédito, tendo como alvo a variável "default payment next month".

## Justificativa

A inadimplência em pagamentos de cartões de crédito é uma preocupação significativa e um conheicmento crucial para instituições financeiras, pois ajuda na identificação de padrões de comportamento dos clientes e na implementação de estratégias para mitigar riscos. 
Logo, compreender os fatores que contribuem para a inadimplência e desenvolver um modelo preciso de predição pode auxiliar na identificação proativa de clientes com maior risco de inadimplência, permitindo a implementação de medidas preventivas.

## Resumo Gráfico
--------OFF------

## Desenvolvedores

- [Laissa Gama](https://github.com/laissaGmA)
- [Igor Pereira](https://github.com/IgorPrGv2)
- [Guilherme Oliveira](https://github.com/oliveiraggui)

## Objetivos e Resultados Chave

O projeto possui os seguintes objetivos e resultados chave:

### Exploração de Dados

- [x] Análise exploratória do conjunto de dados "Default of Credit Card Clients".
- [x] Identificação e correção de valores nulos e faltantes.
- [x] Criação de gráficos descritivos.

### Desenvolvimento do Dicionário de Dados

- [x] Criação do arquivo `data/external/dicionario.csv` com as colunas: variavel, significado, tipo e subtipo.
- [x] Inserção de informações referentes ao arquivo de dados utilizado no projeto.

### Notebook de Análise Exploratória

- **01 - Exploratory Data Analysis.ipynb**
  - Descrição dos dados: informações sobre a quantidade de instâncias, variáveis e seus tipos, quantidade de valores faltantes utilizando o dicionário de dados.
  - Perguntas de partida e hipóteses: levantamento de informações que podem ser obtidas a partir dos dados e hipóteses a serem testadas.
  - Insights: respostas às perguntas anteriores e informações interessantes extraídas dos dados.

---

## Utilização

Para replicar o projeto, recomenda-se a utilização do Poetry. Para mais informações e instruções de instalação, acesse [Poetry](https://python-poetry.org/).

Após a instalação e a clonagem deste projeto, dentro da pasta do projeto, execute o comando para instalar as dependências.

```bash
poetry install
