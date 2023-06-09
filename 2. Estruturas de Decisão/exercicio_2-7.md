# Índice de Massa Corporal

Usando como dados de entrada altura h (em metros) e peso p (em quilos), elabore um programa que calcule o IMC (índice de massa corporal) do usuário, usando a fórmula:

`IMC = p/h2`

Depois interprete e informe o resultado, da seguinte forma:

- Baixo peso: IMC abaixo de 18,5 kg/m2
- Peso normal: IMC entre 18,5 (inclusive) e 24,9 (inclusive) kg/m2
- Sobrepeso: IMC entre 24,9 e 29,9 (inclusive) kg/m2
- Obesidade grau I: IMC entre 29,9 e 34,9 (inclusive) kg/m2
- Obesidade grau II: IMC entre 34,9 e 39,9 (inclusive) kg/m2
- Obesidade grau III: IMC maior que 39,9 kg/m2

Caso ele esteja acima da faixa de peso normal informe também o mínimo de quilos que serão necessários perder para chegar à faixa peso normal (24,9). Para isso basta subtrair do peso o mínimo de quilos que serão necessários perder `(peso_normal_máximo * altura * altura)`.

## Entrada:

Duas linhas de dados: peso (em kg) e altura (em metros).

## Saída:

Caso o usuário esteja na faixa Baixo peso ou Peso normal apenas imprima a mensagem informando o IMC e, na próxima linha, a sua classificação correspondente usando a tabela, conforme exemplo fornecido abaixo. Caso contrário, imprima também o peso mínimo necessário a se perder para chegar à faixa peso normal com 2 casas decimais após a vírgula.
