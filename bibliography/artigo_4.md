# [Particle Swarm Optimization Based LSTM Network for Flood Prediction](https://doi.org/10.1016/j.rineng.2023.100951)

## Sobre
O estudo apresenta uma abordagem híbrida utilizando redes LSTM (Long Short-Term Memory) otimizadas por PSO (Particle Swarm Optimization) para prever níveis de água em uma rede complexa de rios em Bangladesh. A PSO é usada para ajustar hiperparâmetros críticos da LSTM, como número de células ocultas e taxa de aprendizado, maximizando a eficiência do modelo (NSE). O modelo foi testado em 24 estações fluviais, permitindo previsões de 1 a 15 dias à frente. Os resultados mostraram que a PSO-LSTM supera modelos como ANN, PSO-ANN e LSTM padrão, tanto em precisão quanto em estabilidade.

## Modelos utilizados
- PSO-LSTM (Particle Swarm Optimization - Long Short-Term Memory): Rede neural otimizada para previsão multitemporal de níveis de água.
- ANN (Artificial Neural Network) e PSO-ANN: Modelos base para comparação.
- LSTM convencional: Para análise comparativa de desempenho.

## Métricas de performance
- PSO-LSTM:
    - Nash-Sutcliffe Efficiency (NSE).
    - Root Mean Square Error (RMSE).
    - Mean Absolute Error (MAE).
    - Mean Absolute Percentage Error (MAPE).
- Comparações:
    - ANN e PSO-ANN: NSE inferior a PSO-LSTM, com precisão ligeiramente menor.
    - LSTM convencional: Desempenho consistentemente mais baixo.

## Limitações
- Qualidade dos dados: Dependência de dados históricos com lacunas preenchidas por interpolação, o que pode limitar a precisão.
- Escalabilidade: Modelo foi aplicado apenas em uma rede específica de rios em Bangladesh; a generalização para outras regiões pode exigir ajustes.
- Previsões de longo prazo: Precisão diminui à medida que o tempo de previsão aumenta (ex.: 15 dias).
- Fatores externos ignorados: Dados climáticos adicionais, como precipitação, poderiam melhorar ainda mais as previsões.