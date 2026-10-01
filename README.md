# Predição do Cumprimento de Metas de Produtividade

Projeto desenvolvido na disciplina de Machine Learning do curso de Engenharia da Computação.

O objetivo é prever o risco de uma equipe **não atingir a meta de produtividade**, utilizando dados históricos da indústria de confecção.

## Dataset

Foi utilizado o dataset **Productivity Prediction of Garment Employees**, disponibilizado pela UCI Machine Learning Repository.

A variável alvo foi criada a partir da comparação entre:

- `targeted_productivity`
- `actual_productivity`

Classes:

- `0` = atingiu a meta
- `1` = não atingiu a meta

## Modelos utilizados

Foram desenvolvidos e comparados dois modelos de classificação:

- Regressão Logística
- K-Nearest Neighbors (KNN)

Também foram realizados testes de:

- pré-processamento
- remoção de variáveis
- tratamento de valores ausentes
- escalonamento
- One-Hot Encoding
- ajuste de hiperparâmetros
- ajuste de limiar de decisão
- PCA

## Resultado

A **Regressão Logística** apresentou o melhor resultado no conjunto de teste, com melhor equilíbrio entre Precision, Recall e F1, além de gerar menos falsos positivos que o KNN.

## Tecnologias

- Python
- Google Colab
- pandas
- NumPy
- matplotlib
- scikit-learn

## Execução

Abra o notebook no Google Colab, carregue o arquivo `dataset.csv` e execute as células em sequência.
