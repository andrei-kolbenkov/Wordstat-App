# Wordstat-App

- openpyxl
- pandas
- requests
- re


About the project:
1. The excel file is filled with words, phrases and sentences needed to determine the frequency of requests.
2. All data is divided into words
3. Words that do not need to be parsed, added to the specified file, are subtracted
4. The user selects up to what number of words can be in a phrase
5. Words are generated in all possible phrase variants
6. A request with each phrase is sent to the Yandex Wordstat website using the POST method to obtain the number of matches
7. Statistics on the number of matches for each phrase are saved in an excel file

О проекте:
1. Файл excel заполняется словами, фразами и предложениями, необходимыми для определения частоты запросов.
2. Все данные делятся на слова
3. Вычитаются слова, которые не нужно парсить, добавленные в указанный файл
4. Пользователем выбирается, до какого количества слов может быть в фразе
5. Происходит генерация слов во все возможные варианты фраз
6. Методом POST отправляется запрос с каждой фразой на сайт Яндекс Wordstat для получения количества совпадений
7. Статистика количества совпадений по каждой фразе сохраняются в файл excel

