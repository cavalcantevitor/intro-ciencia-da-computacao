# Ghost e a Escada

No caminho para encontrar Jon Snow em Dragonstone, o lobo Ghost enfrenta um problema: uma grande escada. Os degraus da escada são numeradas de 1 até infinito. Sendo um lobo esperto, Ghost decidiu calcular dois valores, o número de degraus percorridos com números pares e ímpares.

Você precisa checar se o número de passos em degraus pares e ímpares encontrados pelo Ghost estão corretos. Considere que ele não pula nenhum degrau e que ele sobe pelo menos o degrau de número 1.

## Entrada:

Em uma única linha são dados dois inteiros `a, b (0 ≤
a,b ≤ 100)`, o número de passos pares e ímpares, respectivamente.

## Saída:

Em uma única linha, imprima "a b ok", se Ghost calculou corretamente os valores e "a b errados" caso contrário.

## Comentários:

Ao começar a contagem de passos com um número ímpar (degrau de número 1) e percorrer os degraus de maneira consecutiva, o número de passos ímpares contados ou é igual ao número de passos pares ou é maior e difere deste por no máximo 1.

Lembre-se que para ler vários valores em uma mesma linha, use `input().split()`. Se o argumento de split for vazio, o separador das variáveis é um espaço em branco. Porém, input lê apenas strings do teclado, portanto você deverá converter as strings em inteiros. No exemplo a seguir, o usuário digita valores separados por um espaço em branco e aperta enter para enviá-los, então, o programa lê esses valores separados por espaços como strings (na ordem em que aparecem), guardados nas variáveis correspondentes e os converte para inteiros:

```
A, B = input().split()
A, B = [int(A), int(B)]
```
