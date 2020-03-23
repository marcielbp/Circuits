<script>
  MathJax = {
    tex: {inlineMath: [['$', '$'], ['\\(', '\\)']]}
  };
  </script>
  <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

   <script src="https://cdn.jsdelivr.net/npm/mermaid@8.4.0/dist/mermaid.min.js"></script>
 <script>mermaid.initialize({startOnLoad:true});</script>


# PRÁTICA 03 - CONSTRUÇÃO DE CIRCUITOS COMBINACIONAIS USANDO SIMULADOR

[Voltar à home](../)
[Aula Anterior](./pr02.md) - [Próxima Aula](./pr04.md)

## OBJETIVOS

- Resolução de problemas práticos utilizando circuitos lógicos;
- Apresentar a metodologia de projeto de circuitos digitais com ferramentas de simplificação algébrica;

## Material Necessário:

Simuladores:
- [Logic Circuit Simulator](https://marcielbp.github.io/Logic-Circuit-Simulator/)
- [Circuitverse](https://circuitverse.org/simulator)

Durante o nosso estudo até agora, nos dedicamos à representação e simplificação de grandezas digitais. Agora, buscaremos a aplicação dos conceitos da eletrônica digital na solução de problemas práticos utilizando a classe de circuitos chamados **combinacionais**.

Um circuito combinacional é aquele em que as saı́das dependem única e exclusivamente das combinações entre as variáveis de entrada; Para a elaboração desses circuitos a partir de processos reais, normalmente seguimos a seguinte sequência de passos:

1.  Problema real - Problema prático que visa solução usando o circuito combinacional;
2.  Visão geral de variáveis e convenções - Definição de quais são as entradas e saı́das do problema;
3.  Tabela verdade - Expressão que mostra todas as possı́veis saı́das para todas as entradas possı́veis;
4.  Expressão mı́nima - Simplificação da tabela da verdade para uma solução ótima;
5.  Solução do problema - Hardware que soluciona o problema real em termos de entradas *booleanas*.


## PROBLEMA 1

Uma fábrica necessita de uma sirene para indicar o fim do expediente. Esta sirene deve ser tocada em uma das seguintes condições:

-   Já passa das cinco horas e todas as máquinas estão desligadas.
-   É sexta-feira, a produção do dia foi atingida e todas as máquinas estão desligadas.

Projete um circuito que controle a sirene atribuindo as seguintes variáveis *booleanas*. Preencha sua tabela-verdade.

- A - Já passa das cinco horas.
- B - Todas as máquinas estão desligadas.
- C - É sexta-feira.
- D - Produção do dia foi atendida.
- S - Tocar a Sirene.


1. Determine a expressão lógica para o circuito acima:

2. Implemente o circuito combinacional utilizando o simuladores [Logic Circuit Simulator](https://marcielbp.github.io/Logic-Circuit-Simulator/) e  [Circuitverse](https://circuitverse.org/simulator)

### PROBLEMA 2

Uma companhia instituiu o seguinte controle para o acesso de seus três
estacionamentos. Cada empregado tem um cartão que deve ser inserido numa
brecha especial que existe em cada portão. O portão só abre se o
empregado estiver autorizado a usar o estacionamento.



![](./pr03/media/image8.png)

Escreva o mapa-K para as três entradas $x_1$, $x_2$ e $x_3$, representar a expressão lógica do circuito e implemente em protoboard.

| EXPRESSÃO LÓGICA  |
|  :-: |
| _____________________________|


Represente o diagrama do circuito usando portas lógicas. Em seguida, implemente o circuito combinacional utilizando o simuladores [Logic Circuit Simulator](https://marcielbp.github.io/Logic-Circuit-Simulator/) e  [Circuitverse](https://circuitverse.org/simulator)

## PÓS LABORATÓRIO - RELATÓRIO

1.  Envie os circuitos combinacionais implementados pelo SIGAA **em um único arquivo docx ou pdf** até o dia 27/03/2020.
