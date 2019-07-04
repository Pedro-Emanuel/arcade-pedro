## @0156 #02_sel L1 - OBI 2016 - Fase1 - Nível 1 - Jogo de par ou ímpar
## @qxcode
# @qxcode

![](capa.jpg)

Dois amigos, Alice e Bob, estão jogando um jogo muito simples, em que um deles grita ou "par" ou "ímpar" e o outro imediatamente responde ao contrário, respectivamente "ímpar" ou "par". Em seguida, ambos exibem ao mesmo tempo uma mão cada um, em que alguns dedos estão estendidos e outros dobrados. Então eles contam o número total de dedos estendidos. Se a soma for par, quem gritou "par" ganha. Se a soma for ímpar, quem gritou "ímpar" ganha. Por exemplo, suponhamos que a Alice gritou "par" e o Bob respondeu "ímpar". Em seguida, Alice não deixou nenhum dos seus dedos estendidos, ao passo que Bob deixou três dedos estendidos. A soma então é três, que é ímpar, portanto Bob ganhou. Seu programa deve determinar quem ganhou, tendo a informação de quem gritou par e o número de dedos estendidos de cada um.

### Entrada

A entrada contém três linhas, cada uma com um número inteiro, P, D\_1 e D\_2, nesta ordem. Se P = 0 então Alice gritou "par", ao passo que se P=1 então Bob gritou "par". Os números D\_1 e D\_2 indicam, respectivamente, o número de dedos estendidos da Alice e do Bob.

### Saída

Seu programa deverá imprimir uma única linha, contendo um único número inteiro, que deve ser 0 se Alice foi a ganhadora, ou 1 se Bob foi o ganhador.

### Restrições

*   P = 0 ou P = 1
*   0 ≤ D\_1 ≤ 5
*   0 ≤ D\_2 ≤ 5

### Exemplos

```
>>>>>>>>
0
0
3
========
1
<<<<<<<<

>>>>>>>>
1
0
3
========
0
<<<<<<<<

>>>>>>>>
0
1
5
========
0
<<<<<<<<
```

<!---
>>>>>>>> 01
0
1
5
========
0
<<<<<<<<


>>>>>>>> 02
0
0
3
========
1
<<<<<<<<


>>>>>>>> 03
0
5
0
========
1
<<<<<<<<


>>>>>>>> 04
1
4
5
========
0
<<<<<<<<


>>>>>>>> 05
1
0
3
========
0
<<<<<<<<


>>>>>>>> 06
0
3
2
========
1
<<<<<<<<


>>>>>>>> 07
0
0
2
========
0
<<<<<<<<


>>>>>>>> 08
1
3
3
========
1
<<<<<<<<


>>>>>>>> 09
1
0
5
========
0
<<<<<<<<


>>>>>>>> 10
0
0
4
========
0
<<<<<<<<


>>>>>>>> 11
0
3
1
========
0
<<<<<<<<


>>>>>>>> 12
0
2
4
========
0
<<<<<<<<


>>>>>>>> 13
1
0
1
========
0
<<<<<<<<


>>>>>>>> 14
0
3
4
========
1
<<<<<<<<


>>>>>>>> 15
0
1
4
========
1
<<<<<<<<


>>>>>>>> 16
0
4
5
========
1
<<<<<<<<
--->