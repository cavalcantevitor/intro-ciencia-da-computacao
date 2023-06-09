# A Hipótese Falsa

Raphael e Renata estão cursando Teoria dos Números juntos. Certo dia eles se deparam com a seguinte hipótese: "Para todo inteiro positivo n e m temos que n⋅
m + 1 é um número primo". Porém, eles percebem que essa hipótese é falsa, pois a Renata rapidamente nota que basta usar m = n - 2, assim:

nm + 1 = n(n - 2) + 1 = (n -1)^2

que não é primo.

De modo que para n > 2, m pode ser n - 2, e ainda inteiro positivo, e o resultado da hipótese não é primo. Por exemplo, se n = 7, então 7⋅
5 + 1 = 36. Para n <= 2, podemos usar m = n + 2 como outro contra-exemplo. Entretanto, Raphael quer impressionar a Renata apresentando não apenas qualquer contra-exemplo, mas sim o menor m tal que n⋅
m + 1 não seja primo para um dado n (por exemplo, para n = 7, poderíamos usar m = 1).

Você pode escrever um programa para ajudá-lo, dado o inteiro n?

## Entrada:

A entrada é o inteiro n (1 <= n <= 1000) da hipótese.

## Saída:

Imprima na tela o menor m >= 1 tal que n⋅
m + 1 não seja um número primo. É garantido que esse m existe.

### Comentários:

Para o primeiro exemplo abaixo, 3⋅
1 + 1 = 4, a saída será 1.

Para o segundo exemplo, 4 \* 1 + 1 = 5, nós não podemos imprimir 1 porque 5 é primo. Porém, sim m = 2 pois 4⋅
2 + 1 = 9, que não é primo.

Para o terceiro exemplo, 10⋅
2 + 1 = 21, imprimimos 2.

Lembre-se que um número primo possui apenas 1 e o próprio número como divisores. Outro divisor resultará em um resto diferente de zero.
