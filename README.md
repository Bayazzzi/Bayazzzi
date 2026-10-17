# Привет! 👋 Я Арман

Full-stack разработчик из Казахстана. Создаю аккуратные и быстрые веб-продукты на **Next.js / TypeScript** и автоматизирую задачи на **Python**. Особенно люблю задачи на стыке финансов, данных и удобных интерфейсов.

## 🚀 Проекты

### 🌐 Портфолио — этот сайт вживую
Личный сайт-портфолио на Next.js: живые превью всех проектов прямо в карточках,
анимированный фон, свечение под курсором, тёмная/светлая тема. Собрано без
внешних UI-библиотек — только чистый CSS.

- 🔗 Демо: [portfolio-rho-ten-c7t3equ7ji.vercel.app](https://portfolio-rho-ten-c7t3equ7ji.vercel.app)
- Стек: Next.js 14, TypeScript, CSS, Vercel

### 📈 Trading Assistant Pro — кокпит трейдера
Веб-дашборд для трейдеров: живые торговые сессии с таймерами и детектом окна
Лондон × Нью-Йорк, котировки, экономический календарь, обзор рынка с
волатильностью (ATR), макро-барометр (DXY, US10Y, VIX, страх/жадность крипты),
COT-позиционирование крупных игроков, корреляция пар, калькуляторы риска,
конвертер валют, чек-лист дисциплины и журнал сделок. Интерфейс на русском и
английском, светлая/тёмная тема.

- 🔗 Демо: [trading-assistant-pro.vercel.app](https://trading-assistant-pro.vercel.app)
- 💻 Код: [github.com/Bayazzzi/TradingAssistantPro](https://github.com/Bayazzzi/TradingAssistantPro)
- Стек: Next.js, TypeScript, Tailwind CSS

### 📄 Генератор КП и счетов
Веб-сервис для малого бизнеса и самозанятых в Казахстане: заполнил форму —
получил готовый PDF (счёт на оплату, коммерческое предложение или акт
выполненных работ) на русском или казахском языке. Автоподстановка реквизитов
по БИН, расчёт НДС 12%.

- 🔗 Демо: [kp-invoice-generator.vercel.app](https://kp-invoice-generator.vercel.app)
- 💻 Код: [github.com/Bayazzzi/kp-invoice-generator](https://github.com/Bayazzzi/kp-invoice-generator)
- Стек: Next.js, TypeScript, Tailwind CSS, @react-pdf/renderer

### 🔳 QR-генератор для облачных дисков
Вставил публичную ссылку на папку Яндекс.Диска или Google Диска — получил
QR-код с логотипом, оформлением и рамкой с подписью. Мастер из четырёх шагов,
экспорт в PNG, SVG и JPG до 4096 px. Приложение разбирает ссылку и
предупреждает о непубличных адресах, которые не откроются у других, а готовый
код тут же декодирует обратно и показывает, читается он или нет. Всё считается
в браузере — ссылки и логотипы никуда не отправляются.

- 🔗 Демо: [qr-code-generator-jade-eight.vercel.app](https://qr-code-generator-jade-eight.vercel.app)
- 💻 Код: [github.com/Bayazzzi/qr-code-generator](https://github.com/Bayazzzi/qr-code-generator)
- Стек: JavaScript, Canvas, SVG, qr-code-styling, jsQR

### 💇‍♀️ Telegram-бот для записи на услуги
Бот для записи клиентов к мастеру (бьюти-сфера, консультации): клиент
выбирает услугу, дату и время в пару кликов, а мастер получает уведомление
о новой записи.

- 💻 Код: [github.com/Bayazzzi/telegram-booking-bot](https://github.com/Bayazzzi/telegram-booking-bot)
- Стек: Python, aiogram 3.x, SQLite

### ⏱️ Session Timer — мировые торговые сессии
Живые аналоговые часы и таймеры пяти мировых торговых сессий (Веллингтон,
Сидней, Токио, Лондон, Нью-Йорк): видно, какая сессия открыта сейчас и
сколько осталось до её закрытия или до следующего открытия. Часовые пояса и
переход на летнее время учитываются автоматически.

- 🔗 Демо: [session-timer-five.vercel.app](https://session-timer-five.vercel.app)
- 💻 Код: [github.com/Bayazzzi/session-timer](https://github.com/Bayazzzi/session-timer)
- Стек: JavaScript, HTML, CSS

### 📜 Конституция Казахстана — интерактивное веб-издание
Удобный веб-интерфейс для чтения и навигации по тексту Конституции РК:
аккуратная типографика, понятная структура разделов, комфортное чтение
на любом устройстве.

- 🔗 Демо: [kazakhstan-constitution.vercel.app](https://kazakhstan-constitution.vercel.app)
- 💻 Код: [github.com/Bayazzzi/kazakhstan-constitution](https://github.com/Bayazzzi/kazakhstan-constitution)
- Стек: HTML, CSS

### 🎓 Финансовая грамотность — обучающая платформа
Бесплатный ресурс с короткими уроками по 10–15 минут, интерактивными заданиями
и мини-тестами. Четыре трека: «Дети 7–12», «Подростки 13–17», «Взрослые-новички»
и «Взрослые-продвинутые». Контент хранится в репозитории и проверяется схемами
перед сборкой, прогресс гостя — в браузере, у вошедшего — в Supabase.

- 🔗 Демо: [fin-learn-lime.vercel.app](https://fin-learn-lime.vercel.app)
- Стек: Next.js 16, React 19, TypeScript, Tailwind CSS, Supabase, Zod

### 🐷 Копилка — трекер челленджа накоплений
PWA для челленджа «каждый день на 10 тг больше»: ставится на экран iPhone,
присылает push-напоминания, считает долг за пропущенные дни и хранит прогресс
каждого пользователя отдельно. Рассылку запускает pg_cron в Supabase.

- 🔗 Демо: [kopilka-theta.vercel.app](https://kopilka-theta.vercel.app)
- Стек: JavaScript, PWA, Web Push, Vercel Functions, Supabase

### 🍽️ Семейное меню
PWA, которое отвечает на вопрос «что готовим и что купить?»: меню на неделю с
автоподбором блюд под бюджет, общий для семьи список покупок с учётом домашних
запасов в реальном времени, учёт расходов и прогноз по меню.

- Стек: Next.js, TypeScript, Supabase (Realtime, RLS), Vercel

### 🚗 Top Drive — сайт автоинструктора
Продающая страница для автоинструктора в Астане: форматы занятий, цены, акция,
FAQ, SEO-разметка. Отзывы подтягиваются из 2ГИС скриптом и обновляются
автоматически через GitHub Actions.

- Стек: HTML, CSS, JavaScript, GitHub Actions

### 🧑‍💼 HR Partner Kazakhstan — сайт HR-аутсорсинга
Корпоративный сайт компании по HR-аутсорсингу и консалтингу: услуги по подбору
персонала и кадровому делопроизводству для бизнеса.

- Стек: HTML, CSS, JavaScript, Vercel

### 🧪 QA Practice Stand — стенд для тестировщиков
Flask-приложение с типичными сценариями (логин, регистрация, задачи, REST API)
и автотестами на Pytest + Playwright, плюс шаблоны тест-кейсов и баг-репортов.

- 💻 Код: [github.com/Bayazzzi/qa-practice-stand](https://github.com/Bayazzzi/qa-practice-stand)
- Стек: Python, Flask, Pytest, Playwright

## 🛠️ Стек

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2CA5E0?style=flat&logo=telegram&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## 📊 GitHub

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Bayazzzi&show_icons=true&hide_border=true&theme=tokyonight)

## 📫 Связаться

- Telegram: [@mr_bayazi](https://t.me/mr_bayazi)
- WhatsApp: [+7 708 223 33 22](https://wa.me/77082233322)
- GitHub: [@Bayazzzi](https://github.com/Bayazzzi)
