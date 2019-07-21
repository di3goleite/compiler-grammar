# Gramática do Compilador

Gramática fatorada à esquerda, sem recursão à esquerda, respeitando a precedência e associatividade dos operadores aritméticos, lógicos e relacionais, utilizando o software GOLD Parser Builder.

## Project Structure
```
.
├── grammars
│   ├── commands/
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── commands.grm
│   ├── constants
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── constants.grm
│   ├── expressions
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── expressions.grm
│   ├── main
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── main.grm
│   ├── methods
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── methods.grm
│   ├── program
│   │   ├── tests/test01.txt
│   │   ├── README.md
│   │   └── program.grm
│   └── variables
│       ├── tests/test01.txt
│       ├── README.md
│       └── variables.grm
├── tests/
│   └── test01.txt
├── README.md
└── main.grm
```

## Project Members and their Roles

* Camille - Gerente e [principal](/grammars/main)
* Diego e Gabriel - [comandos](/grammars/commands) (se, entao, senao, enquanto, escreva, leia)
* Ricardo e Reinildo - [constantes](/grammars/constants) e [variaveis](/grammars/variables)
* Carlos e Daniel - [metodos](/grammars/methods), [programa](/grammars/program), [expressoes](/grammars/expressions)
