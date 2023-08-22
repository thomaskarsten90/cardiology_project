## Previsão de Doenças Cardiológicas - README

Este repositório contém um projeto de previsão de doenças cardiológicas usando uma variedade de algoritmos de machine learning. O objetivo é desenvolver um modelo capaz de prever a presença ou ausência de doenças cardíacas com base em informações clínicas fornecidas.

### Base de Dados

A base de dados utilizada é composta por diversas características clínicas e de saúde que podem influenciar a ocorrência de doenças cardiológicas. Abaixo está uma legenda explicativa de cada coluna:

- **Age:** Idade em anos.
- **Sex:** Sexo (0 = Masculino; 1 = Feminino).
- **Chest Pain Type:** Tipo de dor no peito (0 = Angina Típica; 1 = Angina Atípica; 2 = Dor Não Anginosa; 3 = Assintomático).
- **Resting BP:** Pressão sanguínea em repouso (mmHg).
- **Cholesterol:** Colesterol sérico (mg/dl).
- **Fasting BS:** Açúcar no sangue em jejum (0 = Fasting BS < 120 mg/dl; 1 = Fasting BS >= 120 mg/dl, diabético).
- **Resting ECG:** Eletrocardiograma em repouso (0 = Normal; 1 = Anormalidade da Onda ST-T; 2 = Hipertrofia Ventricular Esquerda).
- **Max HR:** Frequência cardíaca máxima.
- **Exercise Angina:** Angina induzida por exercício (0 = Não; 1 = Sim).
- **Old Peak:** Depressão de ST induzida por exercício em relação ao repouso.
- **ST Slope:** Inclinação do segmento ST (0 = UP; 1 = Flat; 2 = Down).
- **Heart Disease:** Presença de doença cardíaca (0 = Não; 1 = Sim).

### Pré-processamento

As seguintes etapas de pré-processamento foram aplicadas aos dados antes da modelagem:

1. Carregamento dos dados.
2. Separação das características previsoras (atributos) e do alvo.
3. Aplicação de codificação de rótulo (Label Encoding) para transformar variáveis categóricas em numéricas.
4. Aplicação de codificação one-hot (One-Hot Encoding) para transformar variáveis categóricas com mais de duas categorias em múltiplas colunas binárias.
5. Padronização dos dados para garantir que todas as características tenham a mesma escala.
6. Separação dos dados em conjuntos de treinamento e teste.

### Algoritmos de Machine Learning

Foram testados oito algoritmos de machine learning para prever a ocorrência de doenças cardíacas:

- **Naive Bayes:** 
- **SVM (Support Vector Machine):** 
- **Regressão Logística:** 
- **K-Nearest Neighbors (KNN):** 
- **Decision Tree:** 
- **Random Forest:** .
- **XGBoost:** 
- **LightGBM:** 

A acurácia foi calculada para medir a taxa de acertos do modelo. Matrizes de confusão e validação cruzada também foram utilizadas para avaliar o desempenho dos algoritmos.

| Algoritmo        | Acurácia |
|------------------|----------|
| Naive Bayes      | 85.17%   |
| SVM              | 70.46%   |
| Regressão Logística | 85.62%   |
| KNN              | 68.70%   |
| Decision Tree    | 83.31%   |
| Random Forest    | 86.46%   |
| XGBoost          | 86.59%   |
| LightGBM         | 63.65%   |

Este projeto oferece uma análise abrangente da previsão de doenças cardiológicas usando diferentes algoritmos de machine learning e demonstra como o pré-processamento adequado pode impactar o desempenho dos modelos.

***Em breve postarei a conclusão***
