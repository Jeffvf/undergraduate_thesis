# [An Intelligent Early Flood Forecasting and Prediction Leveraging Machine and Deep Learning Algorithms with Advanced Alert System](https://www.mdpi.com/2227-9717/11/2/481)

## Sobre
O estudo propõe um sistema de previsão e alerta precoce de enchentes usando técnicas de aprendizado de máquina (ML) e aprendizado profundo (DL). Modelos como ES-LSTM, RNN, ANN e árvore de decisão (DT) foram usados para prever e classificar precipitações, utilizando dados meteorológicos históricos da Austrália. O ES-LSTM e RNN foram empregados para análise de séries temporais e previsão de chuva, enquanto ANN e DT foram usados para classificação. A pesquisa obteve resultados promissores, com precisão de 96,65% para o ANN e erro médio percentual absoluto (MAPE) de 3,17 para o ES-LSTM.

## Modelos utilizados
- ES-LSTM (Exponential Smoothing - Long Short-Term Memory): Previsão de chuva usando séries temporais.
- RNN (Recurrent Neural Network): Análise de dependências temporais na série de dados.
- ANN (Artificial Neural Network): Classificação da presença de chuva.
- Árvore de Decisão (DT): Classificação complementar à ANN.

## Métricas de performance
- ANN: Precisão.
- DT: Precisão.
- ES-LSTM: MAPE.
- RNN: MAPE.

## Limitações identificadas
- Dados de sensores com lacunas: Algumas leituras ausentes foram preenchidas com valores médios, o que pode impactar a qualidade dos resultados.
- Dependência de modelos únicos: Embora o estudo combine ML e DL, muitos dos modelos avaliados dependem de uma única abordagem, o que pode reduzir a robustez geral.
- Ruído e outliers nos dados: A presença de outliers pode impactar negativamente a acurácia do modelo.
- Limitações de escalabilidade: O sistema foi testado em um conjunto de dados específico e pode não generalizar bem para outros cenários climáticos ou geográficos