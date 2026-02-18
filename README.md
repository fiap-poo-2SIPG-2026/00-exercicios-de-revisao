# Exercícios de Revisão

1. Considere o seguinte algoritmo escrito em pseudolinguagem.  
    input n  
    print n  
    if n = 1 then STOP  
    if n é ímpar then n ← 3n + 1  
    else n ← n/2  
    GOTO 2 

Considerando que a entrada seja o número 22, a seguinte sequência será impressa no vídeo:  
22  11  34  17  52  26  13  40  20  10  5  16  8  4  2  1  
Escreva um programa em Java para implementar o problema descrito.  

2. Reescreva o programa do exercício 1 para ler dois valores inteiros i e j. O seu programa deverá imprimir no vídeo qual é o número máximo (total) de impressões que serão realizadas no terminal para todos os inteiros entre i e j (incluindo i e j). Veja na tabela abaixo alguns exemplos para você testar o seu programa.

 i   | j   | Valor máximo de impressões   | Significado 
:---:|:---:|:----------------------------:|:----------------------------------------:   
1    |10   | 20                           | Serão impressos no terminal 20 números  
100  |200  | 125                          | Serão impressos no terminal 125 números 
201  |210  |89                            | Serão impressos no terminal 89 números 
