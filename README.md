# Дипломный проект. Учебный кейс «Модель прогнозирования стоимости жилья для агентства недвижимости»

## Оглавление
1. Описание проекта

2. Какой кейс решаем?

3. Краткая информация о данных

4. Этапы работы над проектом

5. Результаты

6. Выводы

### 1. Описание проекта

Предстоит решить настоящую задачу машинного обучения, направленную на оптимизацию сервисов и бизнес-процессов. Мы построим модель, которая будет предсказывать стоимость недвижимость по его характеристикам.

**Бизнес-задача**: разработать сервис для предсказания стоимости домов на основе истории предложений.

**Техническая задача** для вас как для специалиста в Data Science: разработать модель, которая позволила бы обойти конкурентов по скорости и качеству совершения сделок.


### 2. Какой кейс решаем?

**Цели проекта**
1. Сформировать набор данных на основе нескольких источников информации.
2. Спроектировать новые признаки с помощью Feature Engineering и выявить наиболее значимые при построении модели.
3. Исследовать предоставленные данные и выявить закономерности.
4. Построить несколько моделей и выбрать из них ту, которая показывает наилучший результат по заданной метрике.
5. Спроектировать процесс предсказания длительности поездки для новых данных.
6. Развернуть модель и написать веб-сервер на Flask.

**Метрика качества**
- Выполнены цели проекта
- Соблюдены и выполнены все этапы проекта с заданиями, представлены обоснования и графики
- Сделаны выводы на всех этапах проекта
- Решение размещено на Git hub
- Выполнен тестовый сабмит на вебсервер

**Что практикуем**
- Навыки работы с несколькими источниками данных
- Генерации признаков
- Разведывательный анализ и визуализация данных, 
- Отбор признаков 
- Построение моделей машинного обучения


### 3. Краткая информация о данных
- Датасет содержит данные об объектах недвижимости США на [ресурсе](https://drive.google.com/file/d/11-ZNNIdcQ7TbT8Y0nsQ3Q0eiYQP__NIW/view?usp=share_link) 
- Учебный кейс Модель прогнозирования стоимости жилья для агентства недвижимости Часть 1.ipynb - Jupiter Notebook с проектом
- Учебный кейс Модель прогнозирования стоимости жилья для агентства недвижимости Часть 2.ipynb - Jupiter Notebook с проектом
- README.md - описание проекта
- get_city_inf.csv - спарсенные данные
- server.py - сервер на Flask
- client.py - клиент для тестирования

- сериализованная модель(model.pkl) 


### 4. Этапы работы над проектом
1. Первичная обработка данных

В рамках этой части  предстоит сформировать набор данных на основе предложенных источников информации, а также обработать пропуски и выбросы в данных.

2. Разведывательный анализ данных (EDA)

Необходимо будет исследовать данные, нащупать первые закономерности и выдвинуть гипотезы.

3. Отбор и преобразование признаков

На этом этапе перекодируем и преобразуем данные таким образом, чтобы их можно было использовать при решении задачи регрессии — для построения модели.

4. Решение задачи регрессии: линейная регрессия и деревья решений

На данном этапе  построим свои первые прогностические модели и оценим их качество. Тем самым  создадим так называемый baseline, который поможет ответить на вопрос: «Решаема ли вообще представленная задача?»

5. Решение задачи регрессии: ансамбли моделей и построение прогноза

На заключительном этапе сможем доработать своё предсказание с использованием более сложных алгоритмов и оценить, с помощью какой модели возможно сделать более качественные прогнозы.

 
### 5. Результаты
Решена задача регрессии, с подобранной оптимальной моделью и лучшей метрикой. 


### 6. Выводы
Задачи проекта выполнены полностью с соблюдением всех этапов. Полные выводы по каждому этапу сформированы в Учебный кейс Модель прогнозирования стоимости жилья для агентства недвижимости. 
 







