# undergraduate_thesis

Repositório para o Trabalho de Conclusão de Curso para a obtenção do Bacharelado em Ciência da Computação na Universidade Federal de São Paulo (UNIFESP) com o tema **"Preditor de baixo custo para alagamentos utilizando pluviômetros e redes sociais"**.

## Estrutura
### bibliography
Contém a bibliografia em relação a modelos de aprendizado de máquina em desastres hidrológicos

### data
Dados utilizados para elaboração dos conjuntos de treino e validação. Entre esses dados estão:
- Dados pluviométricos do Centro Nacional de Monitoramento e Alertas de Desastres Naturais (CEMADEN) do primeiro trimestre de 2019.
- Alagamentos na cidade de São Paulo na região dos pluviômetros do CEMADEN, disponíveis no site do Centro de Gerenciamento de Emergências Climáticas (CGE).
- Tweets extraídos por Hossaki et al. (2023) na região dos pluviômetros.

### models
Todos os modelos criados na elaboração deste trabalho, podem ser importados para reprodução dos resultados. Contém 6 modelos MLP e 11 modelos LSTM.

### Notebooks
Localizados na raiz do projeto, estão separados em três arquivos:
1. project.ipynb: Contém as etapas de filtragem e tratamento dos dados. Cria o dataset contendo a série temporal que foi utilizada no treinamento e validação dos modelos.
2. mlp.ipynb: Criação e exportação de todos os modelos MLP. Ao final do notebook, há uma seção onde esses modelos são importados e são calculadas suas métricas de avaliação.
3. LSTM.ipynb: Criação e exportação de todos os modelos LSTM. Contém testes para diferentes parâmetros do modelo. Possui uma seção de métricas ao final do notebook.
