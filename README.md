# Module-28
Final homework
В рамках выполнения дипломного проекта нужно было протестировать новый интерфейс авторизации в личном кабинете от заказчика Ростелеком Информационные Технологии.

Заказчик передал следующее задание:

Протестировать требования.
Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна.
Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub.
Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов. (если дефекты не будут обнаружены, то составить описание трех дефектов)
Ссылка на анализ требований, тест-кейсы и баг-репорты https://docs.google.com/spreadsheets/d/1DR3tbMsG7SyNEJOW3YMmSbJ4LnfLUa0U/edit?usp=sharing&ouid=109108946357462089213&rtpof=true&sd=true

Для составления и написания тест-кейсов использовались такие техники тест-дизайна как: классы эквивалентности, анализ граничных значений, предугадывание ошибок.

Тестирование было осуществеленно как ручное, так и автоматизированное.

base_data.py - базовые классы, процедуры, функции и локаторы для автотестов

settings.py - регистрационные данные для позитивных тестов авторизации

test_SF_RT_passport - собственно набор автотестов, нумерация соответствует номеру тест-кейса

запуск автотестов (драйвер в одной папке с тест-скриптом)

python -m pytest -v --driver Chrome --driver-path chromedriver.exe test_SF_RT_passport.py
