# Duplas de Inteiros

Faça um algoritmo para ler um valor inteiro T, um valor A e um valor N. Leia T vezes valores inteiros A e N e imprima cada um dos N números consecutivos a partir de A, incluindo o A. Imprima também a soma dos N números a partir de A (inclusive), para cada um dos valores A e N lidos.

## Entrada:

A entrada contém somente valores inteiros, sendo T >= 0 e N > 0. Na primeira linha será lido o valor T e nas próximas T linhas serão lidos os valores de A e N, separados por espaço.

## Saída:

Escreva na tela, para cada dupla de A e N lidos, cada um dos N números a partir de A, separados por espaço. Logo em seguida imprima X, onde X representa a soma dos N números a partir de A, conforme exemplo de saída. Não deve haver espaços em branco após o último valor de cada linha.

## Comentários:

Lembre-se que para ler vários valores em uma mesma linha, use input().split(). Se o argumento de split for vazio, o separador das variáveis é um espaço em branco. Porém, input() lê apenas strings do teclado, portanto você deverá converter as strings em floats. No exemplo a seguir, o usuário digita valores separados por um espaço em branco e aperta enter para enviá-los, então, o programa lê esses valores separados por espaços como strings (na ordem em que aparecem), guardados nas variáveis correspondentes e os converte para inteiros:

A, B = input().split()
A, B = [int(A), int(B)]

O comandp print() tem diversos parâmetros opcionais, entre eles 'end' através do qual podemos especificar o que deverá ser impresso ao final de uma linha. Podemos assim alterar o default line feed e usar, por exemplo, um espaço em branco com o parâmetro end= " ".
