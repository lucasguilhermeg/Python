# Laços de Repetição com Python

## O que este notebook demonstra

Como usar laços `for` e `while` para automatizar tarefas repetitivas, controlar o fluxo de execução com `break`, manipular listas e integrar tudo isso com leitura de planilhas externas e geração de gráficos.

## Conceitos abordados

- Laço `for` com listas fixas e com `range(início, fim, incremento)`
- Laço `while` com condições simples e compostas (`and`)
- Interrupção de laço com `break`
- Listas: criação, acesso por índice (`x[0]`), tamanho com `len`, adição com `append`, concatenação
- Leitura de múltiplas planilhas via loop com pandas
- Construção iterativa de listas de resultados e plotagem com matplotlib

## Principais aprendizados

A posição de inicialização de uma variável dentro ou fora do laço muda completamente o resultado — inicializar dentro reinicia o valor a cada iteração. O `while` é mais adequado quando o número de repetições depende de uma condição dinâmica, como uma senha correta ou um saldo negativo. Listas combinadas com laços permitem acumular resultados ao longo das iterações para plotagem posterior.
