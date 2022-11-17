Описание проектов
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных".


| Название проекта | Задачи | Используемые библиотеки | Презентация выводов по задачам |
| :--------------------- | :---------------------- | :---------------------- |:---------------------- |
| [Музыка больших городов](mus-proj) | Развеять мифы о предпочтениях москвичей и петербуржцев: какую музыку они слушают? Как часто? Влияют ли на это прослушивание какие-то факторы(например, день недели или время суток)?| *pandas* |
| [Исследование надёжности заёмщиков — анализ банковских данных](arrears) | Выяснить влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Какие еще факторы могут быть связаны с успешной выплатой кредита? Установить эти факторы и разобрать их на примере.| *pandas* |
| [Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости](apartments) | 1.Изучить информацию о пропусках ;2. Заменить пропущенные значения, где это возможно;3.Изучить типы данных представленные нам в таблице;4.Найти и устранить выбивающиеся значения;5.Посчитать и добавить в таблицу новые данные;6. Провести исследовательский анализ данных;7.Изучить, как быстро или как долго продавались квартиры;8.Изучить существование корреляционных зависимостей, влияющих на продажи.| *pandas*, *math*, *matplotlib.pyplot*, *numpy* |1.Львиная часть данных смогла нами плавно быть переведена в нужный формат.Были заменены пропуски в 11 полях,и обработаны аномальные значения.2.Мы исправили данные последней цены, потому что цена была либо слишком высокой, либо слишком низкой,
поэтому мы убрали цену, которая явно не отражала реальность.3.Мы отредактировали этаж, определенный в объявлении, если количество этажей в доме было меньше чем указанный в объявлении этаж. 4.Так как мы потеряли только 3,5 процента информации от исходных данных,мы построили гистограммы для всех полей, которые помогли нам добиться любой полезной информации для понимания успешности продажи квартир.5.Например, мы взяли поле с количеством этажей, и выявили самый популярный для продажи этаж, это былвторой этаж.  Положение 2 этажа наводнило более трехтысячи квартир.6. Мы доказали наличие корреляционной зависимости , например, связь между показателями разных помещений с влиянием на продажи квартир. | 
| [Анализ убытков приложения ProcrastinatePRO+](application) | Подобрать лучшую стратегию для развития сайта на основе понимания динамики денежных показателей других схожих сайтов.| *pandas*, *numpy*, *datetime*, *matplotlib* |
| [Исследование данных об инвестиции венчурных фондов в компании-стартапы](fond) | Проанализировать данные с помощью операторов и функций: инструментов SQL.| *SQL* |
| [Проверка гипотез по увеличению выручки в интернет-магазине ](online_store) |Приоритизировать гипотезы и проанализировать результаты. Провести А/B тестирование и проанализировать результаты| *pandas*, *datetime*, *numpy*, *matplotlib.pyplot*, *scipy.stats* |
| [ Определение выгодного тарифа для телеком компании](rate) | Проанализировать поведение клиентов и выяснить на основе него: на какой тариф выгоднее сделать акцент в будущем?| *pandas*, *scipy*|
| [Изучение закономерностей, определяющих успешность игр](success) | Определить дальнейшее развитие в игр-индустрии для игры на примере успешных и отрицательных показателей оценок других игр и связанных с ними факторов.| *pandas*, *numpy*, *matplotlib*, *matplotlib.pyplot*, *seaborn*, *scipy*, *matplotlib.lines*, *matplotlib.ticker*|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering) | Определить наилучшее местоположение для открытия заведения.Изучить особенности заведений и ключевые закономерности в данных.| *pandas*, *seaborn*, *matplotlib.pyplot*, *numpy*, *folium*, *plotly.express*, *plotly*, *folium.plugins*, *json* |

