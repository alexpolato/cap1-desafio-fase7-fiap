# Relatório de Preparação dos Dados

## 1. Visão Geral
- Dataset original: 143 registros
- Dataset após limpeza: 136 registros
- Conjunto de treino: 108 registros
- Conjunto de teste: 28 registros

## 2. Transformações Aplicadas
- Conversão de datas para formato datetime
- Ajuste do preço de combustível (divisão por 1000)
- Ajuste da taxa de desemprego (divisão por 1000)
- Extração de componentes temporais (ano, mês, semana, dia da semana)
- Criação de variáveis cíclicas para mês e semana
- Criação de features de lag (1, 2 e 4 semanas)
- Criação de médias móveis (4 e 8 semanas)
- Normalização de features numéricas

## 3. Features Finais
### Features Numéricas Normalizadas:
- Temperature
- Fuel_Price
- CPI
- Unemployment
- Month_sin
- Month_cos
- Week_sin
- Week_cos
- Sales_Lag_1
- Sales_Lag_2
- Sales_Lag_4
- Sales_Rolling_Mean_4
- Sales_Rolling_Mean_8

### Todas as Features:
- Holiday_Flag
- Temperature
- Fuel_Price
- CPI
- Unemployment
- Year
- Month
- Week
- Day_of_week
- Month_sin
- Month_cos
- Week_sin
- Week_cos
- Sales_Lag_1
- Sales_Lag_2
- Sales_Lag_4
- Sales_Rolling_Mean_4
- Sales_Rolling_Mean_8
