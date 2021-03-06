### [Nbviewer](https://nbviewer.jupyter.org/github/roman-tekarev/yandex-praktikum-projects/blob/main/taxi-orders/taxi-orders.ipynb)

## Прогнозирование заказов такси

### Задача:  
Обучить модель для предсказания количества заказов такси на следующий час.

### Данные:   
Данные с количеством заказов такси каждые 10 минут.

### Используемые библиотеки:  
Pandas, Matplotlib, statsmodels, Seaborn, Sklearn, LightGBM

### Вывод
Изучены и подготовлены исторические данные о заказах такси в аэропортах. Произведено ресемплирование по часу, заменены индексы.  
Данные были проанализированы, выявлена ежедневная сезонная составляющая.  
Было обучено четыре модели (линейная регрессия, решающее дерево, случайный лес, градиентный бустинг) и методом случайного поиска были подобраны оптимальные гипермапараметры.  
Все обученные модели были поверены на тестовой выборке. Самым лучшим качеством (RMSE=44.16) обладает модель градиентного бустинга.  
