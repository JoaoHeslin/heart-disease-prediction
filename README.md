# Classificação de Tendência a Doenças Cardíacas

Este projeto visa classificar com eficiência a tendência de uma pessoa desenvolver doenças cardíacas, utilizando algoritmos de machine learning e otimizando os hiperparâmetros para maximizar a precisão do modelo.

## Objetivo

O objetivo principal é prever a probabilidade de uma pessoa ter doenças cardíacas com alta precisão, com base em um conjunto de dados de saúde. O modelo alcançou uma **pontuação média de teste de 92.72%**, demonstrando a eficácia da abordagem.

## Estrutura do Notebook

O projeto é dividido nas seguintes seções:

1. **Importação das Bases de Dados**: Carregamento e exploração inicial dos dados para análise.
2. **Informações da Base**: Análise do conjunto de dados, incluindo a verificação de valores ausentes e estatísticas descritivas.
3. **EAD das Colunas**: Realização de Análise Exploratória dos Dados (EAD).
4. **Pré-processamento dos Dados**: Tratamento dos dados.
5. **Algoritmos de Machine Learning**: Implementação de modelos de aprendizado de máquina, com foco em classificação.
6. **Otimização dos Hiperparâmetros**: Uso de técnicas como **GridSearchCV** para encontrar a melhor combinação de hiperparâmetros e melhorar a performance do modelo.

## Bibliotecas Utilizadas

- **pandas**: Para manipulação e análise de dados.
- **matplotlib**: Para visualização de gráficos e dados.
- **seaborn**: Para análise exploratória dos dados.
- **numpy**: Para operações matemáticas e manipulação de arrays.
- **sklearn**: Para construção e avaliação de modelos de machine learning, além de otimização de hiperparâmetros com **GridSearchCV**.
- **catboost**: Para o algoritmo de classificação CatBoost, utilizado no modelo.

## Resultados

O modelo de machine learning foi treinado e avaliado, com os melhores resultados alcançados utilizando a combinação de **100 iterações**, **taxa de aprendizado 0.1** e **profundidade 7**. A **pontuação média de teste de 92.72%** foi obtida, o que indica um bom desempenho na previsão da tendência a doenças cardíacas.

## Como Executar

1. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn numpy scikit-learn catboost
2. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/heart-disease-prediction.git
3. Execute o notebook no Jupyter:
   ```bash
   jupyter notebook
4. Abra o notebook Heart Disease Prediction e execute as células conforme a sequência do projeto.
