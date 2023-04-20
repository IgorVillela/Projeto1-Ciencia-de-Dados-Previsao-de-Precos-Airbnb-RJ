# Projeto1 - Ciencia de Dados - Previsao de Precos Airbnb RJ
 
## Contexto
No Airbnb, qualquer pessoa que tenha um quarto ou um imóvel de qualquer tipo (apartamento, casa, chalé, pousada, etc.) pode ofertar o seu imóvel para ser alugado por diária.

Você cria o seu perfil de host (pessoa que disponibiliza um imóvel para aluguel por diária) e cria o anúncio do seu imóvel.

Nesse anúncio, o host deve descrever as características do imóvel da forma mais completa possível, de forma a ajudar os locadores/viajantes a escolherem o melhor imóvel para eles (e de forma a tornar o seu anúncio mais atrativo)

Existem dezenas de personalizações possíveis no seu anúncio, desde quantidade mínima de diária, preço, quantidade de quartos, até regras de cancelamento, taxa extra para hóspedes extras, exigência de verificação de identidade do locador, etc.

## Objetivo
Construir um modelo de previsão de preço que permita uma pessoa comum que possui um imóvel possa saber quanto deve cobrar pela diária do seu imóvel.

Ou ainda, para o locador comum, dado o imóvel que ele está buscando, ajudar a saber se aquele imóvel está com preço atrativo (abaixo da média para imóveis com as mesmas características) ou não.

O que temos disponível, inspirações e créditos
As bases de dados foram retiradas do site kaggle: https://www.kaggle.com/allanbruno/airbnb-rio-de-janeiro

Solução do usuário Allan Bruno do kaggle no Notebook: https://www.kaggle.com/allanbruno/helping-regular-people-price-listings-on-airbnb

É possível perceber semelhanças entre a solução deste projeto e a dele, mas também algumas diferenças significativas no processo de construção do projeto.

As bases de dados são os preços dos imóveis obtidos e suas respectivas características em cada mês. Os preços são dados em reais (R$) Temos bases de abril de 2018 a maio de 2020, com exceção de junho de 2018 que não possui base de dados

## Etapas do projeto
### 1. Extração/Obtenção de Dados

### 2. Ajustes de Dados (Limpeza de Dados)

### 3. Análise Exploratória

### 4. Modelagem + Algoritmos

### 5. Interpretação dos Resultados

### 6. Deploy/Produção

## Bibliotecas utilizadas
Para o tratamento e análise dos dados: <br>
-pandas <br>
-pathlib <br>
-numpy

Para criação de diagramas/gráficos: <br>
-seaborn <br>
-matplotlib.pyplot <br>
-plotly.express

Para treinamento dos algoritmos de machine learning: <br>
-sklearn.metrics import mean_squared_error, r2_score <br>
-sklearn.linear_model import LinearRegression <br>
-sklearn.ensemble import RandomForestRegressor, ExtraTreesRegressor <br>
-sklearn.model_selection import train_test_split

Para salvar o modelo treinado: <br>
-joblib

Para o deploy: <br>
-pandas <br>
-streamlit <br>
-joblib
