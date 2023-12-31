# Проект 2. Анализ данных вакансий c сайта HeadHunter.ru

## Оглавление  
[1. Описание проекта](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Описание-проекта)  
[2. Какой кейс решаем](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Результат)    
[6. Выводы](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Выводы) 

### Описание проекта    
У нас есть база данных с таблицей вакансий и сопутствующими таблицами. Нам хотелось бы создать модель машинного обучения, которая будет рекомендовать вакансии клиентам компании, претендующим на позицию Data Scientist.  Сначала нам необходимо понять, что из себя представляют данные и насколько они соответствуют целям проекта. Эта часть работы над ML-проектом называется Data Understanding, или анализ данных.


:arrow_up:[к оглавлению](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Оглавление)


### Какой кейс решаем    
С помощью связки SQL + Python в Jupyter Notebook, написать запросы на SQL, сделать запрос через    Python и исследовать предоставленные данные выдвинуть гипотезы.

**Условия соревнования:**  
Использовать только следующие библиотеки и приложения:
- Jupyter Notebook.
- SQL запросы.
- Python базовые функций (переменные, основные структуры данных (списки, словари, множества), циклы, функции), Numpy, Pandas.
- Графические библиотеки для построения графиков (seaborn, matplotlib, plotly).

**Метрика качества**     
- Решение оформляется в соответствии с шаблоном в JN.
- Каждое задание выполняется в отдельной ячейке, выделенной под задание.
- Код для каждого задания оформляется в одной-двух jupyter-ячейках.
- Код SQL и Python должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий.
- Графики должны содержать название, отражающее их суть, и подписи осей.
- Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке.

**Что практикуем**     
- Владение базовыми знаниями python,
- Владение базовыми запросами SQL
- Базовый анализ структуры данных,
- Построение графиков

### Краткая информация о данных
Нам доступны в БД (база данных) с 5 таблицами.
- VACANCIES Таблица хранит в себе данные по вакансиям и содержит 10 столбцов, связанна с таблицами - AREAS, EMPLOYERS.
- AREAS Таблица-справочник, которая хранит код региона и его название, связанна с таблицей VACANCIES.
- EMPLOYERS Таблица-справочник со списком работодателей, содержит 3 столбца, связанна с таблицей VACANCIES, EMPLOYERS_INDUSTRIES
- INDUSTRIES Таблица-справочник вариантов сфер деятельности работодателей содержит 2 столбца и связанна с таблицей EMPLOYERS_INDUSTRIES.
- EMPLOYERS_INDUSTRIES Дополнительная таблица, которая существует для организации связи между работодателями и сферами их деятельности. Эта таблица нужна нам, поскольку у одного работодателя может быть несколько сфер деятельности (или работодатели могут вовсе не указать их). Для удобства анализа необходимо хранить запись по каждой сфере каждого работодателя в отдельной строке таблицы.
Содержит 2 столбца, связанна с таблицами EMPLOYERS, INDUSTRIES.

:arrow_up:[к оглавлению](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Оглавление)


### Этапы работы над проектом  
1. Ознакомление с кейсом и его условиями; 
2. знакомство с данными;
3. предварительный анализ данных;
4. детальный анализ вакансий;
5. анализ работодателей;
6. предметный анализ;
7. Оформление проекта;

:arrow_up:[к оглавлению](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Оглавление)


### Результат:  
- По результатам был сформирован и оформлен ноутбук.
- Были сформированы запросы SQL и полученна информация по ним. 
- Проведен анализ данных и по ним сделанны вывводы как общие так и частные. 

:arrow_up:[к оглавлению](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Оглавление)


### Выводы:  
- Поставленные выше задачи были выполнены.
- Были показаны навыки владения запросами SQL, которые были реализованны через Python , а также отдельными библиотеками.
- Был проведен анализ 'живых' данных, по ним сделанны выводы.
- По итогам оформлен ноутбук

:arrow_up:[к оглавлению](https://github.com/Serstefs/sfds/tree/main/Progect_2/README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами