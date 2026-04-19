# FunPay Tools — Firefox Edition

> Форк [FunPay Tools](https://github.com/XaviersDev/FunPay-Tools) by [SanoSenpay](https://github.com/SanoSenpay), портированный для Firefox-based браузеров.

Полнофункциональный порт расширения для продавцов на FunPay. Работает в **Zen Browser**, Firefox, Waterfox, LibreWolf и других браузерах на движке Gecko.

---

## Установка

### Скачать Release:
> https://github.com/SanoSenpay/FunPay-Tools-FireFox/releases/tag/experimental

**Как установить?** (гайд на Zen browser - на других браузерах должно работать так же)
> 1. зайдите в **about:config**
> 2. поставьте **xpinstall.signatures.required** на **false**
> 3. зайдите в **Управление дополнениями** или **about:addons**
> 4. нажмите на шестерёнку и нажмите "Установить дополнение из файла..."
> 5. выберите файл и всё готово!
### Скачать расширение на FireFox Addons:
> статус: Ожидается проверка...
---

## Что изменено относительно оригинала

| | Оригинал (Chrome) | Этот форк (Firefox) |
|---|---|---|
| Манифест | V3 | V2 |
| Background | Service Worker + Offscreen API | Background Page (без offscreen) |
| API | `chrome.*` | `browser.*` + polyfill |
| Парсинг HTML | Offscreen document | Напрямую в background (DOMParser) |

---

## Функции

- 🤖 **AI-ассистент** — улучшение текста в чате, генерация лотов, ответы на отзывы, переводчик
- 🎨 **Кастомизация** — темы, фоны (GIF), шрифты, эффекты курсора, Live Styler
- 📦 **Управление лотами** — экспорт/импорт, массовое редактирование, клонирование, авто-поднятие
- 🤖 **Автоответчик** — приветствия, ответы на ключевые слова, авто-ответ на отзывы, авто-выдача
- 📊 **Аналитика** — статистика продаж, аналитика рынка, копилки
- 🔔 **Discord** — уведомления о новых сообщениях через Webhook
- 👥 **Аккаунты** — быстрое переключение между аккаунтами FunPay

---

## Лицензия

MIT — на основе оригинального проекта [FunPay Tools](https://github.com/XaviersDev/FunPay-Tools) © AlliSighs.
