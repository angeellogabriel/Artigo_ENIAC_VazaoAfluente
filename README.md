# Artigo_ENIAC_VazaoAfluente
Este repositório contém o código e os dados utilizados no artigo submetido ao ENIAC, que aborda a análise e previsão de vazão afluente em sistemas hidrológicos.
O foco principal é no desenvolvimento de técnicas baseadas em redes neurais para melhorar a precisão das previsões de vazão afluente, utilizando séries temporais hidrológicas.

# Modelos Utilizados
LSTM (Long Short-Term Memory): Redes neurais recorrentes para capturar dependências temporais de longo prazo nas séries temporais de vazão.
CNN (Convolutional Neural Network): Redes neurais convolucionais para extrair características relevantes de padrões locais nas séries temporais.
Modelo Híbrido CNN-LSTM: Combinação das arquiteturas CNN e LSTM para aproveitar o melhor de ambos os modelos, extraindo características locais e temporais de forma eficiente.

data/: Conjunto de dados utilizados no projeto.

dados_vazao.xlsx: Arquivo principal de séries temporais de vazão afluente.

notebooks/: Notebook Jupyter com experimentos exploratórios e análises.
