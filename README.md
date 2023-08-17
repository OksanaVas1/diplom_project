
PageObject подход в реализации UI тестов с использованием Selenium + Pytest.

Для запуска тестов:

Установить правила pip3 install -r requirements
Загрузить актуальный драйвер хром отсюда https://chromedriver.chromium.org/downloads
Положить загруженный драйвер в корень проекта (с заменой, вместо имеющегося)
Использовать команду python -m pytest -v tests/tests_rostelekom.py
При запуске всех тестов может сработать защита ростелекома, что приведет к блокировке IP