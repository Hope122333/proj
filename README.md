Описание проектов
Данные проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных".


| Название проекта | Задачи | Используемые библиотеки | Презентация выводов по задачам |
| :--------------------- | :---------------------- | :---------------------- |:---------------------- |
| [Музыка больших городов](mus-proj) |1. Отсортировать поле с названиями жанров в лексикографическом порядке.2.Привести разные названия с одним значением к одному общему названию.3.Почистить дубликаты.4.Оценить активность пользователей в каждом городе.5.Оценить количество прослушиваний по дням недели для каждого города. 6. Создать функцию которая просчитает количество прослушиваний в разное время суток. 7. Подсчитать количество прослушиваний на каждый жанр| *pandas* |В Москве прослушиваний больше.Из активности  по дням недели представленным в датасете в целом больше всего прослушиваний в среду,а в частичном-в понедельник в Москве 15 740 прослушиваний. Количество прослушиваний разных жанров не меняется от времени суток, только в общем , либо увеличивается, либо уменьшается. Чаще всего и в Москве и в Санкт-Петербурге слушают на первом месте поп-музыку,а на втором месте dance.Мы пришли к выводу, что предпочтения людей одних из самых крупных городов России не сильно различаются,Россия большая, а душа у России - одна.|
| [Исследование надёжности заёмщиков — анализ банковских данных](arrears) | 1.Изучить инфомацию 2.Обработать пропуски и отрицательные значения 4.Получить медианные данные о количестве дней работы(или безработицы) для каждой категории людей. 5.Изучить количество детей в датасете 6.Разделить людей на типы по уровню зарплаты. 7.Определить цели людей для взятия кредита. 8.Обработать похожие цели для более простого чтения датасета. 9.Определить зависимость между наличием детей, уровнем дохода,влиянием разных целей и возвратом кредита в срок.| *pandas* |Люди, которые берут кредит на операции с автомобилем или на дополнительное образование чаще выплачивают кредит, чем люди, которые берут кредит на покупку жилья или проведение свадьбы.Лучше всего обстоят дела у людей, у которых либо нет детей, либо трое детей.Хуже всего ситуация с 2, либо с 4 детьми. Зависимость между суммой кредита и его выплатой 8 процентов у 4 категорий, и 7 процентов у "очень богатых".|
| [Продажа квартир в Санкт-Петербурге - анализ рынка недвижимости](apartments) | 1.Изучить информацию о пропусках. 2. Заменить пропущенные значения, где это возможно.3.Изучить типы данных представленные нам в таблице.4.Найти и устранить выбивающиеся значения.5.Посчитать и добавить в таблицу новые данные.6. Провести исследовательский анализ данных.7.Изучить, как быстро или как долго продавались квартиры.8.Изучить существование корреляционных зависимостей, влияющих на продажи.| *pandas*, *math*, *matplotlib.pyplot*, *numpy* |Так как мы потеряли только 3,5 процента информации от исходных данных,мы построили гистограммы для всех полей, которые помогли нам добиться любой полезной информации для понимания успешности продажи квартир.Например, мы взяли поле с количеством этажей, и выявили самый популярный для продажи этаж, это был второй этаж.  Положение 2 этажа наводнило более три тысячи квартиры. Львиная часть данных смогла нами плавно быть переведена в нужный формат.Были заменены пропуски в 11 полях и обработаны аномальные значения. | 
| [Анализ убытков приложения ProcrastinatePRO+](application) | 1.Провести исследовательский анализ данных 2.Провести маркетинговый анализ данных. 3.Оценить окупаемость рекламы 4. Оформить рекомендации для отдела маркетинга| *pandas*, *numpy*, *datetime*, *matplotlib* |Мы разделили наши данные на 3 категории, благодаря такому делению, мы изучили не только привлечение по каналам,ну то есть, успешные приложения и не очень, но еще и рассмотрели все данные для каждого устройства, и выявили специфику того региона, в котором приложение  котируется. То что мы расширили рамки исследования с помощью категорий позволило с разных сторон рассмотреть одни и те же процессы и сделать разные выводы. |
| [Исследование данных об инвестиции венчурных фондов в компании-стартапы](fond) | Проанализировать данные с помощью операторов и функций: инструментов SQL.| *SQL* |Были изучены основные оконные функции,я применила эти знания на практике, были также рассмотрены агрегирующие функции и применены на практике.
| [Проверка гипотез по увеличению выручки в интернет-магазине ](online_store) |1.Приоритизировать гипотезы 2. Провести исследование 3.Выполнить A/B  тестирование по очищенным и неочищенным данным 4.Написать выводы| *pandas*, *datetime*, *numpy*, *matplotlib.pyplot*, *scipy.stats* |Мы сформурировали две гипотезы, одна об отличии конверсии между группами, другая - о различии средних чеков между группами. Мы смогли получить сведения о лидирующей группе в ходе тестирования и не потребовалось повторять эксперимент или проводить исследования по дополнительным данным.Перед тестированием мы провели исследование, благодаря которому и выбрали какой тест будем проводить. Из-за того что в данных много выбивающихся значений, мы выбрали тест Манна-Уитни.|
| [ Определение выгодного тарифа для телеком компании](rate) |1.Провести работу для изучения обработки данных телефонных компаний.2.Изучить данные по  количеству сделанных звонков для каждого пользователя 3.Посчитать количество минут которые были израсходованы каждым аобнентом. 4.Подсчитать количество отправленных сообщений 5.Посчитать выручку за минуты, сообщения и интернет. 6.Подсчитать количество потраченных мегабайт и гигабайт при использовании интернета  7.Сделать распределение звонков по видам тарифа 8.Делаем распределение средней продолжительности звонков по видам тарифа 9.Сделать распределение количества сообщенийпо видам тарифа 10.Сделать сравнение потраченных мегабайт для Smart и Ultra. 11.Создать гипотезу о средней выручке пользователей двух тарифов.12.Создать гипотезу о том что пользователи в Москве приносят большую выручку.| *pandas*, *scipy*,*seaborn*, *matplotlib.pyplot*, *numpy*|По проведенным тестам по гипотезам делаем вывод что средняя выручка Ultra и Smart не равна, выручка Ultra превосходит выручку Smart, поэтому стратегия развития Ultra более предпочтительна, чем у Smart. Стоит отметить, например, что длительность разговоров у Ultra в разы превышала показатели Smart. И только в феврале их показатели были одинаково низкими.В проекте мы отразили и другие факторы иллюстрирующие лидерство тарифа Ultra, все они были визуализированы.|
| [Изучение закономерностей, определяющих успешность игр](success) |1.Изучить данные и найти минимальные аномалии , искажающие данные.2.Отсортировать игры по годам 3.Рассчитать количество игр по годам для каждой платформы.4.Установить год релиза платформы 5.Установить как часто возникали платформы 6.Установить медианное количество игр для каждой платформы всего и для популярных платформ 7.Проанализировать 4 последних года .8.Проанализировать последний год.9.Составить общий вывод. | *pandas*, *numpy*, *matplotlib*, *matplotlib.pyplot*, *seaborn*, *scipy*, *matplotlib.lines*, *matplotlib.ticker*|В проекте мы создали два фильтра для более качественного анализа данных, первый: мы срезали данные за последние 4 года, и для этого среза мы установили общие тенденции, одна из которых, например, это то что мы выяснили какой жанр лучше продавался количественно. Вторым фильтром через который мы попустили данные - это срез за последний год, здесь было представлено больше обобщений: мы выделили 5 самых популярных жанров и 5 самых популярных платформ для каждого региона по отдельности, и на основе анализа создали "игровой" портрет каждого среднего пользователя. Благодаря такому анализу мы смогли обобщить достижения игроиндустрии в целом и вывести интересное предположение для увеличения обхвата одной игрой большей аудитории людей.|
| [Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](catering) | 1.Создать поле 24/7 для работающих круглосуточно и ежедневно заведений.2.Создать поле с названием улицы.3.Определить количество заведений по категориям и округам.4.Исследовать среднее количество посадочных мест по категориям.5.Рассмотреть количественное соотношение сетевых и несетевых заведений.6.Изучить самые популярные сетевые заведения.7.Определить средний чек на который может расчитывать человек, открывающий заведение.8.Определить средний рейтинг заведений для каждого района.9.Отобразить все заведения с пощью кластеров используя библиотеку folium.10.Опредить какие категории определяют успех улицы.11.Найти улицы с одиночными завдениями.12.Изучить часы работы в разных категориях.13.Изучить средний счет рейтингов ниже 2.14.Изучить рейтинги ниже 2 для категорий заведений15.Изучить какой усредненный чек приходится на каждый рейтинг.16.Детализировать исследование.| *pandas*, *seaborn*, *matplotlib.pyplot*, *numpy*, *folium*, *plotly.express*, *plotly*, *folium.plugins*, *json* |Мы создали поле, которое отвечало за название улиц, оно заняло важное место в анализе данных. Мы установили местоположения улиц, на которых располагаются одиночные заведения, определили количество заведений для каждой улицы и  исходя из этих данных вывели 15 улиц на которых чаще всего "сияют ресторанные звезды Мадрида, с птичьими клетками и зелено-белой геометрической плиткой", а другими словами, больше всего заведений, и из этого установили каких категорий заведений на этих улицах больше всего. Мы  выяснили, что средний чек рейтинга от 2 до 3, составляет от 325 до 946 рублей. Поэтому можно обдумать расценку в заведении, если "дом под красным фонарем" откроет кто-то. Но мы еще и обнаружили какие чеки чаще всего замечаются в каждой категории заведения, а это еще более лучший ориентир, чем те расценки, которых желательно избегать. Всегда стоит целится в лучшее, но не забывать о том, что может подстерегать впереди.К проекту была также приложена презентация, с которой вы можете ознакомиться в папке проекта. |
| [Анализ пользовательского поведения в мобильном приложении](device) | 1. Импортировать библиотеки и загрузить данные, изучить 'info' данные;2. Поработать над форматом времени; 3.Проверить наличие пропусков в данных; 4.Оценить наличие дубликатов в данных. 5.Визуализировать оценку; 6.Оценить количество событий в логе; 7.Оценить количество уникальных пользователей в логе; 8.Ответить на вопрос: сколько в среднем событий приходится на одного пользователя; 9.Определить минимальную и максимальную дату времени эксперимента для оценки данных; 10.Обнаружить и очистить аномальные зоны; 11. Оценить долю пользователей для каждого типа события; 12.Определить границы эксперимента; 13. Создать сводную таблицу для воронки, обозначить ее составляющие и иерархию, визуализировать по убыванию;14.Определить долю пользователей , которая доходит с главной страницы до оплаты;15. Для каждой группы определить долю потерянных пользователей после посещения главной страницы;16. Для каждой группы определить сколько процентов пользователей остается при прохождении страниц;17. Добавить метод для проверки разницы статистических критериев;18. Обработать информацию для теста ;19. Сформулировать гипотезы и провести тесты;20. Установить самое популярное событие; 21.Посчитать количество совершивших переход на главную страницу; 22.Посчитать долю совершивших переход на главную страницу от всех пользователей совершивших переход на главную страницу;23.Установить количество пользователей в каждой группе;24.Составить общий вывод; | *pandas*, *datetime*, *numpy*, *matplotlib.pyplot*, *scipy.stats*, *seaborn*, *math*|Нами было проверено 20 гипотез, проведено 20-z-test, информацию для которых мы обработали методом - фильтром.Мы каскадно провели тест: по 5 гипотез за один проход, построили воронку, определив для нее иерархическую последовательность, визуализировали ее barplot , а далее мы построили процентную воронку, ее визуализацию вы можете увидеть в проекте. Написали выводы по проведенным тестам, проверенным гипотезам  и по анализу данных проекта . |
| [Изучение активности на Яндекс.Дзене](yan_dz) | 1.Создать интерактивный дашборд, который позволит проанализировать активность пользователей Яндекс.Дзена. 2.Сделать презентацию, в которой доступно описать как удобно взаимодействовать с дашбордом и как правильно оценивать информацию по нему | -//- |Мы создали систему, которая отражает самые важные запросы со стороны пользователей, такие как их интерес к темам и источникам. Благодаря этому можно отслеживать процентно, и то и другое, и делать выводы на предстояющую неделю. Мы сделали это особенным образом,использовав два разных способа отображения долей от общего количества, чтобы любому человеку было приятно взаимодействовать с нашим дашбордом. Мы добавили разные фильтры, например, такой полезный фильтр, как возраст. А также создали показатели по времени и по пересечению тем и источников, что позволит сделать более прозрачными взаимосвязи интересов пользователей.|
| [Игры — Формирование модели монетизации](osm) | 1.Изучить данные и выполнить предобработку.Убедится, что типы данных во всех колонках соответствуют сохранённым в них значениям.Обратить внимание на столбцы с датой и временем.2.Определить период исследования привлечения клиентов.3.Определить период исследования. Вычислить минимульную и максимальную дату посещения приложения.4.Посчитать количество денег полученных за каждый день эксперимента полученных с каждого источника.5. Выяснить, из каких источников пользователи приходят в приложение .6.Определить какой тип построек чаще всего встречается во взаимодействии пользователя с игрой.7.Определить самых активных пользователей.8. Сравнить количество  пользователей с количеством построек с  количеством событий игры. Выяснить где больше всего пользователей  взаимодействовало с игрой.9.Определить общюю стоимость со всех кликов. 10.Визуализировать стоимости по дням источников привлечения пользователей.11. Построить график распределения различных типов объектов по количеству построек. Чтобы определить какая постройка является более предпочтительной.12.Построить воронку , где пользователь проходит от постройки первого объекта, до конца проекта. Выяснить сколько пользователей доходит до имеющегося на данный момент конца игры.13.Построить воронку измнения стоимости кликов по дням.14. Проверить статистические гипотезы | *pandas*, *math*, *matplotlib.pyplot*, *numpy*, *seaborn*, *plotly*, *plotly.express*, *scipy.stats*| Одним из основных предложений было то, что  если ввести монетизацию на постройки - это может стать лучшим решением для введения монетизации в рамках этой игры. Но мы пришли к выводу, что на самом деле монетизация не так важна для какого-то определенного события. Людям интересна сама игра, и поэтому стоит задуматься о ее развитии в данный момент. Потому что монетизацию можно привязать к чему угодно, главное чтобы люди видели, что игра разивается , что разработчики стараются и прислушиваются к их желаниям по поводу нее. И тогда монетизация станет одним из поводов не обращать на нее особого внимания. Потому что на данный момент мы смогли установить, что людям интересна эта игра и именно об этом история нашего небольшого исследования.Также к проекту прилагаются два дашборда. |
| [Исследование маркетинговых событий интернет-магазина накануне нового года](chris) | 1.Считать и обработать данные.2.Проверить данные на наличие или отсутствие дубликатов. 3.Проверить, проводились ли какие-то маркетинговые акции в период проведения тестов на любых из его этапов отбора или на любых из его этапов самого теста.4.Проверить, сколько пользователей относится к каждой из групп в системе необходимого теста по ТЗ. 5.Определить количество дубликатов среди пользователей для проверки необходимого теста. 6.Выбрать всех пользователей с обозначением европейской принадлежности в данных. 7.Перенести рамки текущего задания в существующий период теста. 8.Посчитать первоначальный процент от общего числа европейцов тех европецев, которые учавствуют в эксперименте. 9.Обработать данные , чтобы получить менее искажающую результат статистику. 10.Проверить входит ли количество испытуемых по данным в размер необходимой выборки по ТЗ. 11.Посчитать долю европейцев, учавствующих в опыте от общего количества европейцев. 12.Проверить, входят ли в события покупки, которые не вошли в периоды отбора и проведения теста. 13.Определить количество событий на одного пользователя в каждой выборке. 14.Определить как число событий в выборках распределено по дням. 15.Определить как меняется конверсия в воронке в выборках на разных этапах. 16. Сгруппировать данные для проведения A/B теста. 17.Добавить метод для проведения A/B теста. 18.Отобрать данные и провести на них тест. 19.Написать выводы к тесту.20.Написать выводы к исследованию. |*pandas*, *plotly*, *numpy*, *scipy.stats*, *seaborn*, *math*, *statsmodels.stats.proportion*| Перед новым годом компания решила отобрать группу новых пользователей, и на основе их активности и активности контрольной группы проверить насколько новая система рекомендаций выполняет свою роль. Было проведено исследование существующих групп и закономерности их изменений активности. На основе исследования и имеющихся данных было проведено множественное A/B -тестирование и проверена основная гипотеза исследования, а именно, эффективность новой рекомендательной системы и возможность оценить рекомендательную систему в рамках исследования.|
| [Изучение крупного сервиса для чтения книг](book_s) | 1.Изучить общую информацию данных. 2.Посчитать, сколько книг вышло после 1 января 2000 года. 3.Для каждой книги посчитать количество обзоров и среднюю оценку. 4.Определить издательство, которое выпустило наибольшее число книг толще 50 страниц. 5. Определить автора с самой высокой средней оценкой книг — учитывать только книги с 50 и более оценками. 6. Посчитайте среднее количество обзоров от пользователей, которые поставили больше 50 оценок. | *pandas* , *sqlalchemy*  |Нами были рассмотрены предпочтения пользователей и распределение оценок и обзоров среди них. Мы обнаружили интересные моменты, которые можно было бы развить и обосновать для будущих исследований. |
| [Исследование аварийной ситуации в Барнауле](bar) | 1.Изучить данные.2.Выбрать изучаемый город.3.Обработать пропуски.4.Отобразить границы районов.5.Отобразить все аварии на карте.6.Определить количество аварий для каждой улицы.7.Определить количество аварий на каждый район.8.Определить как аварии распределялись по существующим временам суток.9.Обработать данные json.10.Выяснить какого цвета машины чаще сбивают людей в Барнауле.11.Узнать какие модели машин самые популярные на дорогах Барнаула.12.Узнать какого года производства эти машины.13.Определить какой бренд самый популярный среди автомобилей.14.Определить какая категория машин попадается чаще в анализе.15.Посмотреть как аварии располагались по времени в датасете.16.Детализировать исследование.17.Написать вывод. | *geopandas*, *matplotlib.pyplot*,*folium*,*numpy*,*pandas*, *seaborn*,*requests*, *json*, *re*, *plotly*,*math* |Первоначальной целью исследования было - изучить данные с целью определить, в каких районах, какие аварии, какая ситуация в городе в целом, на что можно опираться в дальнейших исследованиях вопроса, на что опираться в улучшении ситуации связанной с ДТП, но в ходе исследования вопрос поменял свою форму, и главной задачей стало доказательство, что скорая помощь хорошо справляется с задачей спасения людей после последствий аварии. Чтобы увидеть, как мы к этому пришли, мы можете рассмотреть цепочку размышлений которую мы проводим по проекту. Выводы будут связаны с прогнозом на ситуацию ДТП в Барнауле и  доказательством того, что скорая паомощь справляется со своей ролью в этом непростом деле.|
| [Изучение крупной компании с целью развития ее маркетинговых возможностей](ga) | 1. Изучить данные. 2. Определить возможную проблему. 3. Проверить это предположение 4. Сделать выводы 5. Обнаружить способ повлиять на ситуацию | :---------------------- |Мы хотели ответить на вопрос, который был конкретно поставлен нам: как поднять количество пользователей у компании? Но когда мы стали исследовать данные, перед нами вырос новый вопрос: почему компания так заинтересована в привлечении новых пользователей, если большинство из них составляет неплатежный сегмент? Чтобы выяснить это, мы провели исследование, в ходе которого обнаружили, что компания сама не осознает как выстраивается ее бюджет и с чем связано его изменение. Немного пошевелив тему, мы смогли сделать конкретные выводы и адресовать их компании по этому вопросу|
