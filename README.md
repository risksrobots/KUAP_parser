# Метод извлечения таблиц из отчетности ЦБ

| Название файла/директории | Содержание файла |
|----:|:----------|
| Baza_s_Kuapa.ipynb | Скрипт для скачивания отчетов с КУАПа и соединения этих файлов с файлами в папке BANKS pdf в файл xlsx|
| chromedriver.exe | Приложение, позволяющее запускать Chrome браузер и осуществлять переход по страницам |
| BANKS | Директория, содержащая таблицы с данными за каждый месяц/квартал из отчетов КУАПа|

## Описание 

Этот код позволяет пользователю совершить выгрузку данных с сайта https://kuap.ru/ за определенный период и добавляет эти данные в указанный файл. Парсер принимает на вход файл(.xls) и передает его столбец в выбранный файл(.xlsx). Запуск осуществляется в Jupyter Notebook или Google Collab. Обязательно наличие драйвера браузера и папки с отчетами за предыдущие периоды.

## Документация

* [Документация по работе с Python](https://www.python.org/)
* [Документация по работе с библиотекой Selenium](https://www.selenium.dev/documentation/webdriver/)
* [Документация по работе с библиотекой Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)
* [Документация по работе с библиотекой Numpy](https://numpy.org/doc/)

## Зависимости

Рабочие версии библиотек прописаны в файле "requirements.txt"

Для настройки необходимых пакетов python для скрипта введите в командной строке:

> pip install -r "requirements.txt"
 

## :shipit: Контакты
**Telegram** @niii_chel_angelo
**ВКонтакте**[niii_popova](https://vk.com/niii_popova)
**Email** PopovaNinaM@yandex.ru
