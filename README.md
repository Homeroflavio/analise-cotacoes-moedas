# Análise de Cotações de Moedas

Projeto desenvolvido em Python para consultar, organizar e analisar cotações de moedas estrangeiras em relação ao Real Brasileiro (BRL).

## Moedas analisadas

- Dólar Americano (USD)
- Euro (EUR)
- Libra Esterlina (GBP)
- Iene Japonês (JPY)
- Peso Argentino (ARS)

Durante a coleta, o Peso Argentino (ARS) não retornou registros disponíveis no período analisado.

## Período analisado

22/04/2026 até 20/05/2026

## Objetivo

O objetivo do projeto é realizar uma análise exploratória das cotações de moedas, gerando arquivos CSV, gráficos individuais, gráfico comparativo, variação percentual e análise de correlação entre as moedas.

## Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab

## Arquivos gerados

Foram gerados arquivos CSV com as séries históricas das moedas:

- `serie_USD.csv`
- `serie_EUR.csv`
- `serie_GBP.csv`
- `serie_JPY.csv`

Também foram geradas visualizações gráficas:

- Série comparativa das moedas
- Gráficos individuais por moeda
- Variação percentual no período
- Correlação entre as moedas

## Resumo estatístico

### Dólar Americano (USD)
- Mínimo: R$ 4.8905
- Máximo: R$ 5.0708
- Média: R$ 4.9665

### Euro (EUR)
- Mínimo: R$ 5.7440
- Máximo: R$ 5.8963
- Média: R$ 5.8131

### Libra Esterlina (GBP)
- Mínimo: R$ 6.6208
- Máximo: R$ 6.7735
- Média: R$ 6.7121

### Iene Japonês (JPY)
- Mínimo: R$ 0.0310
- Máximo: R$ 0.0320
- Média: R$ 0.0314

## Conclusão

A análise permitiu observar o comportamento das principais moedas estrangeiras no período analisado. Foram gerados dados tratados, gráficos comparativos e indicadores estatísticos que ajudam a entender a variação das cotações em relação ao Real Brasileiro.

O projeto demonstra o uso de Python para coleta, tratamento, análise e visualização de dados financeiros.
