# Contacts Manager (Bug Fix)
# Contacts Manager

Простое консольное приложение для управления контактами на Python.

## Установка
1. Клонируйте репозиторий.
2. Создайте виртуальное окружение: `python -m venv .venv`
3. Активируйте его: `source .venv/bin/activate` (Mac/Linux)
4. Установите зависимости: `pip install -r requirements.txt`

## Использование
- Добавить контакт: `python main.py add "Иван" "+79991234567" "ivan@mail.ru"`
- Показать все контакты: `python main.py list`
- Найти контакт: `python main.py find "Иван"`
- Удалить контакт: `python main.py delete "Иван"`
