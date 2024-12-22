Diploma
Описание
Авиасейлс — это сервис, который помогает искать и покупать билеты. Вот как это работает:

Вы заходите в приложение или на сайт, вбиваете направление и даты, а мы ищем подходящие билеты у разных авиакомпаний и агентств.

Вы находите свой идеальный билет, а мы перенаправляем вас на сайт продавца — там вы заполняете данные пассажиров и покупаете билет. Некоторые билеты можно купить прямо в знакомом интерфейсе Авиасейлс, но продают их всё равно агентства и авиакомпании (они же помогают оформить обмен или возврат). А есть билеты, которые продаёт именно Авиасейлс, — вы узнаете их по нашему логотипу.

Авиасейлс не хранит билеты, не берет комиссию за услуги и отображает цены, которые присылают авиакомпании и агентства. Найти купленный билет, запросить обмен/ возврат можно в личном кабинете на сайте продавца

Виды тестирования
UI/API тестирование

Структура проекта
Тест файл test_api содержит тесты для тестирования бекенд запросов тестов к API

Тест файл test_ui содержит тесты для тестирвоания фронд запросов тестов к UI, используется подход PageObject и функции вызываются из класса main_page

Запуск тестов:
pytest test_api.py команда для запуска только АПИ тестов

pytest test_ui.py команда для запуска только UI тестов

pytest - команда для запуска всех тестов

Ссылка на итоговый проект ручного тестирования: https://finalhandtest.yonote.ru/doc/diplom-GA3gMFLGR4/edit
Команды для генерации отчёта Allure:
pytest --alluredir=reports

allure serve reports