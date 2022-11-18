Описание проектов
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных".


| Название проекта | Задачи | Используемые библиотеки | Презентация выводов по задачам |
| :--------------------- | :---------------------- | :---------------------- |:---------------------- |
| [Музыка больших городов](mus-proj) | Развеять мифы о предпочтениях москвичей и петербуржцев: какую музыку они слушают? Как часто? Влияют ли на это прослушивание какие-то факторы(например, день недели или время суток)?| *pandas* |
| [Исследование надёжности заёмщиков — анализ банковских данных](arrears) | 1.Изучить инфомацию 2.Обработать пропуски и отрицательные значения 4.Получить медианные данные о количестве дней работы(или безработицы) для каждой категории людей. 5.Изучить количество детей в датасете 6.Разделить людей на типы по уровню зарплаты. 7.Определить цели людей для взятия кредита. 8.Обработать похожие цели для более простого чтения датасета. 9.Определить зависимость между наличием детей, уровнем дохода,влиянием разных целей и возвратом кредита в срок.| *pandas* |Люди, которые берут кредит на операции с автомобилем или на дополнительное образование чаще выплачивают кредит, чем люди, которые берут кредит на покупку жилья или проведение свадьбы.Лучше всего обстоят дела у людей, которые имеют либо ноль детей, либо троих.Хуже всего либо 2, либо 4. Зависимость между суммой кредита и его выплатой 8 процентов у 4 категорий, и 7 процентов у "очень богатых".|
| [Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости](apartments) | 1.Изучить информацию о пропусках ;2. Заменить пропущенные значения, где это возможно;3.Изучить типы данных представленные нам в таблице;4.Найти и устранить выбивающиеся значения;5.Посчитать и добавить в таблицу новые данные;6. Провести исследовательский анализ данных;7.Изучить, как быстро или как долго продавались квартиры;8.Изучить существование корреляционных зависимостей, влияющих на продажи.| *pandas*, *math*, *matplotlib.pyplot*, *numpy* |Так как мы потеряли только 3,5 процента информации от исходных данных,мы построили гистограммы для всех полей, которые помогли нам добиться любой полезной информации для понимания успешности продажи квартир.Например, мы взяли поле с количеством этажей, и выявили самый популярный для продажи этаж, это был второй этаж.  Положение 2 этажа наводнило более трехтысячи квартир. Львиная часть данных смогла нами плавно быть переведена в нужный формат.Были заменены пропуски в 11 полях и обработаны аномальные значения. | 
| [Анализ убытков приложения ProcrastinatePRO+](application) | 1.Провести исследовательский анализ данных 2.Провести маркетинговый анализ данных. 3.Оценить окупаемость рекламы 4. Оформить рекомендации для отдела маркетинга| *pandas*, *numpy*, *datetime*, *matplotlib* |Мы разделили наши данные на 3 категории, благодаря такому делению, мы изучили не только привлечение по каналам,ну то есть, успешные приложения и не очень, но еще и расмотрели все данные для каждого устройства, и выявили специфику того региона, в котором приложение  котируется. То что мы расширили рамки исследования с помощью категорий позволило с разных сторон рассмотреть одни и те же процессы и сделать разные выводы. |
| [Исследование данных об инвестиции венчурных фондов в компании-стартапы](fond) | Проанализировать данные с помощью операторов и функций: инструментов SQL.| *SQL* |
| [Проверка гипотез по увеличению выручки в интернет-магазине ](online_store) |1.Приоритизировать гипотезы 2. Провести исследование 3.Выполнить A/B  тестирование по очищенным и неочищенным данным 4.Написать выводы| *pandas*, *datetime*, *numpy*, *matplotlib.pyplot*, *scipy.stats* |Мы сформурировали две гипотезы, одна об отличии конверсии между группами, другая - о различии средних чеков между группами. Мы смогли получить сведения о лидирующей группе в ходе тестирования и не потребовалось повторять эксперимент или проводить исследования по дополнительным данным.Перед тестированием мы провели исследование, благодаря которому и выбрали какой тест будем проводить. Из-за того что в данных много выбивающихся значений, мы выбрали тест Манна-Уитни.
| [ Определение выгодного тарифа для телеком компании](rate) | Проанализировать поведение клиентов и выяснить на основе него: на какой тариф выгоднее сделать акцент в будущем?| *pandas*, *scipy*|
| [Изучение закономерностей, определяющих успешность игр](success) | Определить дальнейшее развитие в игр-индустрии для игры на примере успешных и отрицательных показателей оценок других игр и связанных с ними факторов.| *pandas*, *numpy*, *matplotlib*, *matplotlib.pyplot*, *seaborn*, *scipy*, *matplotlib.lines*, *matplotlib.ticker*|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering) | Определить наилучшее местоположение для открытия заведения.Изучить особенности заведений и ключевые закономерности в данных.| *pandas*, *seaborn*, *matplotlib.pyplot*, *numpy*, *folium*, *plotly.express*, *plotly*, *folium.plugins*, *json* |

