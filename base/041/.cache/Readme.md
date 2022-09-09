## @041 L3 - Criptografia

![](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/041/cover.jpg)

## Motivação
Yara quer desvendar um enigma, diga-se de passagem é bem enigmático!!!

O enigma consiste em um conjunto de caracteres aparentemente sem sentido, esse enigma so passa a 
fazer sentindo quando processado com uma 'Key' composto por um número inteiro.


O processamento consiste em fazer operações short (^), bit a bit, entre cada caractere do 
enigma e cada digito da 'key', se a quantidade de dígitos da 'key' for menor que a quantidade 
de caracteres do enigma, a 'key' se repete, se a quantidade de caracteres do enigma for menor 
que a quantidade de dígitos da 'key', a 'key' se converte ao tamanho do enigma , desprezando os 
dígitos adicionais. 


### Exemplo :
```
Enigma = nnb!ovofl
Key = 123
```
Ao processar cada caractere do enigma acima com a 'key', temos:
```
n n b ! o v o f l
1 2 3 1 2 3 1 2 3

o l a   m u n d o
```
Perceba que na prática os caracteres serão convertidos para o seu código decimal ASCII.
```
'n' = 110 = 1101110
 1  =  1  = 0000001
            1101111 = 111 = 'o'
```
Ufaaa! Em fim... Ajude Yara nessa missao :)
## Ação

Yara irá procurar a chave pra você. 

Então dada a chave(KEY) e o enigma(E) de Yara retornar o enigma revelado.  

### Entrada:

Um conjunto de caracteres E, representando o enigma. 

1 Inteiro KEY representando a chave do enigma.
 
### Saida:

O enigma revelado.

### Restrições:

1 < E <= 100.

1 < KEY <= 2147483647.
## Exemplos
```
>>>>>>>> Teste 0
nnb!ovofl
123
========
ola mundo
<<<<<<<<

>>>>>>>> Teste 1
Br'tbn+'qhdb'tfeb+'iht'tfebjht
777
========
Eu sei, voce sabe, nos sabemos
<<<<<<<<

>>>>>>>> Teste 2
jsmc*&cs&uis&ucs&vgo
666
========
luke, eu sou seu pai
<<<<<<<<
```
###### @spinosa