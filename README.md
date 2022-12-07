## Ames-Housing-Dataset-Predictions
Segunda versão do meu modelo preditivo utilizando o Ames Housing Dataset do Kaggle.
Neste modelo utilizei a média com o SimpleImputer nas colunas numéricas. Nas categóricas utilizei One-Hot Encoder.
No modelo em si a melhor escolha, até o momento, foi o XGBRegressor. Fiz diversos testes com RandomForestRegressor, mas o tempo de processamento era muito maior em comparação ao XGBRegressor. A escolha de hiperparâmetros foi a parte mais trabalhosa, mas foi possível reduzir o mean_absolute_error em 1261.51 (o mae do modelo mk1 era 15541.86 e do modelo mk2 foi 14280.35.
