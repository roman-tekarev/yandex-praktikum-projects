### [Nbviewer](https://nbviewer.jupyter.org/github/roman-tekarev/yandex-praktikum-projects/blob/main/telecom-tariff-recomendation/telecom-tariff-recomendation.ipynb)

## Рекомендация тарифов

### Задача:  
Используя предобработанные данные, определить оптимальный тариф для пользователя с оценкой accuracy не менее 0.75

### Данные:   
Данные клиентов оператора сотовой связи

Описание данных  
Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц.   
Известно:  
сalls — количество звонков  
minutes — суммарная длительность звонков в минутах  
messages — количество sms-сообщений  
mb_used — израсходованный интернет-трафик в Мб  
is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0)  

### Используемые библиотеки:  
Pandas, Matplotlib, Sklearn

### Вывод
Обучено три модели.
Полученно значение Accuracy на тестовой выборке 0.793
