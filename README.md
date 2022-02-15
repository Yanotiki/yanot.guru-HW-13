Проект по автоматизации тестирования для Tourmachine
Веб сайт Tourmachine

:drop_of_blood: Содержание:
Технологии и инструменты
Реализованные проверки
Сборка в Jenkins
Запуск из терминала
Allure отчет
Отчет в Telegram
Видео примеры прохождения тестов
:bird: Технологии и инструменты
IDEA Java Github JUnit 5 Gradle Selenide Selenoid Allure Jenkins

:boom: Реализованные проверки
✓ Поиск вакансии QA Automation
✓ Открытие статьи о Biocad и Exchange (параметризованные тесты)
✓ Поиск информации о компании Biocad в скачанном PDF файле
✓ Смена языка с русского на английский
✓ Заполнение Запроса в отдел продаж
Jenkins Jenkins job
Jenkins

:maple_leaf: Параметры сборки в Jenkins:
browser (браузер, по умолчанию chrome)
version (версия браузера, по умолчанию 91.0)
size (размер окна браузера, по умолчанию 1920x1080)
remoteUrl (логин, пароль и адрес удаленного сервера selenoid)
:japanese_ogre: Запуск тестов из терминала
Локальный запуск:

gradle clean test
Удаленный запуск:

clean
test
-Dbrowser=${BROWSER}
-Dversion=${VERSION}
-Dsize=${BROWSER_SIZE}
-Durl=${REMOTE_URL}
Allure Отчет в Allure report
:lady_beetle: Основное окно
Allure Overview Dashboard

:cherries: Тесты
Allure Tests

:cut_of_meat: Графики
Allure Graphics

Allure Уведомление в Telegram при помощи бота
Allure Overview Dashboard

Allure Видео прохождения теста
video
