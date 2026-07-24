# Entrada de Dados com Python

## O que este notebook demonstra

Como receber dados digitados pelo usuário durante a execução de um programa, e como converter esses dados para o tipo numérico correto antes de realizar cálculos.

## Conceitos abordados

- Função `input()` para leitura de dados do usuário
- Por que `input()` retorna texto por padrão e o que acontece ao somar strings
- Conversão de tipos: `float()` para números decimais e `int()` para inteiros
- Formas equivalentes de converter e atribuir em uma ou duas linhas

## Principais aprendizados

O operador `+` aplicado a strings as concatena em vez de somá-las — `"10" + "10"` resulta em `"1010"`, não em `20`. Para operar matematicamente com valores digitados pelo usuário, é necessário converter explicitamente com `float()` ou `int()`. A forma mais comum e concisa é `float(input("mensagem"))` em uma única linha.
