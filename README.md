# Awesome Parser Generators

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Parser generators, Parser Combinators, Parsing libraries and ready parsers list
The most preferred tools by author are bold

[//]: # ([Optional: logo/illustration — centered or top-right, links to a relevant site])

## Contents

- [Lexer and Parser Generators](#lexer-and-parser-generators)
    - [Multiple targets](#multiple-targets)
    - [Developing](#developing)
    - [C bindings](#c-bindings)

## Lexer and Parser Generators

Tools are rated 0-10 on each axis:

| # | Axis |
|---|------|
| 1 | Entry point |
| 2 | Modern syntax and technologies |
| 3 | Production state |
| 4 | Performance |
| 5 | Community support |

### Multiple targets

| Tool | Description | Entry Point | Modern | Production state | Performance | Community Support |
|------|-------------|---|---|---|---|---|
| [ANTLR](https://github.com/antlr/antlr4#readme) | One of the most powerful general-purpose tool with good abstractions | 6 | 9 | 10 | 5 | 10 |
| [Ragel](https://github.com/adrian-thurston/ragel#readme) | Lexer state machine generator for Assembly, C, C++, Java, Go | 8 | 10 | 9 | 10 | 7 |

### Developing

| Tool | Description | Entry Point | Modern | Production state | Performance | Community Support |
|------|-------------|---|---|---|---|---|
| [ISPA](https://github.com/Sinfolke/ispa-parser-generator#readme) | High abstraction, new generator | 8 | 10 | 5 | 9 | 0 |

### C bindings

| Tool | Description | Entry Point | Modern | Production state | Performance | Community Support |
|------|-------------|---|---|---|---|---|
| [Tree Sitter](https://github.com/tree-sitter/tree-sitter#readme) | Incremental generator, the best suitable to parse any major programming language | 9 | 9 | 9 | 9 | 10 |
| [Flex](https://github.com/westes/flex#readme) | high-speed lexer generator with C/C++ embeddings | 9 | 4 | 10 | 10 | 10 |
| [Bison](https://github.com/akimd/bison#readme) | high-speed LALR parser generator with C/C++ embeddings | 9 | 4 | 10 | 10 | 10 |
| [PackCC](https://github.com/arithy/packcc#readme) | generator to C with direct code embeddings | 9 | 4 | 8 | 10 | 7 |

## Parser Combinators and libraries

### C++

| Tool | Description | Entry Point | Modern | Production state | Performance | Community Support |
|------|-------------|---|---|---|---|---|
| [Boost.spirit](https://github.com/boostorg/spirit#readme) | Part of Boost collection | 6 | 9 | 10 | 5 | 10 |
| [PegTL](https://github.com/taocpp/PEGTL#readme) | Peg-style | 8 | 10 | 9 | 10 | 7 |
| [lexy](https://github.com/foonathan/lexy#readme) | uses an operator based DSL instead of inheriting from templated classes as PEGTL does | 8 | 10 | 9 | 10 | 7 |


## Contributing

See [contributing.md](contributing.md).

## Footnotes

(anything extra that doesn't fit elsewhere)