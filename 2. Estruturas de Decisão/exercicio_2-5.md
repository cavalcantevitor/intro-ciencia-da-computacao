# A Mais Longa Subsequência Incomum

Uma subsequência de uma string é uma sequência de caracteres que aparece na mesma ordem da string. As ocorrências não precisam ser consecutivas, por exemplo, "ac", "bc", "abc" e "a" são subsequências da string "abc", enquanto as strings "abbc" e "acb" não são. A string vazia é subsequência de qualquer string. Qualquer string é subsequência dela mesmo.

A maior subsequência incomum entre duas strings é a maior string que é subsequência de uma das duas e não é subsequência da outra.

Dada duas strings x e y, encontre o tamanho da maior subsequência incomum.

## Entrada:

A primeira linha contém a string x e a segunda linha contém a string y. As duas strings não são vazias e são compostas apenas por letras minúsculas.

## Saída:

Se não houver nenhuma subsequência incomum, imprima "-1". Caso contrário imprima o tamanho da maior subsequência incomum de a e b.

## Comentários:

A maior subsequência de uma string é ela mesma. No primeiro exemplo abaixo "abcd" e "defgh" são as maiores subsequências das strings de entrada, "abcd" e "defgh", respectivamente. Essas duas maiores subsequências são incomuns, ou seja, diferentes? Nesse caso, imprima o tamanho da maior. Caso contrário, imprima "-1".

## Dica:

Existe uma função em Python que retorna o tamanho de uma string qualquer dada como parâmetro. Exemplo: `len(A)`
