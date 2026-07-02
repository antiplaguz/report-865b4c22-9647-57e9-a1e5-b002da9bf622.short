# Antiplag Print Report

Локальная копия страницы «Вывод отчёта в печать» сервиса [Antiplag](https://antiplag.uz/) — статический сайт со всеми ресурсами (стили, скрипты, изображения), готовый к публикации через GitHub Pages / Netlify / Vercel.

## Структура проекта

```
├── index.html                  # страница отчёта
├── assets/
│   ├── css/
│   │   ├── print.css           # стили печатной формы отчёта
│   │   ├── jquery-ui.min.css   # стили jQuery UI
│   │   └── google-fonts.css    # шрифт Open Sans
│   ├── js/
│   │   ├── print.js            # логика круговой диаграммы и подсветки цитат
│   │   └── print-jquery.js     # библиотека jQuery
│   └── images/
│       ├── antiplag-logo.png
│       └── report-preview.png
└── README.md
```

## Запуск

Просто откройте `index.html` в браузере — все пути относительные, ничего дополнительно настраивать не нужно.
