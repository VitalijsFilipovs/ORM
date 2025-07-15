# Django ORM – Менеджер задач

Домашнее задание по курсу **Python Advanced**  
Тема: Работа с ORM (Create, Read, Update, Delete)

---

## 📌 Описание

Проект демонстрирует работу с моделями `Task` и `SubTask` в Django.  
Реализованы основные операции:
- Создание задач и подзадач
- Чтение (фильтрация по статусу, просроченные задачи)
- Обновление записей
- Удаление задач вместе с подзадачами

---

## 🧩 Модели

- **Task**: заголовок, описание, статус, дедлайн
- **SubTask**: привязка к задаче, заголовок, описание, статус, дедлайн

---

## 🧪 ORM-запросы

Все CRUD-запросы выполнены в Django shell:
- `Task.objects.create(...)`
- `Task.objects.filter(status="New")`
- `task.status = "In progress"`
- `task.delete()`

---

## ⚙️ Стек

- Python 3.13
- Django 5.2
- SQLite (по умолчанию)

---

## 👤 Автор

Vitalijs Filipovs  
[GitHub профайл](https://github.com/VitalijsFilipovs)
