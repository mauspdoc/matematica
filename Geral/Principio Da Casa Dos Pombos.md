# Princípio Da Casa Dos Pombos

# Teorema 1

> Se n + 1 objetos são distribuídos em n caixas, então pelo menos uma caixa contém dois ou mais objetos.

Isso é um pouco óbvio ao levar em conta a seguinte figura :

![](imagens/contagem/pigeons.jpg)

Temos 4 círculos (n caixas), porém temos 5 pombos(n+1 objetos), claramente pelo menos uma caixa terá dois ou mais pombos.

A principal prova desse teorema é por meio de uma contradição.

> Para haver um e somente um objeto em cada caixa, precisamos de uma caixa para cada objeto. Por exemplo , se temos 5 objetos, deveria ter 5 caixas; para 6 objetos, precisaríamos de 6 caixas. Isso é assumir k caixas e n objetos como k = n . Porém vimos que no teorema a quantidade de objetos é sempre k + 1 ,o que torna  k = n impossível, logo não é possível que todas as caixas contenham somente um objeto.

Observação :

> Esse princípio não é garantido para casos em que o número de objetos é menor que o número de caixas

O princípio em si não ajuda a identificar qual caixa possui mais de um objeto, a maior utilidade dele é a prova da existência de algo como a de que há uma caixa com mais de um pombo.

# Aplicações

## Aplicação 1

> Em um grupo de 13 pessoas há pelo menos 2 pessoas que fazem aniversário no mesmo mês.

Caso tentarmos afirmar que cada pessoa faz aniversário em um mês diferente, precisamos um mês para cada. Isso é aplicável no máximo para 12 pessoas, pois podem ser distribuídos para os 12 meses, que compõe o ano. Qualquer pessoa extra ( acima dessas 12 pessoas) deverá ser ocupar algum mês já ocupado.

## Aplicação 2

> Em grupo de 7 pessoas , deve haver pelo menos 4 do mesmo sexo(masculino/feminino).

Temos 7 pessoas sendo distribuídos em duas categorias(caixas) : masculino ou feminino.

7 pessoas = ${\color{orange}3} \times {\color{red}2} + 1$ , ou seja, podemos distribuir igualmente ${\color{orange}3}$ pessoas para essas ${\color{red}2}$ caixas, entretanto, há uma pessoa extra que precisa ser colocada em alguma caixa, logo, teremos pelo menos uma caixa com 4 pessoas.

## Aplicação 1 Revisitado

> Em um grupo de 13 pessoas há pelo menos 2 pessoas que fazem aniversário no mesmo mês.

Podemos fazer da mesma forma como na Aplicação 2. 

Temos 13 = ${\color{orange}1} \times {\color{red}12} + 1$, ou seja, podemos distribuir igualmente 1 pessoa para cada 12 caixas(meses), entretanto, sobra uma pessoa extra que deve ser colocada em alguma caixa já ocupada ( ,pois temos no máximo 12 caixas), logo, algum mês deve possuir 2 pessoas.

> Em um grupo de 3000 pessoas, há pelo menos 9 pessoas que possuem o mesmo aniversário.

Um ano possui 365 dias, então , devemos saber de quantas formas podemos distribuir esses dias igualmente para cada  pessoa e calcular as pessoas "extras".

3000 = ${\color{orange}8} \times {\color{red}365}+80$ , então, podemos distribuir 8 pessoas pra cada dia do ano , entretanto, sobra 80 pessoas que deve ocupar algum dia já ocupado( cada dia até então possui 8 pessoas), logo, deve haver algum dia com 9 pessoas compartilhando o mesmo aniversário. 