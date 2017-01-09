# Quadratic Equations Solver
Скрипт содержит функцию для поиска корней квадратного уравнения. Для проверки правильности работы функции написан модуль tests.py. Чтобы файл tests.py запускался автоматически, необходимо поместить файл pre-commit в папку .git/hook. Файлу pre-commit надо добавить бит исполнения. После этого при попытке коммита файл с тестами будет запускаться автоматически и, если в тестах будет найдена ошибка, коммит прервётся.

## Пример использования pre-commit hook
    git add quadratic_equation.py
    git commit
При успешном выполнении тестов появится окно с предложением ввести комментарий к комиту, в противном случае коммит прервётся.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
