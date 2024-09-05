# Dashboard de PIB per Capita dos Países BRICS com Previsões Futuras

## Descrição do Projeto

Este projeto explora a evolução do PIB per capita (PPP, Paridade de Poder de Compra) dos países que compõem o grupo BRICS (Brasil, Rússia, Índia, China e África do Sul), utilizando um modelo de regressão linear para fazer previsões de crescimento até 2030.

O projeto faz uso de bibliotecas como Pandas, Matplotlib, Plotly e Dash para análise, visualização e construção de um dashboard interativo, oferecendo ao usuário a possibilidade de visualizar a evolução histórica do PIB per capita e previsões futuras.

## Funcionalidades

- Análise Descritiva e Visualização: Gráficos que mostram a evolução histórica do PIB per capita dos países BRICS.
- Modelagem Preditiva: Um modelo de regressão linear foi treinado para prever o crescimento do PIB per capita até 2030.
- Dashboard Interativo: O Dash é usado para criar um dashboard que permite selecionar países e visualizar dados reais e previsões futuras de forma interativa.
- Métricas de Avaliação: O desempenho do modelo é avaliado usando métricas como \( R^2 \), MAE, e RMSE.


Gráficos e Visualizações

Gráfico Interativo de Linha para o Brasil:

Este gráfico mostra a evolução do PIB per capita do Brasil de 1970 a 2020.
![Grafico brasil](https://github.com/user-attachments/assets/7c833350-ea0f-4787-8376-6fbdeb740012)

Gráfico de Linha para Todos os Países do BRICS:

Este gráfico mostra a evolução do PIB per capita para todos os países do BRICS.
![Evolução Pib Brics](https://github.com/user-attachments/assets/ccc9cfc1-3b33-4f3b-ad3c-52f79be7706d)

Dashboard Interativo com Dash
O Dashboard foi desenvolvido utilizando Dash e permite que você selecione qualquer um dos países do BRICS para visualizar a evolução do PIB per capita e as previsões futuras.

![newplot (3)](https://github.com/user-attachments/assets/136f1229-6d14-4b1b-95d3-3423a77197e4)

Gráficos interativos gerados com Plotly não são exibidos diretamente no GitHub porque dependem de interações dinâmicas (JavaScript). No entanto, você pode visualizá-los executando o código localmente em seu ambiente Jupyter Notebook ou Python.

## Tecnologias Utilizadas

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Plotly
- Dash
- Joblib

Avaliação do Modelo
O modelo de regressão linear foi avaliado com os seguintes resultados:

R²: 0.82
Erro Absoluto Médio (MAE): 581.73
Raiz do Erro Quadrático Médio (RMSE): 686.90
Essas métricas indicam que o modelo tem uma boa capacidade de explicar as variações do PIB per capita nos dados de teste.



