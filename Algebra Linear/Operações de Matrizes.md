# Igualdade de Matrizes

Duas matrizes são iguais se possuem o mesmo tamanho $m\times n$ e suas respectivas entradas $[a_{ij}]=[b_{ij}]$ .
$$
A=\begin{bmatrix} 
2&3\\
5&4
\end{bmatrix},
B=
\begin{bmatrix} 
2&3\\
5&4
\end{bmatrix}
$$
A matriz **A** e **B** são iguais, pois possuem o mesmo tamanho $2\times 2$ e suas entradas são equivalentes.

Porém essas duas diferem da seguinte matriz, apesar de ter tamanho semelhante às matrizes **A** e **B**:
$$
C=\begin{bmatrix} 
6&2\\
1&8
\end{bmatrix}
$$


> Podemos escrever a igualdade de matrizes $A=a_{ij},B=b_{ij}$ como:
>
> $(A)_{ij}=(B)_{ij}$
>
> $a_{ij}=b_{ij}$

## Exemplo 1

Seguindo o mesmo modelo exposto, caso uma das entradas da matriz **A** seja uma incógnita $x$ e assumindo que as matrizes $A,B$ são iguais.
$$
A=\begin{bmatrix} 
2&3\\
x&4
\end{bmatrix},
B=
\begin{bmatrix} 
2&3\\
5&4
\end{bmatrix}
$$
O valor de $x$ , obviamente, deve ser 5.

# Adição e Subtração de Matrizes

Definição da adição:

> Se A e B são matrizes com o mesmo tamanho, então a soma A + B é uma matriz obtida ao adicionar as entradas de B com as respectivas entradas de A.

## Exemplo

$$
A=\begin{bmatrix} 
5&2\\
3&1
\end{bmatrix},
B=
\begin{bmatrix} 
2&7\\
7&8
\end{bmatrix} \\
$$

A soma A + B:
$$
A + B =
\begin{bmatrix} 
5&2\\
3&1
\end{bmatrix}+

\begin{bmatrix} 
2&7\\
7&8
\end{bmatrix}
=
\begin{bmatrix} 
7&9\\
10&9
\end{bmatrix}
$$
Definição da subtração:

> Se A e B são matrizes com o mesmo tamanho, então a diferença A - B é uma matriz obtida ao subtrair as entradas de B das respectivas entradas de  A.

## Exemplo 

$$
A=\begin{bmatrix} 
5&2\\
3&1
\end{bmatrix},
B=
\begin{bmatrix} 
2&7\\
7&8
\end{bmatrix} \\
$$

A diferença A - B:
$$
A - B =
\begin{bmatrix} 
5&2\\
3&1
\end{bmatrix}
-

\begin{bmatrix} 
2&7\\
7&8
\end{bmatrix}
=
\begin{bmatrix} 
3&-5\\
-4&-7
\end{bmatrix}
$$
