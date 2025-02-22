# Rede Neural usando Somente Matemática

## Descrição
Este projeto implementa uma rede neural utilizando apenas conceitos matemáticos, sem o uso de bibliotecas de machine learning como TensorFlow ou PyTorch. O objetivo é oferecer uma compreensão aprofundada de como as redes neurais funcionam internamente, desde a inicialização dos pesos até o treinamento e inferência.

O projeto utiliza apenas a biblioteca NumPy para manipulação de matrizes e vetores, garantindo que todos os cálculos sejam realizados manualmente.

## Estrutura do Projeto
- `Rede_neural_matematica.ipynb`: Notebook principal contendo toda a implementação passo a passo.
- `README.md`: Este arquivo, com a descrição detalhada do projeto.

## Conceitos Abordados
Este projeto passa por todas as etapas necessárias para a construção de uma rede neural do zero, incluindo:

### 1. Inicialização dos Pesos e Biases
- Os pesos da rede são inicializados aleatoriamente para garantir aprendizado eficiente.
- Os biases são inicializados para evitar valores nulos.

### 2. Forward Propagation
- Cálculo da ativação de cada camada da rede neural.
- Utilização de funções de ativação como Sigmoid e ReLU.

### 3. Cálculo da Função de Perda
- Mede o erro entre a saída predita e a saída real.
- Exemplos: Erro Quadrático Médio (MSE) e Entropia Cruzada.

### 4. Backpropagation
- Cálculo do gradiente da função de perda em relação aos pesos.
- Propagação reversa dos erros até as camadas iniciais.

### 5. Atualização dos Pesos
- Utilização do algoritmo de gradiente descendente para ajustar os pesos.
- Ajuste dos parâmetros com base na taxa de aprendizado.

### 6. Treinamento e Avaliação
- Divisão do dataset em treino e teste.
- Treinamento iterativo até a convergência.
- Avaliação do desempenho da rede em dados não vistos.

## Requisitos
Para executar este projeto, você precisa ter instalado:
- Python 3.x
- NumPy
- Jupyter Notebook (opcional, para execução interativa)

## Como Executar
1. Clone o repositório:
   ```sh
   git clone https://github.com/Jeferson13oli/Rede_neural_Matematica.git
   cd Rede_neural_Matematica
   ```
2. Instale as dependências necessárias:
   ```sh
   pip install numpy
   ```
3. Execute o notebook `Rede_neural_matematica.ipynb` para visualizar a implementação passo a passo:
   ```sh
   jupyter notebook Rede_neural_matematica.ipynb
   ```

## Observação
Este projeto é voltado para fins educacionais, ajudando na compreensão teórica de redes neurais sem depender de frameworks de alto nível.

## Autor
Desenvolvido por Jeferson13oli. Para mais informações, consulte o repositório oficial.
