# [Prediction of Flood Discharge Using Hybrid PSO-ANN Model](https://www.sciencedirect.com/science/article/pii/S2215016123000638) 

## Sobre
O estudo explora o uso do algoritmo híbrido PSO-SVM (Particle Swarm Optimization - Support Vector Machine) para prever a descarga de enchentes no Rio Barak, na Índia. O modelo combina o SVM, reconhecido por sua capacidade de resolver problemas não-lineares, com o PSO, que otimiza os parâmetros do SVM (como o núcleo e o coeficiente de regularização). Dados meteorológicos e hidrológicos, como precipitação, temperatura, radiação solar, umidade e perda de evapotranspiração, foram utilizados para modelar a descarga mensal do rio entre 1969 e 2018. Os resultados indicam que o PSO-SVM superou o SVM convencional e o BPNN (Backpropagation Neural Network), tanto em precisão quanto em consistência.

## Modelos utilizados
- PSO-SVM (Particle Swarm Optimization - Support Vector Machine): Combinação de SVM otimizado por PSO para previsão de descargas.
- SVM (Support Vector Machine): Usado como comparação.
- BPNN (Backpropagation Neural Network): Rede neural convencional para análise comparativa.

## Métricas de performance
- NSE (Nash-Sutcliffe Efficiency)
- RMSE (Root Mean Square Error)
- R² (Coeficiente de Determinação)

## Limitações identificadas
- Generalização limitada: O modelo foi avaliado apenas no Rio Barak; sua aplicabilidade para outras regiões pode requerer ajustes nos parâmetros.
- Dependência de dados históricos: Os resultados dependem da qualidade e disponibilidade de dados hidrológicos e meteorológicos.
- Complexidade computacional: Embora eficiente, a implementação do PSO-SVM é mais complexa que os métodos convencionais.
- Previsões de longo prazo: A eficácia diminui à medida que o intervalo de previsão aumenta, como é comum em modelos baseados em dados.