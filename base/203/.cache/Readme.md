## @203 L1 - Cláusulas de guarda

![](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/203/cover.jpg)

Essa questão foi extraída do seguinte vídeo. O objetivo é simplificar testes de if else pensando nas negações.

Para fazer acessar a informação desejada você precisa estar conectado no wifi, fazer login e acessar como admin. Caso qualquer dessas operações não seja verdadeira, você deve emitir uma mensagem de erro exatamente nessa ordem. Caso todas sejam corretas avise que houve sucesso.

Entrada: 
    - valor bool de wifi, login e admin
    - saída:
        - se wifi for false: you must connect to wifi
        - se login for false: you need to login first
        - se admin for false: you neet to login as admin
        - caso todos sejam verdadeiros: done

Dica: ao invés de múltiplos if elses aninhados, verifique as negações. 
```c
if (!wifi) {

}
if (!login) {

}
```


### tests
```
>>>>>>>>
0
0
0
========
you must connect to wifi
<<<<<<<<

>>>>>>>>
0
1
1
========
you must connect to wifi
<<<<<<<<

>>>>>>>>
0
0
1
========
you must connect to wifi
<<<<<<<<

>>>>>>>>
1
0
1
========
you need to login first
<<<<<<<<

>>>>>>>>
1
0
0
========
you need to login first
<<<<<<<<

>>>>>>>>
1
1
0
========
you must to login as admin
<<<<<<<<


>>>>>>>>
1
1
1
========
done
<<<<<<<<

```