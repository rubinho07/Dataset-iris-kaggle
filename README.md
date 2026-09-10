# Classificação do Dataset Iris com SVM

Projeto desenvolvido para realizar a análise exploratória do dataset Iris e criar um modelo de classificação utilizando o algoritmo **Support Vector Machine (SVM)**.

## Objetivo

O objetivo do projeto é utilizar as medidas das sépalas e pétalas para classificar uma flor em uma das seguintes espécies:

- Iris-setosa;
- Iris-versicolor;
- Iris-virginica.

## Dataset

Foi utilizado o dataset [Iris Species](https://www.kaggle.com/datasets/menegidio/iris-species), disponibilizado no Kaggle.

O dataset possui as seguintes informações:

- Comprimento da sépala;
- Largura da sépala;
- Comprimento da pétala;
- Largura da pétala;
- Espécie da flor.

## Etapas do projeto

O projeto foi desenvolvido nas seguintes etapas:

1. Importação das bibliotecas;
2. Carregamento do dataset;
3. Análise exploratória dos dados;
4. Verificação de valores ausentes;
5. Visualização dos dados por meio de gráficos;
6. Separação dos dados de treinamento e teste;
7. Padronização das características;
8. Criação e treinamento do modelo SVM;
9. Avaliação dos resultados.

## Tecnologias utilizadas

- Python;
- Pandas;
- Matplotlib;
- Seaborn;
- Scikit-learn;
- Kaggle Notebooks.

## Modelo de classificação

O algoritmo utilizado foi o **Support Vector Machine (SVM)**, por meio da classe `SVC` da biblioteca Scikit-learn.

Antes do treinamento, os dados foram padronizados com o `StandardScaler`. Em seguida, foram divididos em 80% para treinamento e 20% para teste.

## Avaliação

O desempenho do modelo foi avaliado utilizando as seguintes métricas:

- Acurácia;
- Precisão;
- Recall;
- F1-score;
- Matriz de confusão.

Essas métricas permitem verificar a quantidade de classificações corretas e identificar em quais espécies o modelo apresentou erros.

## Notebook do projeto

O notebook completo pode ser acessado no Kaggle:

[Acessar o notebook Iris Dataset](https://www.kaggle.com/code/vitor2505/vitordias-irisdataset)

## Como executar

1. Acesse o notebook pelo link acima;
2. Faça uma cópia utilizando a opção **Copy & Edit**;
3. Confirme se o dataset Iris Species está anexado;
4. Execute todas as células utilizando a opção **Run All**.

## Autor

**Luis Fernando Rubinho Souza**

Projeto desenvolvido como atividade da disciplina de Inteligência Artificial.
