# Geometria Euclidiana Plana ( João Lucas Marques Barbosa)

# Capítulo 1 

## Os axiomas de Incidência e ordem

#### Axiomas de Incidência

**Axioma 1** 

> Qualquer que seja a reta existem pontos que pertencem a reta e pontos que não pertencem a reta.
>
> > Complemento:
> >
> > > Segundo Geometria Euclidiana Plana( Rezende ) na página 15:
> > >
> > > "O plano é visto como o conjunto em que os pontos são seus elementos e as retas , seus subconjuntos"

**Axioma 2**

> Dados dois pontos distintos existe uma única reta que contém estes pontos 
>
> > Observação:
> >
> > Pontos de  uma mesma reta são chamados de pontos colineares

**Proposição 1**

> Duas retas distintas ou não se interceptam ou se interceptam em apenas um único ponto.
>
> Prova:
>
> > Seja *m* e *n* duas retas distintas. A interseção delas não pode conter dois pontos ou mais , pois nesse caso essas retas seriam coincidente segundo o *axioma 2* . Logo , ou elas se cruzam em um único ponto ou não se interceptam em nenhum. 
> >
> > ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/barbosa/1.png)

#### Axiomas de ordem

**Axioma 1**

> Dados três pontos de uma reta , um e apenas um está entre os outros dois.
>
>  ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/barbosa/2.png)
>
> > Observação : 
> >
> > É muito comum autores especificarem a posição dos pontos usando "-" como em  A-C-B (O ponto C está entre os pontos A e B) . Também poderíamos usar "*" no lugar de "-" , assim o resultado seria A\*C\*B .  
> >
> > Observação 2:
> >
> > Definição 1.4 da pagina 17 em Geometria Euclidiana Plana( Rezende ):
> >
> > > Seja A,B e C três pontos colineares e distintos dois a dois. Se $AB+BC=AC$ , dizemos que $B$ está entre $A$ e $C$ , o que denotamos por $A-B-C$ . Observe também que se temos $A-B-C$ , então temos também $C-B-A$ , pois o importante é o $B$ estar entre esses dois pontos.

**Definição 1**

> O conjunto constituído por dois pontos A e B e por todos os pontos que se encontram entre eles(A e B) é chamado de segmento AB. Os pontos A e B são chamados de extremos ou extremidades do segmento.

**Definição 2**

> Se A e B são pontos distintos, o conjunto constituído  pelos pontos do segmento AB e por todos os pontos C, tais que B se encontra entre A e C, é chamado de semi-reta de origem A contendo o ponto B, e é representado por $S_{AB}$ , o ponto A é então denominado origem da semi-reta.
>
> ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/barbosa/3.png)
>
> > Observação do autor:
> >
> > Dois pontos A e B determinam duas semi-retas $S_{AB}$(origem no ponto $A$) e $S_{BA}$(origem no ponto $B$) , as quais contém o segmento AB.
> >
> > Complemento:
> >
> > > Definição 1.8 da pagina 18 em Geometria Euclidiana Plana( Rezende ):
> > >
> > > "A semi-reta de origem $A$ contendo $B$ , a qual é denotada por $\overrightarrow{AB}$, é definida como a união dos pontos do segmento $AB$ com o conjuntos dos pontos $X$ tais que $A-B-X$. O ponto $A$ é denominado origem da semi-reta "
> > >
> > > ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/barbosa/5.png)
> > >
> > > Veja que a frase indica que B está entre A e X, ou seja : A-B-X ou X-B-A seriam formas corretas, que dão sentido a duas semi-retas diferentes. 

**Proposição 1 ** 

> 1. $S_{AB} \cup S_{BA}$ é a reta determinada pelos pontos $A$ e $B$. 
> 2. $S_{AB} \cap S_{BA}$ = AB 
>
> Prova:
>
> > Veja que $S_{AB}$ e $S_{BA}$ contém o segmento AB em comum de acordo com a definição 2 , portanto a interseção $S_{AB} \cap S_{BA}$ é o segmento AB . 
> >
> > $S_{AB}$ é uma semi-reta , ou seja, além de ser constituído pelo segmento  AB , também é composta por todos os pontos C de tal forma que B está entre A e C. 
> >
> > Já $S_{BA}$ é um semi-reta que contém o segmento AB e é composta por todos os pontos C de tal forma que A está entre B e C. 
> >
> > Resumindo esses casos:
> >
> > * Se C está entre A e B, então é o segmento AB
> > * Se B está entre A e C(estamos falando de todos os pontos de uma reta qualquer) , então temos $S_{AB}$  
> > * Se A está entre B e C, então temos $S_{BA}$.

