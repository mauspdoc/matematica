# Equações Quadráticas 

Equações quadráticas são equações na seguinte forma :
$$
 ax^2+bx+c=0
$$
Onde a,b,c são constantes e $a \neq 0$ . $ax^2$ é chamado de termo quadrático, $bx$ é conhecido como termo linear, e c como termo constante. $ax^2 + bx + c$ é a expressão quadrática, e a,b,c são coeficientes da expressão.

# Aquecimento

## Problema 1

> Ache os valores de x que satisfazem a equação $x^2=16$.

Veja que dois números ao quadrado resultam em 16, quando temos x = -4 e x = 4.

## Problema 2

>  Ache as soluções para a equação $x^2-6x=0$

A melhor forma é pensar como essa equação pode ser formado por expressões mais simples :
$$
x^2-6x=x(x-6)
$$
Agora temos o seguinte :
$$
x(x-6) =0
$$
Então para esse produtos $x(x-6)$ ser igual a zero, um dos seus termos precisa ser zero :

1. Podemos ter x = 0
2. Podemos ter $(x-6)=0$, ou seja, x precisa ser igual a 6

Logo, os valores de x que satisfazem essa condição é 0 e 6.

> Cuidado :
>
> Poderíamos ter somado 6x para ambos os lados da equação :
> $$
> x^2-6x +{\color{orange}6x} =0 +{\color{orange}6x}
> $$
> Portanto teríamos :
> $$
> x^2=6x
> $$
> Bastando dividir por x cada lado :
> $$
> x = 6
> $$
> Alguém poderia considerar isso como uma resposta, entretanto, isso não 100% verdade, pois outros valores também são respostas para esse problema, incluindo o próprio zero. E não poderíamos dividir ambos os lados por x se x=0, isso é impossível. 

# Fatorando

 O produto de dois fatores pode resultar na expressão quadrática. Para isso vamos ver a seguinte forma :
$$
(a+b)^2=(a+b)(a+b)
$$
Resulta em :
$$
a ^2 + 2ab+b^2
$$
Isso pode ser feito em uma tabela :

|       | **a** | **b** |
| :---: | :---: | :---: |
| **a** | $a^2$ |  ab   |
| **b** |  ab   | $b^2$ |

Para fazer o mesmo com uma expressão quadrática, seria necessário dois termos que contém x : $ ax^2,bx$ ; e por fim precisamos do termo constante $c$ . 

Para atingir esse objetivo precisamos combinar o x de um fator com o x de outro fator, o os outros termos desses fatores podem ser diferentes :

|       | x     | s    |
| ----- | ----- | ---- |
| **x** | $x^2$ | $xs$ |
| **r** | $xr$  | $rs$ |

Então, temos $(x+s)(x+r)$, resultando em :

- $x^2$ --> Termo quadrático.
- $xs \ e \ xr$ , veja que a soma desses termos é $xs+xr=x(s+r)$, o que origina o termo linear se considerar $(s+r) = b$. Portanto, temos $bx$, nosso termo linear.
- $rs$ --> Termo constante $c$.

> Comparando a expressão :
> $$
> ax^2+bx+c
> $$
> Com o que vimos, temos relações interessantes para resumir :
>
> 1. $b = s+r$
> 2. $c = sr$
>
> Isso para a nossa expressão fatorada :
> $$
> (x+s)(x+r) = a^2+bx+c=0
> $$

## Problema 1 

> Ache todas as soluções para a equação $x^2+8x+15=0 $.

Usando o que vimos, caso desejarmos usar a forma fatorada $(x+s)(x+r)=0$ :

1. $b = 8 = r + s$
2. $c=15=rs$

Logo, temos que descobrir os valores para $r$ e $s$, com algumas tentativas e erros podemos chegar a conclusão de que os números para resolver isso são 3 e 5. Observe que não importa se é $s$ ou $r$ que é 5 ou 3, na verdade, tanto faz.

Então, sabendo dos valores de r e s :
$$
(x+s)(x+s) = (x+5)(x+3)=0
$$
Para essa equação ser satisfeita e ser zero, um dos dois termos precisa ser zero :
$$
\begin{align} 
(x+5) =0 &&&& (x+3)=0
\\
x = -5 &&&& x=-3
\end{align}
$$
Então, os valores de x que satisfazem essa equação são as raízes, portanto, a raízes são -3 e -5 .

## Problema 2

> Ache todas as soluções para a equação $y^2-5y-24=0$

Então, temos :
$$
b = r+s =-5 \\
c = r\times s=-24
$$
Como temos :
$$
r \times s = -24
$$
Para 24 ser negativo,pelo menos um termo precisa ser negativo e o outro positivo, pois se ambos fossem negativos ou positivos, o resultado seria positivo.

Vamos considerar r como o termo negativo.

Para originar -5 de r + s, o valor absoluto de r (termo negativo) precisa ser maior que o valor absoluto de s, pois o termo com maior valor absoluto define o sinal do resultado.

Dessas pistas tiramos a seguinte conclusão :
$$
r = -8\\
s = 3
$$
Logo, a nossa expressão fatorada é :
$$
(x+s)(x+r) = (x+3)(x-8)=0
$$
Portanto :
$$
\begin{align}
(x+3) = 0 &&& (x-8)=0 \\
x = -3 &&& x = 8 
\end{align}
$$
Então os valores de x que satisfazem essa equação é -3 e 8.

> Sumarizando ideias importantes :
> $$
> a ^2+bx+c=(x+s)(x+r)
> $$
> Se c for positivo, então os sinais de r e s são os mesmo :
> $$
> \begin{align} c = s \times r 
> \begin{cases}
> +c & \quad ,\text{quando }(+s) \times (+r) \\
> +c & \quad,\text{quando } (-s) \times (-r) \\
> -c & \quad,\text{quando } (+s)\times (-r) \text{ ou } (-s)\times(+r) \\ 
> 
> \end{cases}\end{align}
> $$
> E o b dita o sinal de r e s comparando o valor absoluto deles e a dominância do  sinal.

Observação importante , a fatoração vista nessa seção só pode ser aplicada com equações cujo o coeficiente do termo quadrático seja 1.
$$
x^2+4x+6=0
$$
Caso ache alguma equação cujo o coeficiente do termo quadrático não seja zero :
$$
-2x^2+2x+4=0
$$
Tente transformar essa equação em um forma conhecida.

Para isso podemos dividir toda a equação por 2 :
$$
-ax^2+x+2=0
$$
E temos que ter nosso termo quadrático positivo para facilitar, então podemos multiplicar essa equação por -1 :
$$
ax ^2-x-2=0
$$
Agora é aplicável ao nosso método fatorado visto. Onde temos o seguinte :
$$
b = r+s= -1 \\
c = r \times s = -2
$$
O sinal de C por ser negativo indica que *r* e *s* possuem sinais opostos, e o B indica que o número negativo possui maior valor absoluto. Então os valores possíveis para isso é -2 e 1. Portanto, temos :
$$
(x-2)(x+1)=0
$$
Então, algum desses dois fatores precia ser zero :
$$
\begin{align} 
(x-2) = 0 & & & (x+1) = 0\\
x = 2 &&& x=-1
\end{align}
$$
 Esses valores de x tornam a equação igual a zero, portanto, são as raízes da equação ( 2 e -1).

# Fatorando (parte 2)