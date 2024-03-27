# Programação lógica com Prolog 
## Características do Prolog
-  Um programa Prolog é um coleção de procedimentos (simples).
-  Dados são procedimentos simples – fatos ou regras.
- Regras suportam recursividade.
- Prolog não tem comandos de atribuição.
- Prolog não faz distinção entre parâmetros reais e parâmetros formais
- Prolog tem tipos dinâmicos
- O escopo de uma variável é a linha (regra ou fato) que a contém.
- A idéia em Prolog é dizer ao computador o quê queremos computar e
não como fazer (DECLARATIVA).
- O algoritmo de unificação (solução) é sempre o mesmo. </br>

- Fatos é uma meio de declarar relações que existem entre objetos:</br>
<b>cidade(salvador).</b></br>
- Regras permitem a definição de novas relações a partir de relações existentes.</br>
Elas têm a forma: <b>B :- A1,A2,...,AN. </b></br>
#
se (:-) e(,) ou(;). </b>

Par consultar ou "fazer uma pergunta" é feito da seguinte forma: </b>
<b>?- estado(bahia). </b></b>

Testar código em: https://swish.swi-prolog.org/example/prolog_tutorials.swinb
