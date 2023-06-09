# Fatorial e Fibonacci

No ocidente, a sequência de Fibonacci apareceu pela primeira vez no livro Liber Abaci (1202) de Leonardo Fibonacci embora ela já tivesse sido descrita por gregos e indianos. Fibonacci considerou o crescimento de uma população idealizada (não realista biologicamente) de coelhos. Os números descrevem a quantidade de casais na população de coelhos depois de n meses se for suposto que:

i) no primeiro mês nasce apenas um casal;

ii) casais amadurecem sexualmente (e reproduzem-se) apenas após o segundo mês de vida;

iii) não há problemas genéticos no cruzamento consaguíneo;

iv) todos os meses, cada casal fértil dá a luz a um novo casal; e

v) os coelhos nunca morrem.

Sendo Fn a quantidade de casais após n meses, faça um programa que, dado um inteiro positivo n digitado pelo usuário, calcule o n-ésimo termo da sequência de Fibonacci usando a definição dada abaixo:

Fn = 1 ; n = 1 ou n = 2;

Fn = Fn - 1 + Fn - 2 ; n > 2

Imprima também o fatorial de n.

Caso haja um número par de casais de coelhos após n meses, imprima também quantos novos casais de coelhos vão nascer no próximo mês.

## Entrada:

Inteiro n > 0, onde n representa os meses que passaram.

# Saída:

Será impresso na tela o número de casais após n meses e o valor de n! na mesma linha.

Caso o número de casais de coelhos seja par, será impresso também, na mesma linha, quantos novos casais irão nascer no próximo mês.
