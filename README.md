# Family Legacy Learning

Одностраничник закрытой образовательной программы **Family Legacy Learning** — программы Tumar Family Office под руководством Галии Нурбековой.

## Стек

Чистый HTML + CSS + минимум JS. Без сборки, без зависимостей. Готов для GitHub Pages.

## Структура

- `index.html` — разметка одностраничника (RU)
- `styles.css` — стили (quiet luxury: navy + gold, serif заголовки, sans-serif тело)
- Шрифты — Cormorant Garamond (заголовки) и Inter (тело) с Google Fonts

## Локальный запуск

Открыть `index.html` в браузере. Или через простой сервер:

```bash
python3 -m http.server 8000
# затем http://localhost:8000
```

## Деплой

Опубликован через GitHub Pages из ветки `main`, корень репозитория.

## Следующие шаги (по PRD)

- Полная локализация: KZ, AR (RTL), EN
- Подключение CRM (Supabase) к форме заявки
- Email/WhatsApp уведомления через Resend + Twilio
- UTM-атрибуция, скоринг лидов
- DocuSign для NDA и контрактов
- Личный кабинет участника

См. полный PRD v2.0.
