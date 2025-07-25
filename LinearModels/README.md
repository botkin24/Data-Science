# Проект: Линейные модели в машинном обучении

## Цель: разработать модель машинного обучения, которая поможет фермеру управлять рисками и принимать объективное решение о покупке. 

## Задачи: 


- ### Загрузить и изучить данные из файлов: /datasets/ferma_main.csv; /datasets/ferma_dad.csv; /datasets/cow_buy.csv

    - Файл ferma_main.csv содержит данные о стаде фермера на текущий момент; 
    
    - Файл ferma_dad.csv хранит имя папы каждой коровы в стаде фермера;
    
    - Файл cow_buy.csv — это данные о коровах «ЭкоФермы», которых фермер хочет изучить перед покупкой.


- ### Проверить данные на наличие пропусков и дубликатов. Узнать, корректны ли типы данных у каждого признака. Устранить все проблемы с данными


- ### Провести исследовательский анализ данных
    - Провести статистический анализ всех признаков;
    - Построить графики для каждого признака;
    - Сделать выводы о данных;


- ### Провести корреляционный анализ признаков в датасете ferma_main.csv
    - Изучить взаимосвязь между признаками: рассчитать коэффициенты корреляции между всеми признаками;
    - Построить диаграммы рассеяния scatterplot для признака Удой, кг и всех количественных признаков с учётом значения категориальных признаков;
    - Сделать выводы о взаимосвязи признаков;


- ### Обучить три модели простой линейной регрессии:
    - Обучите на данные из датасета ferma_main.csv первую модель, используя в качестве целевого признак Удой, кг;
    - Подготовить данные с учётом связи входных признаков с целевым и обучить на них вторую модель;
    - Добавить в данные новый признак и обучить на них третью модель;


- ### Создать две прогнозные модели для отбора бурёнок в поголовье:

    - Первая будет прогнозировать возможный удой коровы (целевой признак Удой);
    - Вторая — рассчитывать вероятность получить вкусное молоко от коровы (целевой признак Вкус молока).
