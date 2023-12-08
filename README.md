# Predição de Inadimplência em Cartões de Crédito


## Desenvolvedores
- [Laissa Gama](https://github.com/laissaGmA)
- [Igor Pereira](https://github.com/IgorPrGv2)
- [Guilherme Oliveira](https://github.com/oliveiraggui)


## Resumo
Este projeto tem como objetivo explorar e analisar um conjunto de dados relacionado à inadimplência em cartões de crédito e desenvolver um modelo de aprendizado de máquina para prever essas inadimplências. Utilizando o conjunto de dados "Default of Credit Card Clients", inclui diversas variáveis, como limite de crédito, sexo, idade e histórico de pagamentos, e o objetivo é desenvolver insights que possam ser úteis na previsão de inadimplência em clientes de cartões de crédito, tendo como alvo a variável "default payment next month".

## Justificativa
A inadimplência em pagamentos de cartões de crédito é uma preocupação significativa e um conhecimento crucial para instituições financeiras, pois ajuda na identificação de padrões de comportamento dos clientes e na implementação de estratégias para mitigar riscos. Logo, compreender os fatores que contribuem para a inadimplência e desenvolver um modelo preciso de predição pode auxiliar na identificação proativa de clientes com maior risco de inadimplência, permitindo a implementação de medidas preventivas.

## Objetivos e Resultados Chave
O projeto possui os seguintes objetivos e resultados chave:

### Exploração de Dados
- Análise exploratória do conjunto de dados "Default of Credit Card Clients".
- Identificação e correção de valores nulos e faltantes.
- Criação de gráficos descritivos.

### Desenvolvimento do Dicionário de Dados
- Criação do arquivo data/external/dicionario.csv com as colunas: variável, significado, tipo e subtipo.
- Inserção de informações referentes ao arquivo de dados utilizado no projeto.

### Notebook de Análise Exploratória
- [01 - Exploratory Data Analysis.ipynb](https://github.com/atlantico-academy/equipe-05/blob/master/notebooks/01-exploratory_data_analysis.ipynb)

### Notebook de Análise Comparativa
- [02 - Comparative Analysis.ipynb](https://github.com/atlantico-academy/equipe-05/blob/master/notebooks/02-comparative_analysis.ipynb) 

## Preparação dos Dados para Análise Comparativa
A equipe realizou a preparação dos dados para análise comparativa conforme as seguintes etapas:

- **Tratamento de Dados Faltantes:** Identificação e tratamento adequado de dados faltantes para garantir a integridade do conjunto de dados.
- **Codificação de Variáveis:** Mapeamento e codificação de variáveis categóricas para garantir a adequada representação nos modelos de machine learning.
- **Normalização:** Normalização das variáveis numéricas para assegurar que diferentes escalas não impactem a performance dos modelos.


## Metodologia da Análise Comparativa
A equipe adotou a metodologia de validação cruzada k-fold para avaliar o desempenho dos modelos, dividindo o conjunto de dados em k subconjuntos, treinando o modelo em k-1 desses subconjuntos e testando no subconjunto restante. Foram utilizados quatro modelos distintos para comparação, incluindo um modelo baseline (Regressão Logística) e outros três modelos (Random Forest, SVM e Decision Tree Classifier).


## Configuração do Experimento
Os dados foram divididos em conjuntos de treino e teste, e as métricas de avaliação, como Acurácia e F1-Score, foram utilizadas para comparar o desempenho dos modelos.


## Resultados e Discussão
Os resultados detalhados da análise comparativa dos modelos estão apresentados na tabela abaixo:

| Modelo                    | Acurácia Média | F1-Score Médio |
|---------------------------|----------------|----------------|
| Regressão Logística       | 82.03%         | 46.79%         |
| Random Forest             | 81.60%         | 46.98%         |
| SVM                       | 81.96%         | 43.87%         |
| Decision Tree Classifier  | 72.92%         | 40.78%         |


Ao avaliar as métricas de Acurácia Média e F1-Score Médio, observamos que a Regressão Logística se destacou como o modelo mais eficaz, apresentando uma Acurácia Média de 82.03% e um F1-Score Médio de 46.79%. Esses resultados são particularmente significativos, considerando a complexidade do problema e a presença de desequilíbrio nas classes.

Os modelos de Random Forest e SVM também demonstraram desempenho sólido, mas a Regressão Logística permanece como a escolha preferencial com base nas métricas avaliadas. Essa análise proporciona insights valiosos sobre a capacidade dos modelos em lidar com os desafios específicos do conjunto de dados em questão.


## Considerações Finais
Este projeto não apenas forneceu uma solução para o problema inicial, mas também ofereceu insights valiosos sobre a natureza dos dados e a eficácia de diferentes abordagens. Futuros trabalhos podem envolver a expansão do conjunto de dados, a inclusão de características adicionais ou a exploração de algoritmos mais avançados.

Em resumo, o projeto demonstra a aplicação bem-sucedida de técnicas de ciência de dados e aprendizado de máquina na resolução do problema proposto, e o modelo de Regressão Logística otimizado é recomendado para implementação em cenários práticos.

## Utilização
Para replicar o projeto, recomenda-se a utilização do Poetry. Para mais informações e instruções de instalação, acesse [Poetry](https://python-poetry.org/).

Após a instalação e a clonagem deste projeto, dentro da pasta do projeto, execute o comando para instalar as dependências.

```bash
poetry install


