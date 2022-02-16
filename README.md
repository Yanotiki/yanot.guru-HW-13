[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%23F78728&size=30&center=true&vCenter=true&multiline=true&width=900&height=150&lines=%D0%94%D0%BE%D0%B1%D1%80%D0%BE+%D0%BF%D0%BE%D0%B6%D0%B0%D0%BB%D0%BE%D0%B2%D0%B0%D1%82%D1%8C;%D0%B2+%D0%BC%D0%BE%D0%B9+%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82+%D0%BF%D0%BE+%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8;%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F+%D1%81%D0%B0%D0%B9%D1%82%D0%B0+Tourmachine!)](https://git.io/typing-svg)

# Проект по автоматизации тестирования для [Tourmachine](https://www.tourmachine.net/) :paw_prints:

## :raccoon:Содержание:

:cookie: Технологии и инструменты

:cookie: Реализованные проверки

:cookie: Сборка в Jenkins

:cookie: Запуск из терминала

:cookie: Allure отчет

:cookie: Отчет в Telegram

:cookie: Видео примеры прохождения тестов


## :raccoon: Технологии и инструменты

<p align="center">
<a href="https://www.jetbrains.com/idea/"><img src="img/icons/Intelij_IDEA.png" width="50" height="50"  alt="IDEA"/></a>
<a href="https://www.java.com/"><img src="img/icons/Java.png" width="50" height="50"  alt="Java"/></a>
<a href="https://github.com/"><img src="img/icons/Github.png" width="50" height="50"  alt="Github"/></a>
<a href="https://junit.org/junit5/"><img src="img/icons/JUnit5.png" width="50" height="50"  alt="JUnit 5"/></a>
<a href="https://gradle.org/"><img src="img/icons/Gradle.png" width="50" height="50"  alt="Gradle"/></a>
<a href="https://selenide.org/"><img src="img/icons/Selenide.png" width="50" height="50"  alt="Selenide"/></a>
<a href="https://aerokube.com/selenoid/"><img src="img/icons/Selenoid.png" width="50" height="50"  alt="Selenoid"/></a>
<a href="https://github.com/allure-framework/allure2"><img src="img/icons/AllureTestOps.png" width="50" height="50"  alt="Allure"/></a>
<a href="https://github.com/allure-framework/allure2"><img src="img/icons/Allure_Report.png" width="50" height="50"  alt="Allure"/></a>
<a href="https://www.jenkins.io/"><img src="img/icons/Jenkins.png" width="50" height="50"  alt="Jenkins"/></a>
 <a href="https://telegram.org/"><img src="img/icons/Telegram.png" width="50" height="50"  alt="Telegram"/></a>
</p>


## :raccoon: Реализованные проверки

:cookie: Проверка заголовка главной страницы

:cookie: Проверка состава путешественников по-умолчанию

:cookie: Проверка кнопки 'Витрина впечатлений'

:cookie: Проверка плейсхолдера 'Куда хотите поехать?'

:cookie: Проверка ошибок в консоле

## <img src="img/icons/Jenkins.png" width="25" height="25"  alt="Jenkins"/></a> Jenkins <a target="_blank" href="https://jenkins.autotests.cloud/job/AUTO-645/"> job </a>
<p align="center">
<a href="https://jenkins.autotests.cloud/job/AUTO-645/"><img src="img/AUTO-645 [Jenkins].jpg" alt="Jenkins"/></a>
</p>

## :raccoon: Параметры сборки в Jenkins:

:cookie: browser (браузер, по умолчанию chrome)

:cookie: version (версия браузера, по умолчанию 91.0)

:cookie: size (размер окна браузера, по умолчанию 1920x1080)

:cookie: remoteUrl (логин, пароль и адрес удаленного сервера selenoid)


## :raccoon: Запуск тестов из терминала

:cookie: Локальный запуск:
```bash
gradle clean test
```

:cookie: Удаленный запуск:
```bash
clean
test
-Dbrowser=${BROWSER}
-Dversion=${VERSION}
-Dsize=${BROWSER_SIZE}
-Durl=${REMOTE_URL}
```

## <img src="img/icons/Allure_Report.png" width="25" height="25"  alt="Allure"/></a> Отчет в <a target="_blank" href="https://jenkins.autotests.cloud/job/AUTO-645/8/allure/">Allure report</a>
### :cookie: Основное окно

<p align="center">
<img title="Allure Overview Dashboard" src="img/Allure Report1.jpg">
</p>

### :cookie: Тесты

<p align="center">
<img title="Allure Tests" src="img/Allure Report2.jpg">
</p>

## <img src="img/icons/Telegram.png" width="25" height="25"  alt="Allure"/></a> Уведомление в Telegram при помощи бота

<p align="center">
<img title="Allure Overview Dashboard" src="img/Telegram.jpg" >
</p>


## <img src="img/icons/Selenoid.png" width="25" height="25"  alt="Allure"/></a> Видео прохождения теста

<p align="center">
<img title="Selenoid Video" src="img/f4042fe798a8a83b.gif" width="250" height="153"  alt="video"> 
</p>
