Modelo de regressão para estimar a emissão de carbono de um individuo utilizando a seguinte base de dados do kaggle: https://www.kaggle.com/datasets/dumanmesut/individual-carbon-footprint-calculation

## Análise Exploratória

Features selecionadas com base na correlação com a variavel alvo 'CarbonEmission'

![Screenshot_1](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/5d808c64-ced3-4cde-83a8-1c37a1d94ca1)


## Treinamento

Através da biblioteca Scikit-learn foram utilizados varios modelos ensemble mathods para seleção daquele com melhor resultado

### GradientBoostingRegressor
![GradienteBoosting](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/d32537b8-cca9-4cb7-9a3f-0abe19706181)

### HistGradientBoostingRegressor
![HistGradient](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/b6b9e88e-5924-4d74-8067-ae3e8b1b5376)

### RandomForestRegressor
![RandomFlorest](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/da42d429-cc26-4bdb-9406-ffe6e2931464)

### ExtraTreesRegressor
![ExtraTrees](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/054356e3-312f-4b36-8c92-41237830e3d5)

### AdaBoostRegressor
![AdaBoost](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/bc488fbc-16b4-4b51-bb47-c7ada9cdb364)


## Resultados de Teste

Depois de treinados os modelos performaram em uma base de dados de teste. Seus resultados foram comparados aos dados reais.

![image](https://github.com/EvandroSanches/CarbonEmissionRegression/assets/102191806/b73c35a3-9aac-4f48-b8ac-cb298f5b0cdf)


