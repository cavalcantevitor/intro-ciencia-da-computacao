# Disciplina: notas

Faça um programa para ler 3 notas, e o número de faltas obtidas no semestre de cada um dos n alunos de uma disciplina. O valor de n (quantidade de alunos) deve ser informado pelo usuário. Calcular a nota final de cada aluno (dada pela média aritmética das 3 notas), e imprimir essa nota final com uma mensagem dizendo a situação final do aluno, ou seja, se o aluno foi “Aprovado”, ficou de “Exame” ou “Reprovado”:

O aluno está Aprovado quando a sua nota final for maior ou igual a 5 E o número de faltas for menor ou igual a 16;
O aluno fica de Exame quando a sua nota final estiver entre 3 e 5 E o número de faltas for menor ou igual a 16;
O aluno está Reprovado se a nota final for menor ou igual a 3 OU o número de faltas for maior que 16.

O programa também deve calcular e apresentar a média aritmética das notas da disciplina e a quantidade de alunos aprovados.

## Entrada:

Na primeira linha, um número inteiro n que é o número de alunos na turma, n > 0.

Na segunda linha, uma sequência de 3 valores reais e 1 valor inteiro, que são as 3 notas dos alunos e quantidade de faltas, respectivamente.

Considere que as entradas sempre serão válidas, ou seja, não é necessário fazer validação das entradas.

## Saída:

Para cada aluno o programa deve imprimir, em uma única linha com separação por espaço, a média aritmética do aluno e, na sequência, sua situação (Aprovado, Exame ou Reprovado). A média deve ser impressa com 1 casa decimal após a vírgula.

No final, o programa deve imprimir, em uma única linha com separação por espaço, primeiro a média da turma (com 1 casa decimal) e depois a quantidade de alunos aprovados. Caso nenhum aluno seja aprovado, apresente o valor 0 (zero).
