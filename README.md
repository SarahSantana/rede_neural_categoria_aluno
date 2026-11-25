# rede_neural_categoria_aluno

Criei uma rede neural sequencial com duas camadas principais:
1. Camada Oculta:
- Input shape: 7 (um para cada atributo).
- 80 neurônios: escolhidos empiricamente para aumentar a capacidade de aprendizado mesmo com poucos
dados.
- Função de ativação: ReLU (Rectified Linear Unit), que permite que apenas valores positivos passem
adiante.
2. Camada de Saída:
- 3 neurônios: um para cada categoria.
- Função de ativação: Softmax, que transforma os valores de saída em probabilidades normalizadas.
Essa arquitetura simples é suficiente para demonstrar os conceitos fundamentais do treinamento de modelos.
