# Gráficos com Matplotlib e NumPy

## O que este notebook demonstra

Como criar gráficos de funções matemáticas em Python usando matplotlib para visualização e numpy para geração de vetores numéricos. Os exercícios partem de pontos simples e evoluem até múltiplas curvas com customizações.

## Conceitos abordados

- `matplotlib.pyplot`: função `plot`, exibição com `show`
- Customização de gráficos: cores, marcadores, estilos de linha (`'r'`, `'o'`, `'.-'`)
- Títulos, rótulos de eixo (`xlabel`, `ylabel`), grade (`grid`) e legendas (`label`, `legend`)
- `numpy.arange`: geração de vetores com início, fim e incremento
- Plotagem de funções matemáticas: polinômios, `sin`, `cos`, `sqrt`
- Múltiplas curvas em um mesmo gráfico

## Principais aprendizados

O incremento do `np.arange` controla a suavidade da curva — incrementos menores produzem gráficos mais contínuos. Funções como `np.sin` e `np.cos` operam diretamente sobre vetores inteiros, sem necessidade de laços. Múltiplas chamadas ao `plt.plot` antes do `plt.show` sobrepõem as curvas no mesmo gráfico.
