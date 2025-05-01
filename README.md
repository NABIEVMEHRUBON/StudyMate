# 🎓 StudyMateBot - Telegram-бот для студентов

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Aiogram](https://img.shields.io/badge/Aiogram-3.x-green.svg)
![SQLite](https://img.shields.io/badge/SQLite-3-lightgrey.svg)

Бот для помощи студентам и админам. Позволяет просматривать расписание, читать новости, задавать вопросы, а также управлять контентом и пользователями.

---

## 🌟 Возможности

### 👨‍🎓 Для студентов:
- 📅 Просмотр расписания своей группы
- 📰 Актуальные новости
- ❓ Задание вопросов админам
- 🔔 Уведомления об изменениях

### 👑 Для админов:
- 🛠 Управление группами и расписанием
- 📢 Публикация новостей (с фото и текстом)
- 📬 Ответы на вопросы студентов
- 🔄 Массовая рассылка
- 👤 Добавление админов по `@username`

---

## 🚀 Быстрый старт

### 1. Скачай проект:

```bash
git clone https://github.com/NABIEVMEHRUBON/StudyMate.git
cd StudyMateBot
```

### 2. Настрой окружение:

```bash
python -m venv venv
source venv/bin/activate      # Linux/macOS
venv\Scripts\activate         # Windows
```

### 3. Установи зависимости:

```bash
pip install -r aiogram
```

### 4. Пропиши:

```bash
TOKEN_BOT="ваш_токен_бота"
ADMINS="username"
```

### 5. Запусти бота:

```bash
python bot.py
```
