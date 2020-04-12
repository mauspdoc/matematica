# Triângulos

Se temos três pontos não colineares A,B,C, então o conjunto $\overline{AB} \cup \overline{BC}\cup \overline{AC} $ é chamado de triângulo.

<img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/1.png" alt="1" style="zoom:6%;" />

Os os segmentos $\overline{AB},\overline{BC},\overline{AC}$  são chamados de lados do triângulo,enquanto que os pontos *A*,*B*,*C* são conhecidos como vértices. 

O triângulo é denotado pelo seguinte símbolo:
$$
\triangle ABC
$$
Veja que o $\triangle ABC$ não contém nenhum ângulo, pois seus lados são segmentos de retas , enquanto que a definição de  ângulos é :

> Um **ângulo é a união de duas semi**-**retas** que têm a mesma origem, mas não estão contidas numa mesma **reta**. 
>
> <img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/2.png" alt="2" style="zoom:20%;" />

Caso queira marcar todos os ângulos, é preciso fazer seus lados como semi-retas:

![3](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/3.png)

# Congruência entre triângulos

## A ideia de congruência

A ideia intuitiva é a mesma para todas as figuras , é a capacidade de uma figura ser movida ,sem modificar seu tamanho ou formato, de forma que coincida com uma segunda figura.

**Definição 1** :

> $\overline{AB} \cong \overline{CD}$ significa por definição que AB = CD.

**Definição 2**:

> Por definição, $\angle BAC \cong \angle PQR$ significa que a medida do ângulo $\angle BAC$ = medida do ângulo $\angle PQR$.

**Definição 3** :

> Dado um triângulo $\triangle ABC$ e outro $\triangle DEF$,  e uma correspondência ABC $\leftrightarrow$ DEF.
>
> É uma congruência se todas as seis condições forem cumpridas:
>
> ​	$\overline{AB} \cong \overline{DE} $ , $\angle A\cong \angle D$ 
>
> ​	$\overline{AC} \cong \overline{DF} $ , $\angle B \cong \angle E$
>
> ​	$\overline{BC} \cong \overline{EF} $ , $\angle C \cong \angle F$
>
> ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/8.png)
>
> Observação: Correspondência indica que o lado A é corresponde ao lado D , B ao E, C ao F , da mesma forma seus ângulos.

**Postulado 1 de congruência** (LAL):

>  Caso dois lados e o ângulo entre esses lados de um primeiro triângulo sejam congruentes à um segundo triângulo correspondente, então eles são congruentes :
>
> ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/9.png)
>
> > Como é  um postulado, não há provas.

## Teoremas básicos de congruência

### Teorema 1 (Triângulo Isósceles)

> Se dois lados de um triângulo são congruentes , então os ângulos opostos a eles são congruentes.

Prova:

> Vou mostrar 3 formas de provar isso. A primeira é  imaginar um mesmo triângulo isósceles como dois($\triangle ABC$ e $\triangle ACB$) . 
>
> <img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/10.png" style="zoom:70%;" />
>
> De forma didática, irei colocar o mesmo triângulo com duas notações diferentes sobre seus lados pra diferenciar. Triangulo $\triangle A_{1}B_{1}C_{1}$ e $\triangle A_{2}B_{2}C_{2}$ . O lado $A_{1}B_{1}$ é igual a $A_{2}C_{2}$ , o lado $A_{1}C_{1}$ é igual ao lado $A_{2}B_{2}$ , e ambos tem o ângulo A congruente , logo pelo postulado LAL(Postulado 1 de congruência).
>
> A segunda forma é dividir $\triangle ABC$ ao meio , dividir o $\overline{BC}$ pela metade, logo $\overline{BD} \cong \overline{DC}$ . Temos também a correspondência de congruência em $\overline{AD}$, que é o lado comum a ambos os triângulos formados, $\overline{AB} \cong \overline{AC}$ . Portanto, todos os lados de um triângulo são congruentes aos lados do outro triângulo.
>
> Como podemos assegurar a segunda forma de demonstrar? Como afirmar que um corte no triângulo seria simétrico desse jeito, mantendo duas partes iguais entre si?
>
> A terceira forma de demonstrar:
>
> > (1) Divida o $\angle C$ pela metade , e que a linha de encontro das duas metades se ligue a $ AB $ no ponto D
> >
> > (2) Agora, nos triângulos $\triangle ACD$  e $\triangle BCD$  , $AC \cong BC$ 
> >
> > (3) $\angle ACD \cong \angle BCD$
> >
> > (4) $CD \cong CD$ 
> >
> > (5) Pelo postulado Lado-Ângulo-Lado, $\triangle ACD \cong \triangle BCD$
> >
> > (6) Logo, $\angle A \cong \angle B$ 
>
> Figura para a terceira prova:
>
>  ![](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/11.png)

###  Teorema 2 (ALA)

> Dada uma correspondência entre dois triângulos( ou entre um triângulo e ele mesmo). Se dois ângulos e o lado incluído do primeiro triângulo são congruentes as suas partes correspondentes do segundo triângulo , então há uma correspondência de congruência.
>
> Em símbolos:
>
> > Dado $\triangle ABC$ , $\triangle DEF$, e a correspondência $ABC \leftrightarrow DEF$. Se $\angle A \cong \angle D$, $\angle C \cong \angle F$  e $\overline{AC} \cong \overline{DF}$ , então $\triangle ABC \cong \triangle DEF$  
>
> #TODO