# Personal-Assistant

## Опис

Цей проект є веб-застосунком на базі Django, що реалізує функціональність для управління особистими даними, включаючи контакти, нотатки та користувачів. Застосунок дозволяє реєстрацію користувачів, управління профілями та інтеграцію з API для обміну даними. Основні функції включають:

- Реєстрація та аутентифікація користувачів.
- Завантаження та управління аватарами користувачів.
- Можливість скидання пароля.
- Інтеграція з API для отримання новин та курсу валют.

## Вимоги

Проект працює на Python 3.10 або вище та використовує наступні бібліотеки:

- **Django**: 5.1.1
- **psycopg2**: для роботи з PostgreSQL
- **django-cors-headers**: для обробки CORS запитів
- **django-crispy-forms**: для покращення вигляду форм
- **cloudinary**: для зберігання зображень
- **whitenoise**: для обслуговування статичних файлів
- Інші бібліотеки, зазначені в `requirements.txt`.

## Установка

### 1. Клонуйте репозиторій

Скопіюйте проект на свій локальний комп'ютер:
```bash
git clone https://github.com/A-Lastovets/Personal-Assistant.git

Перейдіть в кореневу папку

1 Створіть віртуальне середовище:

python -m venv venv
source venv/bin/activate  # Для Linux/Mac
venv\Scripts\activate     # Для Windows

2 Встановіть залежності:

pip install -r requirements.txt

3 Налаштуйте файл .env: Створіть файл .env у кореневій директорії проекту та додайте необхідні змінні середовища використовуючі файл зразок .env.sample

4 Виконайте міграції бази даних:

python manage.py migrate

5 Запустіть сервер:
python manage.py runserver

Використання

Після запуску сервера ви зможете відкрити веб-застосунок у браузері за адресою http://127.0.0.1:8000/. Ви зможете реєструватися, входити в систему, додавати контакти та нотатки, а також управляти своїм профілем.

Тестування

Для запуску тестів використовуйте команду:

python manage.py test

Ліцензія
Цей проект ліцензовано під MIT License.

Дякуємо за використання нашого веб-застосунку!