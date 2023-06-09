# Ímpares Consecutivos

Leia um valor inteiro N que especifica a quantidade de casos de teste que vem a seguir. Cada caso de teste consiste de dois inteiros, X e Y. Você deve apresentar a soma de Y ímpares consecutivos a partir de X, inclusive o próprio X se ele for ímpar. Por exemplo: para a entrada 4 5, a saída deve ser 45, que é equivalente a: 5 + 7 + 9 + 11 + 13, para a entrada 7 4, a saída deve ser 40, que é equivalente a: 7 + 9 + 11 + 13. No final, imprima também a maior e a menor soma entre todos os casos de teste, e a média destas duas últimas somas (a maior e a menor).

## Entrada:

A primeira linha de entrada é um inteiro N > 0 que é a quantidade de casos de teste que vem a seguir. Cada caso de teste consiste em uma linha contendo dois inteiros X e Y, onde Y > 0.

## Saída:

Imprima a soma S dos Y consecutivos números ímpares a partir do valor X, para cada X e Y lidos. Imprima também a maior e a menor soma S. No final, imprima a média da maior e da menor soma com duas casas decimais após a vírgula, conforme exemplo abaixo.

## Comentário:

As variáveis que serão usadas para armazenar a maior e a menor soma devem ser inicializadas antes das comparações. Uma maneira é considerar a primeira soma como um valor inicial para as variáveis que representam a maior e a menor soma.

### Dica:

Este exercício pode ser resolvido com as estruturas for ou while. No caso da estrutura for, o Python possui o comando range( ), que fornece uma sequência de valores à variável do loop for. O comando range( ) tem parâmetros opcionais, como informar o valor inicial (inicio) da sequência e o passo da sequência (salto), range(inicio,fim,salto). O parâmetro fim indica a quantidade de valores da sequência. Exemplo: range(4) - a sequência será 0, 1, 2, 3; range(2,5) - a sequência será 2, 3, 4; e range(1,6,2) - a sequência será 1, 3, 5.
