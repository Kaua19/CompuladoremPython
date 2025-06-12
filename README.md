# Analisador Léxico e Sintático para Subconjunto da Linguagem C

Este projeto implementa um analisador léxico e sintático simples para um subconjunto da linguagem C. Ele permite ler um arquivo `.c` ou `.txt`, identificar e classificar tokens, além de validar a estrutura sintática básica de programas escritos em C.

---

## Funcionalidades

- Leitura de código-fonte via interface gráfica para seleção de arquivo (Tkinter).
- Análise léxica, identificando:
  - Palavras-chave (`int`, `if`, `else`, `while`, `for`, etc.)
  - Identificadores e nomes de variáveis
  - Operadores aritméticos e relacionais (`+`, `-`, `*`, `/`, `==`, `<`, `>`, etc.)
  - Números (inteiros)
  - Strings (delimitadas por aspas duplas)
  - Símbolos especiais (`{}`, `()`, `;`, `,`, etc.)
- Análise sintática para:
  - Função principal `main`
  - Declarações de variáveis e vetores
  - Atribuições e expressões aritméticas
  - Estruturas de controle (`if`, `else`, `while`, `do while`, `for`)
  - Comandos `scanf`, `printf` e `return`
- Geração de mensagens de erro léxico e sintático com indicação da linha.

---

## Tecnologias

- Python 3
- Biblioteca Tkinter para seleção de arquivos

---

