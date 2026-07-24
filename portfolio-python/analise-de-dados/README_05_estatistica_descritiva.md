# Estatística Descritiva com pandas

## O que este notebook demonstra

Como calcular e interpretar as principais medidas estatísticas de um conjunto de dados usando pandas e numpy, aplicando os conceitos a dados reais carregados de planilhas externas.

## Conceitos abordados

- Leitura de dados com `pd.read_csv()` a partir de URLs
- Medidas de tendência central: média (`mean`), mediana (`median`), moda (`mode`)
- Medidas de dispersão: mínimo, máximo, amplitude, variância (`var`), desvio padrão (`std`)
- Percentis e quartis com `np.percentile`
- Resumo estatístico completo com `describe()`
- Criação de novas colunas em DataFrames com operações vetorizadas
- Visualizações: histogramas (`hist`) e boxplots (`boxplot`)

## Principais aprendizados

Média e mediana podem divergir significativamente quando os dados têm valores extremos — a mediana é mais robusta a outliers. O boxplot é uma forma eficiente de visualizar a dispersão e identificar valores atípicos. O `describe()` do pandas entrega as principais medidas descritivas em uma única chamada.
