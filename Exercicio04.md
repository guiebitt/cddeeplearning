# Criar um modelo para previsão do preço das casas

## Caso 1 (64%) - exercicio04-64.ipynb

### Features selecionadas

#### 11 variáveis:
> waterfront, bedrooms, bathrooms, sqft_living, floors, view, grade, sqft_above, sqft_basement, yr_renovated, sqft_living15

### Métricas de eficiência

- MAE        :  143542.9416433429 
- MSE        :  45821209263.32343 
- RMSE       :  214058.89204451058 
- R2         :  0.6484679365910644
- R2 Ajustado:  0.6477507903192732

O modelo não apresentou um resultado muito bom, com o R2 sendo 0.64 (64% eficiente). As previsões não parecem perfeitas, o MSE penalizou os outliers e o RMSE indicou que os resíduos estão dispersos.

## Caso 2 (73%) - exercicio04-73.ipynb

### Features selecionadas

#### 13 variáveis:
> waterfront, bedrooms, bathrooms, sqft_living, floors, view, grade, sqft_above, sqft_basement, yr_built, yr_renovated, sqft_living15, sqft_lot15

### Métricas de eficiência

- MAE        :  122182.1933723862 
- MSE        :  34035486933.546314 
- RMSE       :  184487.09150926064 
- R2         :  0.7384934676750491 
- R2 Ajustado:  0.7378627469106289

O modelo não apresentou um resultado muito bom, entretanto, melhor que o caso 1. Neste foram considerados mais 2 variáveis diferentes do caso 1: yr_built e sqft_lot15. Com o R2 sendo 0.73 (73% eficiente). As previsões não parecem perfeitas, o MSE penalizou os outliers e o RMSE indicou que os resíduos estão dispersos.



