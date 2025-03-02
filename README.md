### ПРОЕКТ

Основной датасет был взят с KAGGLE (https://www.kaggle.com/datasets/eren2222/nasdaq-nyse-nyse-a-otc-daily-stock-1962-2024?select=NASDAQ+1962-2024.csv)
(Соответствующий файл лежит на яндекс диске (https://disk.yandex.ru/d/IFbVS1ezRkNzSg) NASDAQ 1962-2024 (1).csv).
В нем информация об исторической динамике цен большого числа акций с насдака. 

Допом была взята информация с (https://ru.investing.com/indices/us-spx-500) (https://ru.investing.com/economic-calendar/manufacturing-pmi-829) (https://ru.investing.com/indices/usdollar) о динамике индекса S&P-500, PMI, DXY.
В приложенном файле project.ipynb лежит код, который соеденяет основной датасет с динамикой S&P-500 и приводят информацию в более читаемый вид, размещая тикеры по столбцам, а даты по строкам, а так же сужая временной период до с 2014 до 2024.

В результат вышел файл data_price_sp500.csv (https://disk.yandex.ru/d/8-NLdSZmgI09Ag).

В project_final1.ipynb лежит тетрадка со всеми основными работами над данными, подгрузкой дополнительных таблиц, их соеденением и визуализацией.
