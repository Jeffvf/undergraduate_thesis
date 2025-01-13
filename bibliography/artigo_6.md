# [Prediction of Flood Using Optimized Neural Networks](https://doi.org/10.15551/pesd2021152004)

## Sobre
O estudo investiga o uso de redes neurais artificiais otimizadas pelo algoritmo Gray Wolf (GWO) para previsão de enchentes no Rio Maroon, Irã. O modelo neural utilizado é um Perceptron Multicamadas (MLP), cujo desempenho foi melhorado com o ajuste dos pesos e hiperparâmetros via GWO. Dados de fluxo do rio e escalas de nível de água de duas estações ao longo de 8 anos foram usados como entrada. O modelo otimizou a divisão de dados em 80% para treinamento e 20% para teste, alcançando melhores resultados em comparação com redes neurais básicas e métodos genéticos.

## Modelos utilizados
- MLP (Perceptron Multicamadas): Para previsão do fluxo e níveis de água.
- GWO (Gray Wolf Optimization): Para otimização dos pesos da rede neural.

## Métricas de performance
- MSE (Erro Quadrático Médio)

## Limitações identificadas
- Complexidade computacional: O tempo necessário para otimização pelo GWO é elevado em relação a outros algoritmos.
- Generalização limitada: O modelo foi testado apenas em uma região e pode não ser diretamente aplicável a outros sistemas fluviais.
- Sensibilidade aos dados: Resultados dependem fortemente da qualidade e quantidade dos dados disponíveis, como fluxo e escala do rio.
