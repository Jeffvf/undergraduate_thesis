# [A spatial–temporal graph deep learning model for urban flood nowcasting leveraging heterogeneous community features](https://www.nature.com/articles/s41598-023-32548-x)

## Sobre
O estudo propõe um modelo de aprendizado profundo baseado em grafos, chamado ASTGCN (Attention-based Spatial-Temporal Graph Convolutional Network), para previsão de inundações urbanas (nowcasting) em nível de setores censitários. O modelo integra dados físicos (precipitação e elevação da água) e dados sensoriados por humanos (relatos de moradores, tweets sobre inundações e rastros digitais de atividades humanas), permitindo previsões de curto prazo com alta precisão. O estudo foi aplicado ao condado de Harris, Texas, durante o furacão Harvey, em 2017, e demonstrou desempenho superior ao de modelos tradicionais como LSTM e variantes de GCN.

## Modelos utilizados
ASTGCN: Combina convoluções espaciais e temporais em grafos com um mecanismo de atenção para capturar dependências complexas nos dados.

## Métricas de performance
- Precisão
- Recall
- F1 Score
- Acurácia

## Limitações identificadas
- Escalabilidade: O modelo foi testado em um único evento e local, limitando sua aplicabilidade a outras regiões.
- Dados limitados: O uso de dados sensoriados por humanos é restrito a eventos específicos (como o furacão Harvey), dificultando a generalização.
- Dependência de integração de dados: A eficácia do modelo depende da fusão de múltiplas fontes de dados, que nem sempre estão disponíveis em tempo real.
- Desempenho decrescente com o tempo: Observou-se redução na precisão das previsões em períodos mais longos sem atualizações do modelo.