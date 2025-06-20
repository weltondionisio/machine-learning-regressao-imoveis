# Modelos de Regressão para Previsão de Preço de Casas

Este projeto utiliza diferentes modelos de regressão para prever o preço de casas utilizando o dataset [House Prices](https://www.kaggle.com/datasets/lespin/house-prices-dataset) do Kaggle. O objetivo é comparar o desempenho de modelos clássicos e de machine learning, como Regressão Linear, Random Forest e XGBoost.

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Como Executar](#como-executar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Modelos Utilizados](#modelos-utilizados)
- [Resultados](#resultados)
- [Requisitos](#requisitos)
- [Licença](#licença)

---

## Sobre o Projeto

O notebook `regression_models.ipynb` apresenta um pipeline completo de análise e modelagem preditiva, incluindo:
- Carregamento automático do dataset via `kagglehub`
- Análise exploratória dos dados
- Pré-processamento (tratamento de nulos, codificação de variáveis categóricas)
- Treinamento e avaliação de três modelos de regressão
- Visualização dos resultados e comparação de métricas

## Como Executar

1. **Clone este repositório**
2. **Instale as dependências**  
   Recomenda-se o uso de um ambiente virtual:
   ```sh
   pip install -r requirements.txt
   ```
3. **Configure sua API do Kaggle**  
   Siga as instruções do [Kaggle API](https://www.kaggle.com/docs/api) e coloque o arquivo `kaggle.json` na pasta apropriada.
4. **Execute o notebook**  
   Abra o arquivo `regression_models.ipynb` no VS Code ou Jupyter Notebook e execute as células.

## Estrutura do Projeto

```
.
├── regression_models.ipynb
├── requirements.txt
└── README.md
```

## Modelos Utilizados

- **Regressão Linear**  
  Modelo base para comparação.
- **Random Forest Regressor**  
  Modelo de ensemble baseado em árvores de decisão.
- **XGBoost Regressor**  
  Modelo gradient boosting eficiente e robusto.

## Resultados

O notebook exibe:
- Métricas de avaliação: MAE, MSE, R²
- Gráficos de dispersão, resíduos e importância das variáveis
- Tabela comparativa dos modelos

## Requisitos

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- kagglehub

Instale tudo com:
```sh
pip install -r requirements.txt
```

## Licença

Este projeto é apenas para fins