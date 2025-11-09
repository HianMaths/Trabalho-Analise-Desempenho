### Análise de Desempenho de Estruturas de Dados em Java
**Introdução**

Este trabalho tem como objetivo comparar o desempenho de diferentes estruturas de dados **Vetores, Árvores Binárias de Busca (ABB) e Árvores AVL**, em operações de **inserção e busca**, utilizando conjuntos de dados de tamanhos variados e diferentes ordens de inserção **(ordenada, inversa e aleatória)**.

Todos os algoritmos e estruturas foram implementados do **zero, sem uso de bibliotecas externas**, priorizando **códigos simples e/ou recursivos**, para reforçar o aprendizado sobre a complexidade e funcionamento interno dessas estruturas.

**Estrutura das pastas**

````
Trabalho-Analise-Desempenho/
│
├── src/
│ ├── vetor/
│ │ ├── Vetor.java → Implementação de vetor com inserção e busca
│ │ ├── OrdenacaoSimples.java → BubbleSort e InsertionSort
│ │ └── OrdenacaoAvancada.java → MergeSort e QuickSort
│ │
│ ├── arvore/
│ │ ├── No.java → Classe representando um nó
│ │ ├── ArvoreBinaria.java → Árvore Binária de Busca (ABB)
│ │ └── ArvoreAVL.java → Árvore AVL auto-balanceada
│ │
│ ├── utils/
│ │ ├── GeradorDados.java → Gera conjuntos de dados
│ │ └── Cronometro.java → Mede tempo de execução
│ │ 
│ │
│ ├── testes/
│ │ └── TesteDesempenho.java → Executa todos os testes
│ │
│ └── Main.java → Classe principal
│
├── resultados/ → Arquivos CSV com resultados
│ ├── tempos_insercao.csv
│ ├── tempos_busca.csv
│ └── tempos_ordenacao.csv
│
├── relatorio/ → Relatório final em PDF
│ └── Relatorio_Analise.pd         
|
└── Readme
````