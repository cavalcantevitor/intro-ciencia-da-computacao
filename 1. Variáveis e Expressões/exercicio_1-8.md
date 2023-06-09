# Distância e Números Complexos

Leia quatro valores correspondentes aos eixos x e y de dois pontos quaisquer no plano: (x1, y1) e (x2, y2)
e calcule a distância entre eles, mostrando 4 casas decimais após a vírgula, segundo a fórmula:
((x2 − x1)^2 + (y2 − y1)^2)^1/2

Leia também um número complexo z = a + bj e calcule seu módulo |z| (distância até a origem), mostrando 4 casas decimais após a vírgula, usando a fórmula:
|z| = ((a^2 + b^2 ))^1/2

Note que Python possui complex como tipo de dados. Um número complexo tem um componente real e um componente imaginário, ambos representados pelo tipo float em Python (é possível acessá-los separadamente).

## Entrada:

A entrada contém três linhas de dados. A primeira linha contém dois valores de ponto flutuante x1 e y1 , a segunda também contém dois valores de ponto flutuante x2 e y2 e a terceira contém um número complexo no formato a + bj.

## Saída:

Calcule e imprima o valor da distância e do módulo segundo as fórmulas fornecidas, com 4 casas decimais.

## Comentários:

Para ler vários valores em uma mesma linha, use input().split(). Se o argumento de split for vazio, o separador das variáveis é um espaço em branco. Porém, lembre-se que input lê apenas strings do teclado, portanto você deverá converter as strings em floats.
No exemplo a seguir, o usuário digita valores separados por um espaço em branco e aperta enter para enviá-los, então, o programa lê esses valores separados por espaços como strings (na ordem em que aparecem), guardados nas variáveis correspondentes. Em seguida, o programa os converte para floats:

```python
A, B, C = input().split()
A, B, C = [float(A), float(B), float(C)]
```

Números complexos podem ser manipulados facilmente com o método complex(). Exemplo:

```python
D = complex('2+3j')
print('%.2f' % D.real)
print('%.2f' % D.imag)
```

### Dica:

O módulo math pode ser usado para calcular a raiz quadrada com a função math.sqrt(A). Neste caso, a biblioteca precisa ser importada antes: import math.

Existe um operador "**" em Python que faz a exponenciação. Exemplo: A ** B = AB
