# Limites

# Segundo Thomas Calculus

## Taxa de Mudança e Linhas Tanges a Curva

### Velocidade média e instantânea 

​	No século 16 , Galileo descobriu que objetos sólidos soltos,inicialmente em repouso, caem a uma distância proporcional  ao quadrado do tempo de queda. Esse tipo de movimento é conhecido como queda livre. Assume que não há resistência do ar para reduzir a velocidade, e que a única força que força o objeto cair é a gravidade. Se $y$ é a distância de queda em pés após $t$ segundos, então a Lei de Galileo é
$$
y = 16t^{2}ft
$$
Onde 16 é a constante de proporcionalidade (Se $y$ for medido em metros, então a constante é perto de 4.9 )

​	A velocidade média nesse percurso é dada por:
$$
Velocidade\ Média=\frac{Distância\ Percorrida}{Intervalo \ de\ Tempo} = \frac{f(t_{2})-f(t_{1})}{t_{2}-t_{1}} = \frac{\Delta y}{\Delta t}
$$

#### Exemplo 1

Calculando a velocidade média de uma pedra em queda livre no instante t = 1 e t = 2 segundo .

Solução: 

​	Podemos calcular a velocidade média dentro de um intervalo $[t_{0},t_{0}+h]$ ,ou seja, $\Delta t = (t_{0} + h) -(t_{0})=h$ 
$$
\frac{\Delta y}{\Delta x }= \frac{16(t_{0}+h)^2-16t_{0}^2}{h}ft/s
$$
 	Não podemos usar a fórmula para calcular velocidade média simplesmente substituindo h como zero, pois não existe divisão por zero. Entretanto , podemos calcular a velocidade para intervalos cada vez menores começando tanto no ponto $t_{0}$ = 1 e $t_{0}$ = 2 . Faremos isso tornando os valores de h cada vez menores.

| Valor de h | Velocidade no intervalo  h começando no $t_{0}=1$ | Velocidade no intervalo  h começando no $t_{0}=2$ |
| :--------: | :-----------------------------------------------: | :-----------------------------------------------: |
|     1      |                        48                         |                        80                         |
|    0.1     |                       33.6                        |                       65.6                        |
|    0.01    |                       32.16                       |                       64.16                       |
|   0.001    |                      32.016                       |                      64.016                       |
|   0.0001   |                      32.0016                      |                      64.0016                      |

​	Observamos que no intervalo  h começando no tempo igual a 1, a velocidade média parece se aproximar de 32 $ft/s$ a medida que o valor do intervalor h diminui. Enquanto que  no intervalo h começando no tempo 2 ,  a velocidade se aproxima de 64 $ft/s$.

​	De forma algébrica  podemos determinar tal resultado e confirmar:
$$
\frac{\Delta y}{\Delta t} = \frac{f(t_{0}+h)-f(t_{0})}{h} = \frac{16(t_{0}+h)^2 -16t_{0}^2}{h}\\
\frac{16(t_{0}^2+2t_{0}h+h^2)-16t_{0}^2}{h} = \frac{32t_{0}\color{orange}{h}+16h^2}{h}\\
\frac{\bcancel{h}(32t_{0}+16h)}{\bcancel h} \\
32t_{0}+16h
$$
​	Quando $t_{0}$ se aproxima de zero, o valor $16h$ torna-se desprezível , logo:
$$
32t_{0}
$$
​	Confirmando os valores visto no quadro acima:
$$
Para \ t_{0}=1: \\
32\times 1 = 32 ft/s \\
Para \ t_{0} = 2:\\
32\times 2 = 64 ft/s
$$

## Limites

### Descrição Informal

​	Agora a definição informal do limite de uma função $f$ no ponto interior do domínio de  $f$. Suponha que $f(x)$ é *definida* no intervalo aberto em $c$ , exceto possivelmente no próprio $c$. Se $f(x)$ é arbitrariamente perto do número $L$ (tão perto de $L$ como desejar) para todos os $x$ suficientemente perto de $c$, além do próprio $c$ , então falamos que $f$ se aproxima do limite $L$ quando $x$ tende a $c$:
$$
\lim_{x\to c}{f(x)} =L
$$
 

​	É Uma definição informal, pois não é definida por frases precisas.

### Descrição precisa de limites

<figure><img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/4.png"/></figure>

Como devemos definir $\delta > 0 $ para manter $x$ dentro do intervalor $(c-\delta,c+\delta)$ para manter $f(x)$ dentro do intervalo $(L-\frac{1}{10},L+\frac{1}{10})$?

​	Definição:

> Seja f(x) definida em um intervalo aberto contendo $c$ , exceto possivelmente em $c$. Falamos que o limite de $f(x)$ quando $x$ tende a ao número $L$ é escrito como:
> $$
> \lim_{x\to c}{f(x)}=L
> $$
> se, para cada número $ \varepsilon>0$ , existe um valor $\delta$ correspondente tal que:
> $$
> |f(x)-L|< \varepsilon \ sempre \ que \ 0<|x-c|<\delta
> $$
> 



![5](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/5.png)

A definição formal de limites não indica como achar o limite de uma função, mas sim como verificar que um valor encontrado para o limite está correto. 

Veja a ilustração abaixo, onde mostra o teste de limites:

![6](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/6.png)

#### Encontrando algebricamente um $\delta$ para um dado $f,L,c$ e $\varepsilon>0$

> O processo para achar $\delta>0$ tal que 
> $$
> |f(x)-L|<\varepsilon \ quando \  0<|x-c|<\delta \\
> $$
> Pode ser encontrado em dois passos
>
> 1. Resolva a desigualdade $|f(x)-L|<\varepsilon$ para achar um intervalo aberto $(a,b)$ contendo $c$ na qual a desigualdade é composta por todos os valores de $x\neq c$. Note que não precisamos de $x=c$, o valor de $f(x)$ em $x=c$ não influencia a existência do limite.
> 2. Ache o valor de $\delta>0$ que se encontre no intervalo aberto $(c-\delta,c+\delta)$ centrado em c dentro do intervalo $(a,b)$. A  desigualdade $|f(x)-L|< \varepsilon$ vai segurar todos os valores $x\neq c$ nesse intervalo de $\delta$.

> Exemplo 1:
>
> Prove que $\begin{equation}\lim_{x\to c}{f(x)}=4 \end{equation} $  se:
> $$
> f(x)= \begin{cases}
> x^2 ,& x\neq 2										\\
> 1 ,&  x =2
> \end{cases}
> $$
> **Solução** 	Nossa tarefa é mostrar que existe para um dado $\varepsilon >0$ , $\delta>0$ tal que  :
> $$
> |f(x)-4| < \varepsilon \ quando \ 0<|x-2|<\delta
> $$
>
> 1. Resolver a inequação $|f(x)-4| < \varepsilon$ e achar o intervalo aberto que contém x = 2 no qual a inequação permanece verdadeira para todos os valores $x \neq 2$.
>
>    Para $x\neq2$ ,temos $f(x)=x^2$ , a inequação para resolver é $|x^2-4|<\varepsilon$:
>    $$
>    |x^2-4|<\varepsilon \\
>    -\varepsilon <x^2-4<\varepsilon \\
>    4-\varepsilon <x^2<\varepsilon +4 \\
>    \sqrt{4-\varepsilon }<x<\sqrt{\varepsilon + 4}
>    $$
>    A inequação $|f(x)-4|<\varepsilon$ permanece verdadeiro para todos os valores $x \neq 2$ no intervalo aberto $(\sqrt{4-\varepsilon },\sqrt{\varepsilon + 4})$ 
>
> 2. Achar o valor de $\delta>0$ ,que possui o intervalo ($2-\delta,2+\delta$) ,  dentro do intervalo $(\sqrt{4-\varepsilon },\sqrt{\varepsilon + 4})$ . O valor minimo é os dois números. Essa é a distância do ponto $x=2$ até os pontos $(\sqrt{4-\varepsilon },\sqrt{\varepsilon + 4})$ .
>    $$
>    \delta=min\{ 2- \sqrt{4- \varepsilon},2- \sqrt{4+ \varepsilon}\}
>    $$
>    Se $\delta$ assumir estes valores ou menores positivos , a inequação $0<|x-2|<\delta$ vai automaticamente inserir o x entre $\sqrt{4- \varepsilon }$ e  $\sqrt{4+ \varepsilon }$ para fazer o $|f(x)-4|< \varepsilon$ .
>
>    O intervalo de $\delta$ desde o ponto $x=2$ é $(0, \sqrt{4+ \varepsilon})$ , ou seja ,$\delta$ = $min\{2,\sqrt{4+\varepsilon} -2 \}$
>
>    ![7](/home/mauspdoc/Documentos/Educacional/Matemática/imagens/triangle/7.png)
>
>    

#