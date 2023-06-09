# Relógio Digital

Leia do teclado um valor inteiro x, que é o tempo de duração em segundos de um determinado evento, e informe-o expresso no formato: horash:minutosm:segundoss.

## Entrada:

Um único inteiro x.

## Saı́da:

Imprima o tempo lido em segundos, convertido para horash:minutosm:segundoss, conforme exemplos da tabela abaixo.

## Comentários:

Uma das formas de imprimir mais de um valor/variável com textos no print é separá-los por vírgulas. Exemplo:

```python
print(horas, “h:”, minutos, “m:”, tempo, “s”).
```

Nesse caso, seria apresentado na tela: 1 h: 1 m: 1 s (supondo, é claro, que as três variáveis tenham o valor 1). Isso acontece porque os valores/textos do print são separados (separamos valores e textos usando a vírgula) por um espaço em branco, por padrão. Entretanto, é possível mudar o separador padrão para o que quisermos, usando a keyword `sep`:

```python
print(horas, “h:”, minutos, “m:”, tempo, “s”, sep=“”).
```

Nesse caso, seria apresentado na tela: 1h:1m:1s. Outra maneira mais sofisticada de usar variável em um texto que será impresso na tela é:

```python
print(f“{horas}h:{minutos}m:{tempo}s”)
```

### Dica:

Existe um operador "//" em Python que faz a divisão inteira entre dois números e outro operador "%" que calcula o resto de uma divisão inteira. Exemplos: A // B e A % B
