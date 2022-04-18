# Grammars
## Grammar Overview
Grammar is used to specify legal sentences in a language. Usually grammars are used to check if a program’s syntax is legal but in GE the grammar is used in a generative way, i.e. it’s used to generate individuals in the population. There are many forms of grammar available but a popular option, and the one GE uses, is Backus Naur Form (BNF).

## File Breakdown
grammar.bnf - is the final grammar file used in the implementation. It larger than the other grammar and allows GE to explore more and generate longer individuals .

grammar_old.bnf - is the initial grammar file used in the implementation. It was abandoned due to it being too limiting to allow GE to have a high degree of exploration.
