# Windows с нуля

Сайт-визитка цифрового куратора с консультацией по установке Windows 10 и 11.
Свёрстан на чистом HTML и CSS, без сборщиков и JavaScript.

**Живая версия:** https://metaamfik.github.io/windows-s-nulya/

## Страницы и блоки

- Обо мне
- О консультации: формат, длительность, аудитория 16–45 лет
- Программа из пяти циклов на CSS-вкладках
- FAQ
- Контакты: Telegram [@Metaamfik](https://t.me/Metaamfik)

## Структура

```
index.html            — разметка и контент
css/style.css         — стили, адаптив, анимации
assets/logo-mark.svg  — логотип, иконка сайта и favicon
```

## Как открыть

Откройте `index.html` в браузере — сайт работает без сервера и зависимостей.
Шрифт Inter подключается с Google Fonts, при отсутствии интернета используется системный.

## Доступность

- Вкладки переключаются с клавиатуры
- Есть skip-link и видимый фокус
- Учитывается `prefers-reduced-motion`
- Lighthouse: Accessibility, Best Practices, SEO — 100
