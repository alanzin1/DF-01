# Sistema de Cálculo de Nível de Herói

Este é um pequeno programa em **Node.js** que permite calcular o nível de um herói com base na quantidade de XP (pontos de experiência) fornecida pelo usuário. O programa utiliza a biblioteca `readline` para interagir com o usuário no terminal.

## Funcionalidade

O sistema solicita o nome e a quantidade de XP do herói, depois calcula o nível do herói de acordo com a quantidade de XP inserida. Os níveis são definidos pelas seguintes faixas de XP:

- **Ferro:** XP < 1000
- **Bronze:** 1001 ≤ XP ≤ 2000
- **Prata:** 2001 ≤ XP ≤ 5000
- **Ouro:** 5001 ≤ XP ≤ 7000
- **Platina:** 7001 ≤ XP ≤ 8000
- **Ascendente:** 8001 ≤ XP ≤ 9000
- **Imortal:** 9001 ≤ XP ≤ 10000
- **Radiante:** XP > 10000
