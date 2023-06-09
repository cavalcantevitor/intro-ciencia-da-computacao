# Rally

Uma competição de rally consiste de dois trechos que devem ser percorridos a velocidades médias distintas. Ganha a equipe que perder menos pontos durante os trechos. Pontos são descontados por passar atrasado ou adiantado pelos Postos de Controle (PC) e por ultrapassar limite máximo de velocidade conforme descrito a seguir.

O trecho 1 tem que ser percorrido em 30 minutos. No final do trecho existe um PC que registra o tempo da equipe. Cada segundo a mais (atraso) do tempo ideal a equipe perde 1 ponto e cada segundo a menos (adiantado) a equipe perde 2 pontos. A velocidade máxima no trecho é de 60 Km/h. Se a equipe passar por um radar com velocidade acima de 60 Km/h, para cada Km/h acima do permitido é descontado 10 pontos.

O trecho 2 tem que ser percorrido em 60 minutos. Da mesma forma que no trecho 1, existe um PC no final do trecho 2 que registra o tempo da equipe. Cada segundo a mais (atraso) do tempo ideal a equipe perde 1 ponto e cada segundo a menos (adiantado) a equipe perde 2 pontos. A velocidade máxima no trecho é de 40 Km/h. Se a equipe passar por um radar com velocidade acima de 40 Km/h, para cada Km/h acima do permitido é descontado 20 pontos.

A equipe que não conseguir cumprir um trecho perde mais 1000 pontos para cada trecho, além das penalidades já descritas. Neste caso, o tempo registrado pela equipe no trecho não cumprido é zero.

Faça um programa que leia o tempo que a equipe levou para percorrer o trecho 1, a velocidade com que passou pelo radar do trecho 1, o tempo que a equipe levou para percorrer o trecho 2 e a velocidade com que passou pelo radar do trecho 2. Calcule os pontos perdidos da equipe no trecho1 sem levar em conta a velocidade máxima, no trecho1 levando em conta a velocidade máxima, no trecho 2 sem levar em conta a velocidade máxima e no trecho 2 levando em conta a velocidade máxima. Calcule também a pontuação total (perdida) da equipe sem levar em conta a velocidade máxima e levando em conta a velocidade máxima.

## Entrada:

Quatro valores inteiros, em uma linha e separados por espaços, nessa ordem: o tempo que a equipe levou para percorrer o trecho 1 em segundos, a velocidade com que passou pelo radar do trecho 1 em Km/h, o tempo que a equipe levou para percorrer o trecho 2 em segundos e a velocidade com que passou pelo radar do trecho 2 em Km/h.

## Saída:

Seis inteiros um por linha, com os pontos (perdidos) da equipe:

- no trecho 1 sem levar em conta a velocidade máxima,
- no trecho 1 levando em conta a velocidade máxima,
- no trecho 2 sem levar em conta a velocidade máxima,
- no trecho 2 levando em conta a velocidade máxima,
- a pontuação total da equipe sem levar em conta a velocidade máxima, e
- a pontuação total da equipe levando em conta a velocidade máxima.
