# Empresa: reajuste salarial

Uma empresa aplicará um reajuste salarial a todos os seus funcionários baseado no cargo ocupado e no tempo de serviço, conforme as especificações a seguir:

| Cargo      | >= 3 anos | 3 > e < 6 anos | >= 6 anos |
| ---------- | --------- | -------------- | --------- |
| Gerente    | 12%       | 13%            | 15%       |
| Engenheiro | 7%        | 11%            | 14%       |
| Outros     | 5%        | 5%             | 5%        |

Faça um programa que receba como entrada o cargo, o tempo de serviço e o salário atual de um funcionário, em seguida, calcula e imprime o reajuste concedido e o salário reajustado. O salário atual não pode ser inferior ao salário mínimo, ou seja, R$ 1039,00, caso isso ocorra, a mensagem “Salário inválido!” deve ser impressa na tela e o programa deve ser encerrado.

## Entrada:

O primeiro valor é uma string e indica o cargo do funcionário. O segundo valor, que é um número inteiro, indica o tempo de serviço do funcionário. O terceiro valor, que é um número real, representa o salário atual do funcionário. Considere que o tempo de serviço sempre será um número válido, não é necessário validar. Os valores devem ser lidos um por linha.

## Saída:

Dois valores reais, apresentados um por linha. O primeiro valor é o reajuste que será concedido e o segundo é o salário já reajustado. Observe que os valores de reajuste e salário reajustado são impressos com duas casas decimais de precisão.
