## Machine Learning

### O objetivo 
Realizar ensaios com algoritmos de Classificação, Regressão e Clusterização, para estudar a mudança do comportamento da performance, a medida que os valores dos principais parâmetros de controle de overfitting e underfitting mudam.

## Algoritmos ensaiados
### Classificação:
Algoritmos: KNN, Decision Tree, Random Forest e Logistic Regression
Métricas de performance: Accuracy, Precision, Recall e F1-Score
### Regressão:
Algoritmos: Linear Regression, Decision Tree Regressor, Random Forest
Regressor, Polinomial Regression, Linear Regression Lasso, Linear
Regression Ridge, Linear Regression Elastic Net, Polinomial Regression
Lasso, Polinomial Regression Ridge e Polinomial Regression Elastic Net
Métricas de performance: R2, MSE, RMSE, MAE e MAPE
### Agrupamento:
Algoritmos: K-Means e Affinity Propagation
Métricas de performance: Silhouette Score

## Ferramentas utilizadas
Python e Scikit-learn

## Etapas
1- Divisão dos dados em treino, teste e validação. 

2- Treinamento dos algoritmos com os dados de treinamento, utilizando os parâmetros “default”.

3- Medir a performance dos algoritmos treinados com o parâmetro default, utilizando o conjunto de dados de treinamento.

4- Medir a performance dos algoritmos treinados com o parâmetro “default”, utilizando o conjunto de dados de validação.

5- Alternar os valores dos principais parâmetros que controlam o overfitting do algoritmo até encontrar o conjunto de parâmetros apresente a melhor performance dos algoritmos.

6- Retreinar o algoritmo com a união dos dados de treinamento e validação, utilizando os melhores valores para os parâmetros de controle do algoritmo. (em alguns casos essa etapa foi pulada)

7- Medir a performance dos algoritmos treinados com os melhores parâmetro, utilizando o conjunto de dados de teste

## Insights
### Insight 1
Os algoritmos baseado em árvores possuem uma performance melhores em todas as métricas, quando aplicados sobre os dados de teste, no ensaio de Classificação.
### Insight 2
A performance dos algoritmos de classificação sobre os dados de validação ficou bem próxima da performance sobre os dados de teste.





