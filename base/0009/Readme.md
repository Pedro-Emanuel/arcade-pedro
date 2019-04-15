## @0009 #4_vet L4 - Segredo do cofre (OBI 2017 F1P1)
## @qxcode

![](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/0009/capa.jpg)

O sistema de segredo para abrir esse cofre é bastante complexo. Ao invés de girar um botão várias vezes, como a gente vê normalmente nos filmes, o dono do cofre tem que deslizar um controle para a esquerda e para a direita, em cima de uma barra, várias vezes, parando em determinadas posições. A barra possui N posições e cada posição contém um número inteiro entre 0 e 9, inclusive. No exemplo da figura, a barra tem 14 posições e o controle está na posição 1.

![](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/0009/cofre.png)

O segredo vai depender de quantas vezes cada um dos dez inteiros entre 0 e 9 vai aparecer dentro do controle. Por exemplo, suponha que o dono deslize o controle da posição inicial 1 até a posição 9, depois para a posição 4, depois para a posição 11 e por fim até a posição 13. Veja que o inteiro 1, por exemplo, vai aparecer seis vezes dentro do controle; e o inteiro 9 vai aparecer quatro vezes.

Dada a sequência de inteiros na barra e a sequência de posições entre as quais o dono desliza o controle, começando da posição inicial 1, seu programa deve contar quantas vezes cada inteiro, entre 0 e 9, vai aparecer dentro do controle.

## Entrada

A primeira linha da entrada contém dois inteiros N e M, representando o número de posições na barra do cofre e o número de posições na sequência que o dono vai seguir para deslizar o controle. A segunda linha contém N inteiros entre 0 e 9, definindo a barra do cofre. A terceira linha contém M inteiros representando a sequência de posições que o dono vai seguir. A primeira posição nessa sequência é sempre 1 e não há duas posições consecutivas iguais.

## Saída

Seu programa deve imprimir uma linha contendo 10 inteiros, representando o número de vezes que cada inteiro, entre 0 e 9, vai aparecer no controle da barra.

## Restrições

*   2 ≤ N ≤ 105 e 2 ≤ M ≤ 105

## Informações sobre a pontuação

*   Em um conjunto de testes somando 40 pontos, N ≤ 1000 e M ≤ 1000

## Testes

```
>>>>>>>>
14 5
9 4 3 9 1 2 4 5 1 1 9 7 0 5
1 9 4 11 13
========
1 6 3 1 4 3 0 1 0 4
<<<<<<<<


>>>>>>>>
5 4
5 8 0 5 1
1 4 2 5
========
3 1 0 0 0 3 0 0 2 0
<<<<<<<<


>>>>>>>>
10 10
6 6 7 7 2 8 9 2 0 0
1 10 3 9 6 9 8 1 8 2
========
5 0 13 0 0 0 6 11 7 8
<<<<<<<<


>>>>>>>>
10 10
8 2 5 6 8 0 0 7 3 3
1 9 7 2 4 2 9 10 9 6
========
8 0 3 4 0 5 4 4 4 0
<<<<<<<<
```