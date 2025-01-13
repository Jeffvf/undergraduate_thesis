# [Fast simulation and prediction of urban pluvial floods using a deep convolutional neural network model](https://www.sciencedirect.com/science/article/abs/pii/S0022169423008879)

## Sobre
Este estudo propõe um modelo baseado em redes neurais convolucionais (CNN) para previsão e simulação rápidas de inundações urbanas devido a chuvas intensas. A abordagem substitui modelos baseados em física, que são precisos, mas computacionalmente lentos, por um modelo de aprendizado profundo que é significativamente mais rápido. O CNN foi treinado usando um banco de dados de cenários de chuva e inundação gerados por um modelo acoplado (SWMM e LISFLOOD-FP). O modelo mostrou alta precisão, sendo 600 vezes mais rápido que o modelo baseado em física.

## Modelos utilizados
- CNN (Convolutional Neural Network): Para previsão da profundidade da água e evolução espacial e temporal da inundação.
- Modelos comparativos:
    - XGBoost (Extreme Gradient Boosting).
    - MORF (Multi-objective Random Forest).
    - KNN (K-Nearest Neighbors).

## Métricas de performance
- CNN:
    - Coeficiente de Correlação de Pearson (PCC).
    - Erro Médio Absoluto (MAE).
    - Erro Médio Quadrático (RMSE).
    - Eficiência de Nash-Sutcliffe (NSE).

- Modelos comparativos:
    - XGBoost: PCC, MAE, RMSE.
    - MORF: PCC, MAE, RMSE.
    - KNN: PCC, MAE, RMSE.

## Limitações identificadas
- Dependência de dados gerados por modelos físicos: O treinamento foi baseado em cenários simulados, não em medições reais, o que pode limitar a aplicação prática.
- Generalização para eventos extremos: O modelo apresentou menor precisão para cenários com períodos de retorno de 100 anos.
- Recursos computacionais para treinamento: Embora rápido na previsão, o treinamento do CNN exige maior capacidade computacional comparado aos modelos ML tradicionais.
- Ausência de características espaciais: O modelo usa apenas características temporais, descartando potenciais informações espaciais no treinamento.