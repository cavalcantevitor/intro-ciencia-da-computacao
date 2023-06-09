# Combustível

Efetuar o cálculo da quantidade de litros de combustível (gasolina) gastos em uma viagem, sabendo-se que o carro faz 14.2 km com um litro (na estrada). Deverão ser lidos o tempo gasto na viagem e a velocidade média. Utilizar as seguintes fórmulas:

distancia = tempo x velocidade

litros = distancia / 14.2

## Entrada:

Duas entradas com valores reais, um por linha. O primeiro valor é o tempo gasto na viagem (em horas) e o segundo valor é a velocidade média (km/h).

## Saída:

O programa deverá apresentar os valores da distância percorrida e a quantidade de litros utilizados na viagem. Observe que as saídas são números reais e apenas a quantidade de litros deve ser formatada com duas casas decimais, ou seja, a distância percorrida não deve ser formatada, conforme os exemplos a seguir. Os valores são apresentados na mesma linha e separados por espaço.

### Dica:

Um exemplo de como imprimir valores em uma mesma linha e sem e com formatação de casas decimais. Nesse exemplo a fomatação é de 1 casa decimal:

```python
print("{} {:.1f}".format(A,B))
```

Note que a impressão de valor não formatado pode variar entre as diferentes estruturas do print(), logo, os resultados podem divergir. Ainda, alguns interpretadores Python utilizam aspas simples e não duplas.
