**Princípios de Contagem:** analise combinatória

**1 - Princípio da casa dos pombos:**

Você tem 10 pombos mas tem somente 9 casas, se todos forem dormir, 2 pombos vão ficar na mesma casa.

**EX:** Mostre que há, no máximo 6 algarismos na dizima periódica de 1/7.

Dizima: depois da vírgula, pode ter blocos de algarismos que se repetem.

**10**00000    |     7                      

 7                   0, 142857             

**3**0                                                 

-28                                                

**2**0                                                                               

-14                                                

**6**0                                                

**4**0

-35

**5**0

-49

**10** repetiu

*Se o resto se repete, a partir daquele momento tudo que fez para trás vai se repetir. 

*1/9 pode ter até 8 algarismos na parte periódica antes de repetir,  mas só tem 1.

*1/13 pode ter até 12 algarismos depois da virgula antes de repetir mas só tem 6.

*1/7 pode ter até 16 depois da virgula e tem 16 mesmo.



**2 - Principio da adição:**

n(AUB) = n(A) + n(B) - n(A∩B)

precisa subtrair a intersecção para não somar duas vezes.

A∩B = Ø    intersecção vazia Ø  n(AUB) = n(A) + n(B)

**EX:** em uma urna há 20 fichas numeradas de 1 a 20. Ao retirarmos apenas 1 ficha, qual a chance de obtermos uma bola cujo número é múltiplo de 3 ou um múltiplo de 5?

múltiplos de 3: A = {3;6;9;12;**15**; 18} => n(A) = 6

múltiplos de 5: B = {5;10;**15**; 20} => n(B) = 4

*se fosse múltiplo de 3 **e** de 5 seria 1, o número 15.

A∩B = {15} => n(A∩B) = 1

n(AUB) = n(A) + n(B) - n(A∩B) = 9 



**3 - Principio da multiplicação:**

O número de possibilidades de se realizar varias ações distintas e independentes pode ser obtido pelo produto (multiplicando) dos números de possibilidades de cada uma das ações, individualmente. 

**EX:** Um palhaço possui 4 calças(K) e 3 camisas(C). Considerando exclusivamente as possíveis escolhas de uma calça e uma camisa, de quantas maneiras diferentes ele pode se vestir?

K2 => C1 ou C2 ou C3 = 3

K2 => C1 ou C2 ou C3 = 3

K3 => C1 ou C2 ou C3 = 3

K4 => C1 ou C2 ou C3 = 3

3+3+3+3=12 ou **4 x 3 = 12**





