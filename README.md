## Calculadora Básica em Python
# Descrição
Este repositório contém um programa simples em Python que simula uma calculadora. O programa permite que o usuário escolha entre diferentes operações matemáticas (soma, subtração, multiplicação, divisão, e potência) e então insira dois números para realizar a operação desejada. O código utiliza a estrutura de controle match (introduzida no Python 3.10) para definir o comportamento da calculadora baseado na escolha do usuário.

# Funcionalidades
O programa oferece as seguintes operações matemáticas:

* Soma: Adiciona dois números.
* Subtração: Subtrai o segundo número do primeiro.
* Multiplicação: Multiplica dois números.
* Divisão: Divide o primeiro número pelo segundo (com tratamento para divisão por zero).
* Potência: Calcula a potência de um número, elevando o primeiro número à potência do segundo.
  
# Funcionamento do Código
O usuário é solicitado a escolher qual operação deseja realizar. Essa escolha é feita através de um input(), onde o usuário pode digitar o nome da operação (por exemplo, "soma", "subtração", "multiplicar", etc.).

O programa utiliza o comando match para verificar qual operação o usuário escolheu. Com base nessa escolha, o programa realiza a seguinte lógica:

Para soma, subtração, multiplicação e divisão, o programa pede dois números ao usuário, usando input() para coletar a entrada e convertendo os valores para o tipo float.
Para potência, o programa também pede dois números, mas converte ambos para o tipo int, já que estamos lidando com números inteiros para a base e o expoente.
Tratamento de erros:

No caso da operação de divisão, o programa inclui uma verificação para garantir que o divisor não seja zero, pois isso geraria um erro de "divisão por zero". Se o divisor for zero, uma mensagem de erro apropriada é exibida.
Se o usuário inserir uma operação que não esteja listada, o programa cai no caso padrão (case _:) e exibe uma mensagem indicando que a operação é inválida.

