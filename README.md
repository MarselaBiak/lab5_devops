# Лабораторна робота №5

## Тема

Створення простого API

---

## Мета роботи

Навчитися створювати простий HTTP API для своєї моделі.  
Забезпечити доступ до обчислювальної функції через веб-запит.  
Підготувати основу для CI/CD та хмарного запуску.

---

## Модель

Оптимізація енергоспоживання готелю з використанням генетичних алгоритмів

---

## Опис роботи

У лабораторній роботі реалізовано HTTP API для моделі оптимізації енергоспоживання готелю.  
Для створення API використано Flask.

Модель використовує генетичний алгоритм для пошуку оптимального режиму роботи пристроїв готелю з урахуванням:
- споживання електроенергії;
- критичності обладнання;
- впливу на комфорт гостей.

Створено endpoint `/calculate`, який приймає параметр `max_power` через URL-запит та повертає результат у форматі JSON.

---

## Структура проєкту

```text
hotel-energy-ga/
│
├── app.py
├── requirements.txt
└── Dockerfile
```

---

У терміналі виконано команду:

<img width="364" height="137" alt="image" src="https://github.com/user-attachments/assets/e0459df5-ffbb-4378-b2d4-607d61bc1ea7" />

---

<img width="940" height="288" alt="image" src="https://github.com/user-attachments/assets/68a29664-d6ec-4821-8357-ba35cc8df24d" />

---

<img width="940" height="296" alt="image" src="https://github.com/user-attachments/assets/02c9d0d8-04af-4e86-a039-5b4c16760e41" />

---

<img width="940" height="664" alt="image" src="https://github.com/user-attachments/assets/84b1a2e8-d7ec-44b3-b769-0b03d875b8f4" />

---

Для запуску API виконано команду:

<img width="940" height="233" alt="image" src="https://github.com/user-attachments/assets/13fa73ad-7808-4bb4-b8e1-9da31519e879" />

---

Після запуску Flask сервер працює за адресою:

<img width="858" height="1174" alt="image" src="https://github.com/user-attachments/assets/531256ff-332f-4ae2-9ea7-ce479f4b8c72" />













