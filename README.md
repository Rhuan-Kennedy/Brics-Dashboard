# Dashboard de PIB per Capita dos Países BRICS com Previsões Futuras

## Descrição do Projeto

Este projeto explora a evolução do **PIB per capita** (PPP, Paridade de Poder de Compra) dos países que compõem o grupo **BRICS** (Brasil, Rússia, Índia, China e África do Sul), utilizando um modelo de **regressão linear** para fazer previsões de crescimento até 2030.

O projeto faz uso de bibliotecas como **Pandas**, **Matplotlib**, **Plotly** e **Dash** para análise, visualização e construção de um dashboard interativo, oferecendo ao usuário a possibilidade de visualizar a evolução histórica do PIB per capita e previsões futuras.

## Funcionalidades

- Análise Descritiva e Visualização**: Gráficos que mostram a evolução histórica do PIB per capita dos países BRICS.
- Modelagem Preditiva: Um modelo de regressão linear foi treinado para prever o crescimento do PIB per capita até 2030.
- Dashboard Interativo: O **Dash** é usado para criar um dashboard que permite selecionar países e visualizar dados reais e previsões futuras de forma interativa.
- Métricas de Avaliação: O desempenho do modelo é avaliado usando métricas como \( R^2 \), MAE, e RMSE.

## Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**
- **Numpy**
- **Scikit-learn**
- **Matplotlib**
- **Plotly**
- **Dash**
- **Joblib**

Avaliação do Modelo
O modelo de regressão linear foi avaliado com os seguintes resultados:

R²: 0.82
Erro Absoluto Médio (MAE): 581.73
Raiz do Erro Quadrático Médio (RMSE): 686.90
Essas métricas indicam que o modelo tem uma boa capacidade de explicar as variações do PIB per capita nos dados de teste.



