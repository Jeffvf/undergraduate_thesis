# [Application of Long Short-Term Memory (LSTM) Networks for Flood Forecasting](https://doi.org/10.3390/w11071387)  

## Sobre
O estudo explora o uso de redes neurais do tipo LSTM (Long Short-Term Memory) para previsão de cheias no Rio Da, no Vietnã. Os dados utilizados incluem vazões diárias e precipitações de estações hidrometeorológicas, abrangendo diferentes cenários. Foram propostas duas abordagens principais de entrada de dados, comparando precipitação e vazão em diversas estações. O modelo foi avaliado em previsões de um, dois e três dias, alcançando alta precisão, particularmente para previsões de curto prazo.

## Modelos utilizados
- LSTM (Long Short-Term Memory)


## Métricas de performance
- NSE
- RMSE

## Limitações
- Precisão limitada para previsões de longo prazo: A eficácia do modelo diminui em previsões acima de dois dias.
- Dependência de dados hidrométricos: O modelo é limitado por sua necessidade de dados de vazão e apresenta menor desempenho quando utiliza precipitação como variável.
- Generalização: Treinado em um único sistema fluvial, pode ser necessário recalibrar para outras regiões.
- Ruído em dados de precipitação: Dados de precipitação apresentaram menor correlação com a vazão, causando potenciais imprecisões.