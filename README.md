# Regras de Divisibilidade como Caminhadas em Grafos Finitos

Este repositório contém um aplicativo interativo para explorar regras de divisibilidade por meio de caminhadas em grafos finitos. A proposta articula aritmética modular, representação gráfica e visualização dinâmica, permitindo que professores e estudantes investiguem como os restos de uma divisão podem ser organizados em um grafo.

O aplicativo foi desenvolvido como material complementar ao artigo **“Regras de divisibilidade como caminhadas em grafos finitos”**.

## Ideia matemática

Para um divisor (n), consideramos os restos possíveis da divisão por (n):

[
0,1,2,\ldots,n-1.
]

Cada resto é representado por um vértice do grafo. As setas indicam operações aritméticas simples sobre esses restos. Em particular, o aplicativo permite visualizar o efeito da multiplicação por 10 e da adição de algarismos, mostrando como um número pode ser lido como uma caminhada em um grafo finito.

Assim, uma regra de divisibilidade deixa de ser apenas um procedimento memorizado e passa a ser interpretada como um percurso em uma estrutura visual.

## Objetivos didáticos

O aplicativo foi concebido para apoiar:

* a exploração de regras de divisibilidade;
* a compreensão de restos e congruências;
* a visualização de padrões em aritmética modular;
* a construção de grafos simples com papel e lápis;
* a discussão de conexões entre aritmética, grafos e pensamento visual.

## Construção com papel e lápis

O uso do aplicativo não é indispensável. Professores e estudantes podem construir os grafos manualmente.

Para um divisor (n):

1. desenhe (n) vértices, identificados pelos restos (0,1,\ldots,n-1);
2. disponha os vértices, preferencialmente, em círculo;
3. desenhe as setas que representam a soma de uma unidade;
4. desenhe as setas internas associadas à multiplicação por 10, ligando cada resto (r) ao resto de (10r) na divisão por (n).

Por exemplo, para (n=7), a seta que sai de (1) chega em (3), pois (10\cdot 1=10) deixa resto (3) na divisão por (7). A seta que sai de (2) chega em (6), pois (20) deixa resto (6). Repetindo esse procedimento para todos os restos, obtém-se o grafo completo.

## Como usar

Abra o arquivo principal do aplicativo em um navegador moderno.

Se o repositório estiver publicado pelo GitHub Pages, o aplicativo poderá ser acessado diretamente pelo endereço:

```text
INSERIR_AQUI_O_LINK_DO_GITHUB_PAGES
```

Também é possível baixar ou clonar este repositório e abrir o arquivo `index.html` localmente.

## Tecnologias utilizadas

* HTML
* CSS
* JavaScript

## Licença

Este projeto está disponibilizado sob a licença MIT.

Isso significa que o código pode ser usado, copiado, modificado e redistribuído, desde que sejam preservados o aviso de copyright e a licença original.

## Autor

Humberto José  Bortolossi
Universidade Federal Fluminense — UFF

## Como citar

Caso utilize este aplicativo em atividades didáticas, formações, materiais ou pesquisas, cite o artigo associado e este repositório.

```text
BORTOLOSSI, Humberto. Regras de divisibilidade como caminhadas em grafos finitos. Aplicativo interativo. Disponível em: INSERIR_AQUI_O_LINK_DO_REPOSITORIO.
```
