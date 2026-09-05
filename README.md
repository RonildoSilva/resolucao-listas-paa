# Resolução das listas de PAA

> Resoluções das listas semanais e dos trabalhos da disciplina de Projeto e Análise de Algoritmos da pós-graduação (2020.2), em Python e em relatórios HTML.

![status](https://img.shields.io/badge/status-concluído-success) ![python](https://img.shields.io/badge/Python-3-blue) ![mathjax](https://img.shields.io/badge/relatórios-HTML%20%2B%20MathJax-lightgrey)

## Sobre
Cada lista (`r01` a `r12`) foi resolvida em notebook e exportada para HTML com fórmulas renderizadas por MathJax. Os algoritmos discutidos foram implementados em Python: BFS, coloração de grafos, pontes e componentes conexos, Dijkstra com heap, subsequência comum máxima, programação dinâmica e backtracking. A pasta `trabalho` reúne as três submissões do trabalho final, que compara Floyd-Warshall com `n` execuções de Dijkstra (o código final está no repositório [paa-pcomp-trabalhos](https://github.com/RonildoSilva/paa-pcomp-trabalhos)).

## Estrutura de pastas
```text
lista01.html                 primeira lista
resolucao/
├── r01.html … r12.html      resoluções semanais
├── *.py                     bfs, coloracao_grafo, scm, prefixo, jogo_cartas, matriz_ordenada, print_nearly
├── r06/, r09/               scripts das listas 6 e 9 (pontes, componentes)
├── Semana04/, 1b_*, 1c_*    análises de tempo de algoritmos
└── trabalho/sub01..sub03    descrição, avaliação teórica e avaliação empírica (Floyd x Dijkstra)
```

## Como executar
Abra os arquivos `.html` no navegador. Os scripts rodam com `python3 resolucao/<arquivo>.py`.

## Status
Concluído. Material acadêmico; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
