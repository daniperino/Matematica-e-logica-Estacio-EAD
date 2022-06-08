**Agrupamento Arranjo** sem repetição (filas/senhas/anagramas)

A n,p = n! / (n – p)!

**EX:**

**1 -** De quantas maneiras podemos fazer filas com 5 alunos, se dispomos de 12 alunos?

12x11x10x9x8 = 95.040

Forma fatorial => 12!/7!    12 - 5 = 7

A 12, 5 = 12!/ (12-5)!

**2 -** 8 alunos com todos na fila:

8x7x6x5x4x3x2x1 = 40.320

Forma fatorial => 8!/0!     8-8 = 0

**3 -** Quantas senhas de 3 algarismos distintos posso formar com os algarismos 2 a 8?

2 a 8 = 7 algarismos

7x6x5 = 210 

Forma fatorial => 7!/4!    7-3 = 4

**Agrupamento Permutação** sem repetição (filas/senhas/anagramas)

**EX:** 

Calcule o número de anagramas das palavras TRAPO e da palavra PUBLICAR.

TRAPO = 5 letras, todas diferentes

1x2x3x4x5 = 120

PUBLICAR = 8 letras, todas diferentes

1x2x3x4x5x6x7x8 = 40.320

**Agrupamento Combinação** sem repetição (comissões/subconjuntos)

*Precisa dividir

A n,p = n!/(n-p)!

**EX:**

Determine quantos subconjuntos de 3 elementos podemos construir a partir de um conjunto com 7 elementos.

**R.** Se a, b, c são 3 dos 7 objetos do conjunto, então estamos contando as 6 filas diferentes como subconjuntos diferentes, que são, na verdade, iguais.

Ordenando 7 objetos 3 a 3 obtemos A 7, 3 = 7!/(7-3)! = 7x3x5 = 210

Mas de cada 3 objetos escolhidos estamos contando 3! = 6 vezes o mesmo conjunto. Então, para ajustar nosso resultado devemos **dividir** o resultado anterior (210) por 3! = 6

210/3! = 35 subconjuntos de 3 elementos a partir de um grupo com 7 elementos.

*Deve dividir o número de filas por p.

**Agrupamento arranjo** com repetição (senhas/filas/anagramas)

**EX:** 

Quantas senhas de 4 algarismos posso formar com os algarismos de 2 a 8?

**R.** 2 a 8 = 7 algarismos

7x7x7x7x7x7x7= 7⁴=2.401

**Agrupamento Permutação Circular** (mesa/círculo)

**EX:** 

De quantas maneiras podemos dispor 5 pessoas em torno de uma mesa?

Você só circula os lugares/roda as cadeiras.

5! = 120 (mas não é isso a resposta)

precisa sempre dividir pelo número de pessoas 5!/5 = 24

**Agrupamento Permutação** com repetição

**EX:**

Calcule o número de anagramas da palavra ARARAQUARA.

Araraquara tem 10 letras;

Tem 5 letras A;

Tem 3 letras R;

Se ordenarmos de todas as formas as 10 letras, obteremos um total de P10 situações, ou seja, P10 = 10!

Mas, na verdade, muitos desses agrupamentos formados são o mesmo anagrama. Isso porque as letras A1 até A5, por exemplo, são na verdade a mesma letra A. Então, imagine tais letras em suas posições nos anagramas anteriores.

Se você trocar de posição qualquer uma delas entre si (nas 5 posições que elas ocupam), você continuará com o mesmo anagrama. Então **é necessário dividir o total** de 10! por P5 = 5! para evitar contagem múltipla. Da mesma forma, devemos dividir o total anterior por 3 (repetições da letra R).

10! / 5! x 3! = 5.040

**Agrupamento Combinação** com repetição

*A ordem não é relevante

**EX:**

Uma loja possui tabletes de chocolate de 3 marcas diferentes e você deseja comprar 8 tabletes. De quantas maneiras diferentes podem ser escolhidos os tabletes em sua compra?

**R.** Dispomos de 2 tipos de objetos: o sinal de adição (usado 2 vezes - pois há 3 tipos de tabletes) e quadradinhos que simbolizam os tabletes de chocolate de qualquer tipo. Então, cada sequencia de sinais de adição e de quadradinhos representa uma situação de compra.

□□+□+□□□□□ => 2 tabletes do tipo um, 1 tablete do tipo dois e 5 tabletes do tipo três;

□□□□+□□□□ => 4 tabletes do tipo um, nenhum do tipo dois e 4 do tipo três;

++□□□□□□□□ => todos os 8 do tipo três;

Assim, o problema de determinar a quantidade de combinações com repetição de n objetos p a p recai na contagem de quantas permutações com repetição de 10 objetos (2 sinais de adição e 8 quadradinhos):

CR8/5 = PR 10/ 2, 8 = 10! / 2! x 8! = 45

Note que, no caso geral de dispormos de n objetos e desejamos calcular o número de combinações com repetição escolhendo p objetos, a expressão da quantidade desses agrupamentos será dada por:

CRn/p = PRn+p-1 / n, p-1

***A ordem é relevante?**

SIM => Filas/ senhas/anagramas (Arranjos e Permutações)

NÃO => Comissões/subconjuntos (Combinações)

[Link](https://www.youtube.com/playlist?list=PLMmvZBYhOMPWaoW0n39YuoNwaGD9vbrmM) de alguns exercícios sobre o tema em vídeo com o professor André Brochi 













