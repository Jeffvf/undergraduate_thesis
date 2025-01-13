# [Fast Prediction of Urban Flooding Water Depth Based on CNN−LSTM](https://www.mdpi.com/2073-4441/15/7/1397)

## Sobre
O estudo desenvolve um modelo híbrido CNN-LSTM (Convolutional Neural Network - Long Short-Term Memory) para prever rapidamente a profundidade de enchentes urbanas. O modelo é alimentado por dados de simulações hidrodinâmicas e usa características espaciais e temporais para prever profundidades de inundação em pontos críticos na cidade de Zhoukou, China. O modelo foi avaliado utilizando 20.422 amostras, abrangendo cenários históricos e de design de chuva intensa. O CNN-LSTM demonstrou alta precisão com um tempo de execução significativamente reduzido (10 segundos), adequado para gerenciamento emergencial de enchentes.

## Modelos utilizados
- CNN-LSTM (Convolutional Neural Network - Long Short-Term Memory):
    - CNN: Extrai características espaciais dos dados de entrada.
    - LSTM: Captura padrões temporais de variação nas enchentes.

## Métricas de performance
- Erro médio quadrático (MSE).
- Erro absoluto médio (MAE).
- Coeficiente de determinação (R²).
- Erro médio relativo entre medição real e previsão.

## Limitações identificadas
- Dependência de simulações hidrodinâmicas: A precisão do modelo CNN-LSTM depende da qualidade dos dados de treinamento gerados por modelos hidrodinâmicos.
- Erro relativo elevado em alguns pontos: Diferenças de até 6,50% em profundidade máxima prevista em comparação com medições reais.
- Aplicação regional limitada: O modelo foi projetado para uma área específica (Zhoukou) e pode exigir ajustes para outras regiões.
- Treinamento computacionalmente intensivo: Embora a previsão seja rápida, o treinamento exige recursos computacionais elevados.