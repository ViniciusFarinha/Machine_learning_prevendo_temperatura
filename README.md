
# Machine_learning_prevendo_temperatura
Projeto de machine learning que, com input de termperaturas em C° e outputs de temperatura em Fº, a máquina aprende a fórmula de conversão e nos retorna a equação.

### Bibliotecas utilizadas
* TensorFlow - para aprendizado de máquina
* Numpy - para transformar as variáveis em arrays
* Matplotlib - para visualização do gráfico do erro diminuindo ao longo dos epochs

### Metodologia

* Criação das variáveis de input e output (Celsius e Fahrenheit);
* Criação dos layers
* Sequential
* Compilação do modelo
* Treinamento do modelo
* Plotar gráfico do treinamento do modelo
* Predição
* Função layer.get_weights() para ver quais os coeficientes do gráfico.

### Embasamento teórico

Se você nao faltou a nenhuma aula de física quando esteve no colégio, provavelmente sabe transformar qualquer temperatura de celsius pra Fahrenheit.
Você sabe fazer isso porque sabe a fórmula de conversão: Fº = (Cº*1,8) + 32.

Porém, se eu te desse só os valores iniciais e finais (Celsius e Fahrenreit) e te pedisse pra transformar um valor de 100C° em Fahrenheit, você saberia?

O aprendizado de máquina permite que os dados sejam estudados de tal forma que a máquina aprende qual foi o caminho que um input fez para se tornar o output.
Lógico que, se tratando de um exemplo simples e conhecido, as coisas se tornam mais fáceis. Porém, o objetivo aqui é mostrar que caso os dados possuam uma correlação forte como os deste exemplo, é possível predizer diversas coisas sobre o mundo
