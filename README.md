# [Итоговый проект Skillfactory 28.1 по автоматизации тестирования]()

====================================================================

> Требования [лежат тут](https://docs.google.com/document/d/1_CvDrfeia5rYTJ0owSHSnuO0-nAphKw8/edit?usp=share_link&ouid=118178127297918959624&rtpof=true&sd=true)

_________________________________________________________________________________________________________________

> Объект тестирования [перейти по этой ссылке](https://b2c.passport.rt.ru)

_________________________________________________________________________________________________________________

> Мои тест-кейсы, баг репорты [тут](https://docs.google.com/spreadsheets/d/1MHtfwyUK8QaueOOzvM9mGCb_LWugxvKz/edit?usp=share_link&ouid=118178127297918959624&rtpof=true&sd=true)

====================================================================

### [Ожидаемый результат]()

1. Перечислены инструменты, которые применялись для тестирования.
* Почему именно этот инструмент и эту технику.
* Что им проверялось.
* Что именно в нем сделано.
2. К выполненному заданию прикреплены:
* Набор тест-кейсов.
* Набор автотестов на GitHub. Обратите внимание, что в репозитории должен находиться файл README.md, где будет описано, что именно проверяют данные тестовые сценарии и какие команды необходимо выполнить для запуска тестов. Описанные команды должны работать на любом компьютере с установленными Python3 и PyTest.
* Описание оформленных дефектов.

====================================================================

## Заказчик передал вам следующее задание:

* Протестировать требования.
* Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
* Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
* Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)

====================================================================

Для написания тест-кейсов использовались следующие техники тест-дизайна: 
1) Классы эквивалентности
2) Граничных значений

> [base_data.py]() - базовые классы, процедуры, функции и локаторы для автотестов

> [settings.py]() - регистрационные данные для позитивных тестов авторизации

> [test_SF_RT_passport]() - набор автотестов. нумерация соответствует номеру тест-кейса в документе

Драйвер лежит в одной папке с тест-скриптом для запуска автотестов

> python -m pytest -v --driver Chrome --driver-path chromedriver.exe test_SF_RT_passport.py



