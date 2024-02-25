# Прогнозирование заказов такси
В первой части проекта была выполнена подготовка данных: загрузка и вывод данных, ресемплирование и создание признаков.
Во второй части были проанализированы данные.
В третьей части были обучены разные модели и рассчитаны RMSE на тестовой выборке.Ниже приведены результаты:

Результаты качества моделей RMSE: 
Dummy Regression	 84.7
Desicion Tree      47.8
Random Forest      45.7
Linear Regression	 51.2
XGBoost	           50.0
CatBoost	         48.5
LGBoost            44.2
						
Таким образом, для прогнозирования количества заказов такси на следующий час рекомендуется модель LGBoost с качеством RMSE=44.2.
![image](https://github.com/NikBaybal/Taxi/assets/117065495/7d34ff4e-bee8-4be8-a7fa-2165d7d8b17d)
