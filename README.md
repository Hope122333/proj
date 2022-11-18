Описание проектов
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных".


| Название проекта | Задачи | Используемые библиотеки | Презентация выводов по задачам |
| :--------------------- | :---------------------- | :---------------------- |:---------------------- |
| [Музыка больших городов](mus-proj) | Развеять мифы о предпочтениях москвичей и петербуржцев: какую музыку они слушают? Как часто? Влияют ли на это прослушивание какие-то факторы(например, день недели или время суток)?| *pandas* |
| [Исследование надёжности заёмщиков — анализ банковских данных](arrears) | 1.Изучить инфомацию 2.Обработать пропуски и отрицательные значения 4.Получить медианные данные о количестве дней работы(или безработицы) для каждой категории людей. 5.Изучить количество детей в датасете 6.Разделить людей на типы по уровню зарплаты. 7.Определить цели людей для взятия кредита. 8.Обработать похожие цели для более простого чтения датасета. 9.Определить зависимость между наличием детей, уровнем дохода,влиянием разных целей и возвратом кредита в срок.| *pandas* |Люди, которые берут кредит на операции с автомобилем или на дополнительное образование чаще выплачивают кредит, чем люди, которые берут кредит на покупку жилья или проведение свадьбы.Лучше всего обстоят дела у людей, которые имеют либо ноль детей, либо троих.Хуже всего либо 2, либо 4. Зависимость между суммой кредита и его выплатой 8 процентов у 4 категорий, и 7 процентов у "очень богатых".|
| [Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости](apartments) | 1.Изучить информацию о пропусках ;2. Заменить пропущенные значения, где это возможно;3.Изучить типы данных представленные нам в таблице;4.Найти и устранить выбивающиеся значения;5.Посчитать и добавить в таблицу новые данные;6. Провести исследовательский анализ данных;7.Изучить, как быстро или как долго продавались квартиры;8.Изучить существование корреляционных зависимостей, влияющих на продажи.| *pandas*, *math*, *matplotlib.pyplot*, *numpy* |Так как мы потеряли только 3,5 процента информации от исходных данных,мы построили гистограммы для всех полей, которые помогли нам добиться любой полезной информации для понимания успешности продажи квартир.Например, мы взяли поле с количеством этажей, и выявили самый популярный для продажи этаж, это был второй этаж.  Положение 2 этажа наводнило более трехтысячи квартир. Львиная часть данных смогла нами плавно быть переведена в нужный формат.Были заменены пропуски в 11 полях и обработаны аномальные значения. | 
| [Анализ убытков приложения ProcrastinatePRO+](application) | 1.Провести исследовательский анализ данных 2.Провести маркетинговый анализ данных. 3.Оценить окупаемость рекламы 4. Оформить рекомендации для отдела маркетинга| *pandas*, *numpy*, *datetime*, *matplotlib* |Мы разделили наши данные на 3 категории, благодаря такому делению, мы изучили не только привлечение по каналам,ну то есть, успешные приложения и не очень, но еще и расмотрели все данные для каждого устройства, и выявили специфику того региона, в котором приложение  котируется. То что мы расширили рамки исследования с помощью категорий позволило с разных сторон рассмотреть одни и те же процессы и сделать разные выводы. |
| [Исследование данных об инвестиции венчурных фондов в компании-стартапы](fond) | Проанализировать данные с помощью операторов и функций: инструментов SQL.| *SQL* |
| [Проверка гипотез по увеличению выручки в интернет-магазине ](online_store) |1.Приоритизировать гипотезы 2. Провести исследование 3.Выполнить A/B  тестирование по очищенным и неочищенным данным 4.Написать выводы| *pandas*, *datetime*, *numpy*, *matplotlib.pyplot*, *scipy.stats* |Мы сформурировали две гипотезы, одна об отличии конверсии между группами, другая - о различии средних чеков между группами. Мы смогли получить сведения о лидирующей группе в ходе тестирования и не потребовалось повторять эксперимент или проводить исследования по дополнительным данным.Перед тестированием мы провели исследование, благодаря которому и выбрали какой тест будем проводить. Из-за того что в данных много выбивающихся значений, мы выбрали тест Манна-Уитни.|
| [ Определение выгодного тарифа для телеком компании](rate) |1.Провести работу для изучения обработки данных телефонных компаний.2.Изучить данные по  количеству сделанных звонков для каждого пользователя 3.Посчитать количество минут которые были израсходованы каждым аобнентом. 4.Подсчитать количество отправленных сообщений 5.Посчитать выручку за минуты, сообщения и интернет. 6.Подсчитать количество потраченных мегабайт и гигабайт при использовании интернета  7.Сделать распределение звонков по видам тарифа 8.Делаем распределение средней продолжительности звонков по видам тарифа 9.Сделать распределение количества сообщенийпо видам тарифа 10.Сделать сравнение потраченных мегабайт для Smart и Ultra. 11.Создать гипотезу о средней выручке пользователей двух тарифов.12.Создать гипотезу о том что пользователи в Москве приносят большую выручку.| *pandas*, *scipy*,*seaborn*, *matplotlib.pyplot*, *numpy*|По проведенным тестам по гипотезам делаем вывод что средняя выручка Ultra и Smart не равна, выручка Ultra превосходит выручку Smart, поэтому стратегия развития Ultra более предпочтительна, чем у Smart. Стоит отметить, например, что длительность разговоров у Ultra в разы превышала показатели Smart. И только в феврале их показатели были одинаково низкими.В проекте мы отразили и другие факторы иллюстрирующие лидерство тарифа Ultra, все они были визуализированы.|
| [Изучение закономерностей, определяющих успешность игр](success) |1.Изучить данные и найти минимальные аномалии , искажающие данные.2.Отсортировать игры по годам 3.Рассчитать количество игр по годам для каждой платформы.4.Установить год релиза платформы 5.Установить как часто возникали платформы 6.Установить медианное количество игр для каждой платформы всего и для популярных платформ 7.Проанализировать 4 последних года .8.Проанализировать последний год.9.Составить общий вывод. | *pandas*, *numpy*, *matplotlib*, *matplotlib.pyplot*, *seaborn*, *scipy*, *matplotlib.lines*, *matplotlib.ticker*|В проекте мы создали два фильтра для более качественного анализа данных, первый: мы срезали данные за последние 4 года, и для этого среза мы установили общие тенденции, одна из которых, например, это то что мы выяснили какой жанр лучше продавался количественно. Вторым фильтром через который мы попустили данные - это срез за последний год, здесь было представлено больше обобщений: мы выделили 5 самых популярных жанров и 5 самых популярных платформ для каждого региона по отдельности, и на основе анализа создали "игровой" портрет каждого среднего пользователя. Благодаря такому анализу мы смогли обобщить достижения игроиндустрии в целом и вывести интересное предположение для увеличения обхвата одной игрой большей аудитории людей.|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering) | Определить наилучшее местоположение для открытия заведения.Изучить особенности заведений и ключевые закономерности в данных.| *pandas*, *seaborn*, *matplotlib.pyplot*, *numpy*, *folium*, *plotly.express*, *plotly*, *folium.plugins*, *json* |Мы создали поле которое отвечало за название улиц, оно заняло важное место в анализе данных. Мы установили местоположения улиц, на которых располагаются одиночные заведения, определили количество заведений для каждой улицы и  исходя из этих данных вывели 15 улиц на которых чаще всего "сияют ресторанные звезды Мадрида, с птичьми клтеками и зелено-белой геометрической плиткой", а другими словами, больше всего заведений, и из этого установили каких категорий заведений на этих улицах больше всего. Мы  выяснили что средний чек рейтинга от 2 до 3 составляет от 325 до 946 рублей. Поэтому можно обдумать расценку в заведении, если "дом под красным фонарем" откроет кто-то. Но мы еще и обнаружили какие чеки чаще всего замечаются в каждой категории заведения, а это еще более лучший ориентир, чем те расценки, которых желательно избегать. Всегда стоит целится в лучшее, но не забывать о том, что может подстерегать впереди. |

