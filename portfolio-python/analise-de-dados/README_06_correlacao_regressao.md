# Correlação e Regressão com NumPy

## O que este notebook demonstra

Como identificar e quantificar relações entre variáveis usando correlação de Pearson e regressão com numpy, aplicando os conceitos a conjuntos de dados reais sobre desempenho acadêmico.

## Conceitos abordados

- Coeficiente de correlação de Pearson com `df[coluna].corr()`
- Gráfico de dispersão para visualizar relações entre variáveis
- Regressão linear com `np.polyfit(deg=1)`: cálculo dos coeficientes `a` e `b`
- Plotagem da reta de regressão sobre o gráfico de dispersão
- Coeficiente de determinação R² via correlação ao quadrado e via fórmula direta
- Regressão polinomial com `np.polyfit(deg=2)` e `np.polyfit(deg=3)`

## Principais aprendizados

Correlação mede a força e direção da relação linear entre duas variáveis — valores próximos de 1 ou -1 indicam relação forte, próximos de 0 indicam relação fraca. O R² indica quanto da variação de uma variável é explicada pela outra. Regressão polinomial de grau maior pode se ajustar melhor aos dados, mas corre o risco de overfitting.
