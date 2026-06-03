# Parte 1
## Shared Counter
Foi pedido para analisar o código [SharedCounter](SharedCounter.java) disponibilizado no material da aula 27.

O código usa threads para incrementar um mesmo contador ao mesmo tempo com 2 instâncias, cada uma 1000 vezes, tendo que resultar em 2000 no final. Mas isso não acontece 100% das vezes pois algumas vezes as 2 threads tentar incrementar o contador nos exato mesmo tempo e um acaba bloqueando o outro.

Execução sem modificar nada:

![](gif1.gif)

