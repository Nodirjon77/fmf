# FMF — Complex SW СУСТАВЫ | Landing Page

## Описание проекта
Лендинг-страница для БАД «Complex SW СУСТАВЫ» от Оптисалт.
Разработана по макету Figma (FMF-Test) с использованием ИИ-инструмента **Claude (Anthropic)**.

---

## Структура файлов

```
fmf-project/
├── index.html          — Разметка страницы
├── css/
│   └── style.css       — Стили (CSS Variables + Flexbox/Grid)
├── js/
│   └── main.js         — JavaScript (FAQ, burger, slider)
├── images/
│   ├── logo.png
│   ├── jar.png
│   ├── jar-small.png
│   ├── knee.png
│   ├── powder.png
│   ├── woman.png
│   └── instruction.png
└── README.md
```

---

## Использование ИИ (Claude)

| Задача | Что автоматизировано |
|---|---|
| CSS переменные | Claude сгенерировал полную систему Design Tokens |
| HTML структура | Все 9 секций страницы — скелет и классы |
| Zigzag layout | CSS для чередующихся карточек Benefits |
| FAQ accordion | JavaScript логика открытия/закрытия |
| Burger menu | Мобильная навигация с toggle |
| Responsive | Media queries для 1024px и 768px |
| Комментарии | Все блоки задокументированы |

---

## Секции страницы

1. **Header** — sticky навигация, CTA кнопка
2. **Hero** — главный экран с jar изображением
3. **About** — описание продукта + преимущества
4. **Benefits** — 5 карточек в zigzag layout
5. **CTA Banner** — призыв к действию
6. **Composition** — 9 активных компонентов
7. **For Whom** — слайдер по возрастным группам
8. **Comparison** — сравнение с конкурентами
9. **Price** — блок цены + инструкция
10. **FAQ** — accordion с вопросами и ответами

---

## Оптимизация (SEO & Performance)

- `<meta name="description">` — SEO описание
- `font-display: swap` через Google Fonts — быстрая загрузка шрифтов
- `loading="lazy"` — можно добавить к img для lazy load
- `scroll-behavior: smooth` — нативный CSS scroll
- CSS Variables — один источник правды для цветов
- Семантические теги: `header`, `nav`, `section`, `footer`
- `aria-expanded` на FAQ кнопках — доступность

---

## Технологии

- **HTML5** — семантическая разметка
- **CSS3** — Grid, Flexbox, Custom Properties, clamp()
- **JavaScript** — Vanilla JS, без библиотек
- **Google Fonts** — Montserrat
- **ИИ** — Claude (Anthropic) для генерации и оптимизации кода
