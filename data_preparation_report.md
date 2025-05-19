# Relat�rio de Prepara��o dos Dados

## 1. Vis�o Geral
- Dataset original: 143 registros
- Dataset ap�s limpeza: 136 registros
- Conjunto de treino: 108 registros
- Conjunto de teste: 28 registros

## 2. Transforma��es Aplicadas
- Convers�o de datas para formato datetime
- Ajuste do pre�o de combust�vel (divis�o por 1000)
- Ajuste da taxa de desemprego (divis�o por 1000)
- Extra��o de componentes temporais (ano, m�s, semana, dia da semana)
- Cria��o de vari�veis c�clicas para m�s e semana
- Cria��o de features de lag (1, 2 e 4 semanas)
- Cria��o de m�dias m�veis (4 e 8 semanas)
- Normaliza��o de features num�ricas

## 3. Features Finais
### Features Num�ricas Normalizadas:
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
