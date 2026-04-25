# Aula-16-04-COMPARADORES-E-OPERADORES

Revisão Lógica de Comparação e

Operadores

Introdução ao Pensamento Lógico
Traduzimos o raciocínio humano para o código através de comparadores e operadores
lógicos.
O objetivo dessas ferramentas é transformar dados em respostas binárias: True
(Verdadeiro) ou False (Falso). É essa lógica que permite que um software se comporte de
forma inteligente e dinâmica.

Ferramentas de Comparação: Os Blocos Básicos
Os operadores de comparação analisam a relação entre dois valores e retornam um valor
booleano.
Tabela de Operadores de Comparação
Operador Significado Exemplo Prático Resultado Python

== Igual a 8 == 7 False

!= Diferente de 8 != 7 True

> Maior que 8 > 6 True

< Menor que 8 < 7 False

>= Maior ou
Igual a

10 >= 10 True

None
<= Menor ou
Igual a

10 <= 10 True

Insight de Precisão:
1. Atribuição vs. Comparação: = define valor; == compara valores.
2. Inclusividade: Use >= ou <= quando o valor limite também faz parte da
regra.
3. Tipagem: O Python diferencia o número 10 do texto "10".

3. Operadores Lógicos: A Arte de Combinar
Condições
Utilizados quando uma decisão depende de múltiplos fatores simultâneos.
● and (E): Retorna True apenas se ambas as condições forem verdadeiras.
● or (OU): Retorna True se pelo menos uma das condições for verdadeira.
● not (Negação): Inverte o valor lógico (transforma True em False e vice-versa).
Exemplos de Verificação (Sintaxe Python)
Python

1. print(8 > 7 and 7 > 8) # Resultado: False
2. print(8 > 7 or 9 < 8) # Resultado: True
3. print(7 >= 7 or 10 <= 10) # Resultado: True
