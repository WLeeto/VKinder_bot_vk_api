# VKinder
Бот для чата сообщества ВКонтакте.
Автоматический поиск похожих контактов.

Для работы в первую строку .ini файлов вставить:
- токен вашей учётки
- токен учётки сообщества
- id сообщества

Создать пустую базу данных vk_bot:
- создать базу данных PostgreSQL (например, с помощью pgAdmin4)
- ввести пароль от базы данных в ORM/class_ORM.py (self.DSN = "postgresql://postgres:ваш пароль@localhost:5432/vk_bot")

