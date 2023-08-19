# Исследование данных о зарплатах в сфере Data Science 
## Оглавление
[1. Описание проекта](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Описание-проекта)

[2. Какой кейс решаем](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Описание-проекта)

[3. Краткая информация о данных](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Описание-проекта)

[4. Этапы проекта](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Этапы-проекта)

[5. Результаты](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Результаты)

### Описание проекта

HR-агентство изучает тренды на рынке труда в IT. Компания хочет провести исследование на основе данных о зарплатах в сфере Data Science за 2020–2022 годы и получить некоторые выводы.

:arrow_up:[к оглавлению](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Оглавление)

### Какой кейс решаем

Исследуем данные и делаем выводы по полученным результатам. Все рассуждения и выводы должны быть подкреплены визуализациями и проверены с помощью статистического тестирования, являются ли выводы статистически значимыми.
В процессе анализа необходимо:

1. Выяснить, какие факторы влияют на зарплату специалиста Data Scientist.

2. А также ответить на ключевые вопросы HR-агентства:
- Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
- Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?
- Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?
- Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?

Что от нас требуется?

Продемонстрировать использование разных тестов для проверки статистической значимости сделанных выводов:

1. тесты для количественного признака:
- для одной выборки;
- для двух выборок;
- для нескольких выборок;
2. тесты для категориальных признаков.

### Краткая информация о данных

Нам предоставлен набор данных, который содержит 607 строк с данными о зарплатах в сфере Data Science.

Данные содержат следующие столбцы:
* *work_year* - Год, в котором была выплачена зарплата;
* *experience_level* - 	Опыт работы на этой должности в течение года со следующими возможными значениями (EN — Entry-level/Junior, MI — Mid-level/Intermediate, SE — Senior-level/Expert, EX — Executive-level/Director);
* *employment_type* - Тип трудоустройства для этой роли (PT — неполный рабочий день, FT — полный рабочий день, CT — контракт, FL — фриланс);
* *job_title* - Роль, в которой соискатель работал в течение года;
* *salary* - Общая выплаченная валовая сумма заработной платы;
* *salary_currency* - Валюта выплачиваемой заработной платы в виде кода валюты ISO 4217;
* *salary_in_usd* - Зарплата в долларах США (валютный курс, делённый на среднее значение курса доллара США за соответствующий год через fxdata.foorilla.com);
* *employee_residence* - Основная страна проживания сотрудника в течение рабочего года в виде кода страны ISO 3166;
* *remote_ratio* - 	Общий объём работы, выполняемой удалённо. Возможные значения: 0 — удалённой работы нет (менее 20 %), 50 — частично удалённая работа, 100 — полностью удалённая работа (более 80 %);
* *company_location* - Страна главного офиса работодателя или филиала по контракту в виде кода страны ISO 3166.
* *company_size* - 	Среднее количество людей, работавших в компании в течение года (S — менее 50 сотрудников (небольшая компания), M — от 50 до 250 сотрудников (средняя компания), L — более 250 сотрудников (крупная компания)).

Источник датасета: [“Data Science Job Salaries” (kaggle.com)](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)


### Этапы проекта
1. Загрузка и обработка данных.
2. Разведывательный анализ данных.
- Визуальный анализ данных
- Статистический анализ данных 
3. Соответствие выводов бизнес-вопросам.
4. Дополнительное исследование. 


**Условия соревнования:**
- Решение оформляется в Jupyter Notebook.
- Код на Python должны быть читаемыми. 
- Выводы по каждому этапу оформляются в формате Markdown в отдельной ячейке.

### Результаты:
[Ноутбук с выполненными заданиями и выводами](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/Project_DS_Job_Salaries%C2%A0%E2%80%94%20%D0%BA%D0%BE%D0%BF%D0%B8%D1%8F.ipynb)
:arrow_up:[к оглавлению](https://github.com/dariazvonareva/Project_DS_Job_Salaries/blob/main/README.md#Оглавление)