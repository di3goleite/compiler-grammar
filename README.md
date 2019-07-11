# Gramática do Compilador

Gramática fatorada à esquerda, sem recursão à esquerda, respeitando a precedência e associatividade dos operadores aritméticos, lógicos e relacionais, utilizando o software GOLD Parser Builder.

## Project Structure
```
.
├── README.md
├── grammars
│   ├── commands
│   │   ├── README.md
│   │   ├── commands.grm
│   │   └── tests
│   │       └── test01.txt
│   ├── constants
│   │   ├── README.md
│   │   ├── constants.grm
│   │   └── tests
│   │       └── test01.txt
│   ├── methods
│   │   ├── README.md
│   │   ├── methods.grm
│   │   └── tests
│   │       └── test01.txt
│   ├── program
│   │   ├── README.md
│   │   ├── program.grm
│   │   └── tests
│   │       └── test01.txt
│   └── variables
│       ├── README.md
│       ├── tests
│       │   └── test01.txt
│       └── variables.grm
├── main.grm
└── tests
    └── test01.txt
```

## Project Members and their Roles

* Camille - Gerente
* Carlos e Daniel - [metodos](/grammars/methods), [programa, principal](/grammars/program)
* Diego e Gabriel - [comandos](/grammars/commands) (se, entao, senao, enquanto, escreva, leita)
* Ricardo e Reinildo - [constantes](/grammars/constants) e [variaveis](/grammars/variables)

