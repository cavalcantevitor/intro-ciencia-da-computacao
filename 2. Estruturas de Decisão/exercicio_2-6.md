# Calendário

Raphael quer fazer um calendário para o mês atual. Para isso, ele desenha um tabela aonde as colunas correspondem às semanas (uma semana são 7 dias consecutivos de segunda até domingo), linhas correspondem aos dias da semana, e as células contém datas. Por exemplo, o calendário para Janeiro de 2017 seria como na tabela abaixo:

|     |     |     |     |     |     |
| :-: | :-: | :-: | :-: | :-: | :-: |
|  -  |  2  |  9  | 16  | 23  | 30  |
|  -  |  3  | 10  | 17  | 24  | 31  |
|  -  |  4  | 11  | 18  | 25  |  -  |
|  -  |  5  | 12  | 19  | 26  |  -  |
|  -  |  6  | 13  | 20  | 27  |  -  |
|  -  |  7  | 14  | 21  | 28  |  -  |
|  1  |  8  | 15  | 22  | 29  |  -  |

Raphael quer saber quantas colunas sua tabela deve ter, dado o mês e o dia da semana do primeiro dia do mês. Você pode fazer um programa para ajudá-lo, assumindo que o ano não é bissexto?

## Entrada:

A entrada consiste de uma única linha contendo dois inteiros m e d `(1 ≤ m ≤ 12, 1 ≤ d ≤ 7)`. O inteiro m é o número do mês (de janeiro à dezembro) e o inteiro d é o dia da semana do primeiro dia do mês (1 é segunda, 2 terça, até 7 domingo).

## Saída:

Imprima um único inteiro: o número de colunas que a tabela terá. O primeiro exemplo corresponde a janeiro de 2017, mostrado na figura acima.

## Dica:

Analise, caso a caso, cada mês e cada possibilidade de dia de início de semana usando if's encadeados ou aninhados.
