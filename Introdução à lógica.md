# Introdução À Lógica

Segundo Cezar A. Mortari:

> Lógica é a ciência que estuda princípios e métodos de inferência, tendo o objetivo principal de determinar em que condições certas coisas se seguem (são consequência), ou não, de outras.

Segundo John Nolt,Dennis Rohatyn:

> Lógica é o estudo de argumentos. Um argumento é uma sequência de enunciados na qual um dos enunciados é a conclusão e os demais são premissas, as quais servem para provar ou, pelo menos, fornecer alguma evidência para a conclusão.

# Lógica e Argumentos

## Validade e Forma

$(A_{1})$ 

> $P_{1}$    Todo gato é mamífero.
>
> $P_{2}$ 	Miau é um gato.
>
> $\blacktriangleright$ 	 Miau é um mamífero.

$(A_{2})$

> *Considerando Lulu como cachorro*:
>
> $P_{1}$    Todo gato é mamífero.
>
> $P_{2} $    Lulu é um mamífero.
>
> $\blacktriangleright$ 	Lulu é um gato.

$A_{3}$

> $P_{1} $	Todo peixe é dourado.
>
> $P_{2}$	Cléo é um peixe.
>
> $\blacktriangleright$ 	Cléo é dourado. 

A conclusão de $A_{1}$ é evidentemente correta, "Miau" é um mamífero é adequadamente justificado pelas premissas : sendo Miau um gato, a afirmação de que todo gato é um mamífero também o inclui; assim, ele não tem como não ser mamífero.

Observe no $A_{2}$ , a conclusão está errada , apesar de as premissas serem verdadeiras. Lulu é uma mamífero de fato, entretanto, não é um gato , isso logicamente é suportado pela existência de inúmeros mamíferos. Assim, mesmo que as premissas sejam verdadeiras, não são suficientes para justificar a conclusão.



# Cálculo Proposicional 

É a parte da lógica matemática que estuda a validade dos argumentos apresentados, em uma linguagem própria, a linguagem proposicional. 

## Proposição

Uma proposição ou enunciado  é uma sentença declarativa que pode ser verdadeira(V) ou falsa(F) .

Isso exclui exclui sentenças interrogativas, exclamativas , imperativas.

Exemplos de proposições:

> * $sen(90)º$ é igual a 1 ( Proposição verdadeira)
> * Júpiter está a 100 km da Terra (Proposição falsa) 

Exemplos de não-proposições:

> * Venha aqui! (Sentença imperativa)
> * Não corra tão rápido (Sentença imperativa)
> * Pela mãe do guarda (Sentença exclamativa)
> * Quantas vezes terei que repetir isso? (Sentença interrogativa)
>
> Essas sentenças não são proposições, pois é impossível estabelecer um valor-verdade para elas.

O cálculo proposicional se preocupa apenas com a relação entre as proposições e não com o conteúdo de cada, ou seu significado. 

As proposições podem ser substituídas por letras maiúsculas do alfabeto latino.

Exemplo:

> 1. Os suíços fabricam os melhores relógios e os franceses, o melhor vinho.
>
>    Podemos colocar da seguinte forma :  
>
>    * R = "Os suíços fabricam os melhores relógios"
>    * P = "Os franceses fabricam o melhor vinho"
>
>    Então teremos: R e P.
>
> 2.  Se prestar atenção na aula , então tirarei boas notas nas provas. 
>
>    Podemos colocar da seguinte forma:
>
>    * A = "Eu prestar atenção na aula"
>    * S = "Eu tirarei boas notas nas provas"
>
>    Então teremos: Se A, então S.

### Princípios da Lógica Clássica

A lógica matemática segue alguns princípios como regras fundamentais:

* Princípio da Identidade

  > "Toda proposição é idêntica a si mesma"
  >
  > P é P

* Princípio da Não Contradição

  > "Uma proposição não pode ser verdadeira e falsa ao mesmo tempo"
  >
  > não(P e não P)

* Princípio do Terceiro Excluído:

  > "Toda proposição ou é verdadeira ou é falsa , não existindo um terceiro valor que possa assumir"
  >
  > P ou não P (ou exclusivo)

### Conectivos Proposicionais 

* e ( $ \wedge $ )
* ou ( $ \vee $)
* se..., então ... ( $\implies$ )
* se, e somente se ( $\iff$ )
* não ( $\neg$ ou $\sim$)

### Classificação dos Conectivos

#### Conjunção ( $\wedge$  ou 'e' )

É o resultado da combinação de duas proposições ligadas pelo conectivo **e**, e que será simbolizada por $\wedge$ . A conjunção pode ser expressa também por palavras como : *mas, todavia, contudo , no entanto , visto que , enquanto , além disso , embora*.

Exemplo:

a) Maria foi ao cinema e Marta , ao teatro.

> * C = Maria foi ao Cinema.
> * T = Marta foi ao teatro.
>
> Simbolicamente : C $\wedge$ T

b) José é jogador de futebol e Leandro seguiu a carreira de medicina.

> * F = José é jogador de futebol.
> * M = Leandro seguiu a carreira de medicina.
>
> simbolicamente : F $\wedge $ M

c) André foi ao baile, mas Maria ficou em casa.

> * B = André foi ao baile.
> * C = Maria ficou em casa. 
>
> simbolicamente : B $ \wedge $ C

#### Disjunção ($\vee$  ou  'ou')

É o resultado de duas proposições ligadas pelo conectivo "ou" , que será simbolizado por $\vee$ . 

Na linguagem coloquial o "ou" pode ser empregado em dois sentidos "exclusivo" ou "inclusivo".

Exemplo:

> "Paulo é físico ou matemático."
>
> Caso o "ou" fosse inclusivo , Paulo tanto poderia ser físico como matemático.
>
> Caso o "ou" fosse exclusivo, Paulo não poderia ser físico e matemático ao mesmo tempo. 

No cálculo proposicional, o "ou" inclusivo é o mais abordado. 

#### Condicional ($\implies$)

Caso uma frase possa ser disposta da seguinte forma:

> Se (proposição 1) , então (proposição 2).

O símbolo utilizado para ligar as duas proposições é $\implies$.

Exemplo:

a) Se Alberto é poliglota, então fala várias línguas. 

> P = Se Alberto é poliglota.
>
> Q = Fala várias línguas. 
>
> Simbolicamente : P $\implies$ Q 

b) Se Fernando é inteligente, eu sou um gênio. 

> F = Fernando é inteligente.
>
> E = Eu sou um gênio.
>
> Simbolicamente : F $\implies$ E 

c) Se todos os homens são mortais e Sócrates é um homem, então Sócrates é mortal.

> H = Todos os homens são mortais.
>
> S = Sócrates é um homem.
>
> M = Sócrates é um mortal.
>
> Simbolicamente : $(H \wedge S)\implies M$
>
> Observação : Parênteses indica a ordem de operação. 

#### Bicondicional ($\longleftrightarrow$)

Toda proposição que pode ser colocada da seguinte forma:

> (proposição 1) se, e somente se (proposição 2)

A conexão entre as duas proposições é simbolizada por $\longleftrightarrow$.

A bicondicional pode ser entendida como a conjunção de duas condicionais , ou seja :

> $p \longleftrightarrow q$ pode ser entendido como $p \implies q$ e $q \implies p$ . 

Exemplos:

a) Só ganharás o dinheiro se completares o trabalho.

> Ganharás o dinheiro se, e somente se , completares o trabalho.  
>
> D = Ganharás o dinheiro.
>
> T = Completares o trabalho.
>
> Simbolicamente: $D \longleftrightarrow T$ .

#### Negação ( $ \neg $)

Não conecta duas proposições, mas simplesmente nega a afirmação da proposição que o precede. 

É um conectivo unário ( Caso fosse binário , ligaria duas proposições).

Se uma proposição P é verdadeira , então a sua negação(não P) resulta em falsa e vice-versa. Simbolizado por "$ \neg$".

Exemplos:

a) Luís não recebeu seu pagamento na data prevista.

> Se P = Luís recebeu seu pagamento na data prevista, então $\neg$P = Luís não recebeu seu pagamento na data prevista.

b) Alfredo não gosta de trabalhar.

> Se P = Alfredo gosta de trabalhar , então $\neg$P = Alfredo não gosta de trabalhar.

### Formalização

O processo de formalização consiste em converter um conjunto de proposições interligadas em uma estrutura composta de letras proposicionais, conectivos lógicos e símbolos de pontuação.

* Letras proposicionais : A,B,C... ou P$_{1}$ , P$_{2}$ ... ou a,b,c... ou p$_{1}$ , p$ _{2}$. 
* Conectivos Proposicionais : $\neg$ , $\wedge$ , $\vee$ ,$\longrightarrow$,$\longleftrightarrow$ .
* Parênteses: ( ).

Ordem de precedência:

* Operações dentro do parênteses devem ser efetuadas primeiro.

* A ordem de prioridade dos conectivos:

  - 1 º	 $\neg$
  - 2 º    $\wedge \text{ e } \vee$  
  - 3 º   $\longrightarrow$ e $\longleftrightarrow$ 

  

Exemplos de frases:

1. Interprete a letra sentencial "C" como "Está chovendo" e letra "N" como "Está nevando", e expresse a forma de cada sentença:
   1. Está chovendo.
      * C
   2. Não está chovendo.
      * $\neg$C
   3. Está chovendo ou nevando.
      * $C \vee N$
   4. Está chovendo e nevando.
      * $C \wedge N$
   5. Está chovendo, mas não está nevando.
      * $C \wedge \neg N$
   6. Não está chovendo  e nevando.
      * $\neg(C \wedge N)$
   7. Se não está chovendo, então está nevando.
      * $\neg C \implies N$ 

## Tabela verdade

Para determinar o valor-verdade (V) ou (F) de uma proposição composta, usa-se a tabela verdade , na qual figuram todas as possibilidades para as proposições simples (p e q) que compõem a proposta.

|      |      |  Conjunção   | Disjunção  |  Condicional   | Bicondicional |
| :--: | :--: | :----------: | :--------: | :------------: | :-----------: |
|  p   |  q   | p $\wedge$ q | p $\vee$ q | p $\implies$ q |  p $\iff$ q   |
|  V   |  V   |      V       |     V      |       V        |       V       |
|  V   |  F   |      F       |     V      |       F        |       F       |
|  F   |  V   |      F       |     V      |       V        |       F       |
|  F   |  F   |      F       |     F      |       V        |       V       |

 Tabela para a negação( conectivo unário), tomando **p** como uma proposição simples.

|      | Negação |
| :--: | :-----: |
|  p   | $\neg$p |
|  V   |    F    |
|  F   |    V    |

O número de linhas numa tabela depende do número de proposições simples , sendo $n$ o número de proposições simples, a fórmula para calcular isso é $2^n$. Na primeira tabela temos duas proposições simples $p$ e $q$ , logo temos $2^2$ linhas , ou seja, 4. Na segunda tabela temos apenas uma proposição simples , logo 2 linhas.

Exemplos:

1. Verifique as preposições a seguir:
   1. O Brasil foi colônia de Portugal, mas hoje é um país independente.
      1. <img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/Logica/1.png" style="zoom:70%;" />
   2. Vivemos em um país da América Latina, portanto, nosso idioma é proveniente do Latim.
      1. <img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/Logica/2.png" style="zoom:70%;" />
   3. Só cursamos a faculdade, se obtivermos aprovação no vestibular. 
      1. P(V) =  Cursaremos a faculdade 
      2. Q(V) = Obtivermos aprovação no vestibular
      3. P $\iff$ Q (V)
   4. Se D. Pedro proclamou a independência do Brasil, ou declarou guerra à Inglaterra, então, o Brasil foi colônia da Inglaterra.  
      1. <img src="/home/mauspdoc/Documentos/Educacional/Matemática/imagens/Logica/4.png" style="zoom:67%;" />

#### Complemento

###### "Ou"

Uma fase composta pelo conectivo "ou" é verdadeira caso tenha pelo menos uma de suas proposições simples como verdade.

Entretanto, se o "ou" for de uso exclusivo, temos:

 

|  P   |  Q   | P $\vee$ Q |
| :--: | :--: | :--------: |
|  V   |  V   |     F      |
|  V   |  F   |     V      |
|  F   |  V   |     V      |
|  F   |  F   |     F      |

O conectivo "ou" com o sentido de exclusivo pode ser denotado formalmente como $(P \vee Q ) \wedge \neg(P \wedge V)$ :



## Classificação Proposicional 

### Tautologia / Tautológica

Uma proposição composta cujo valor lógico é sempre verdade, independente do valor lógico das proposições simples que a compõe.

### Contradição

Uma proposição cujo valor lógico é sempre falso, independente do valor lógico das proposições simples que a compõe.

### Contingência 

O valor lógico da proposição composta pode ser verdadeiro ou falso dependendo do valor lógico de suas proposições simples. 

# Cálculo de Predicados  ( Cálculo Funcional)

