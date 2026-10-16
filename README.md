# Admin Dashboard

Панель управления — проект курса [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard) (Intermediate HTML and CSS).

**Живая страница:** https://makschakof.github.io/odin-admin-dashboard/

## Что внутри

- Каркас страницы — CSS Grid с областями: `grid-template-areas` раскладывает меню, шапку и основную часть, меню тянется на всю высоту.
- Карточки проектов — `repeat(auto-fit, minmax(16rem, 1fr))`: колонок столько, сколько влезет, без `@media`.
- Мелкие ряды (меню, шапка, значки в карточке) — Flexbox.
- Иконки — шрифт Material Symbols от Google Fonts, аватары — инициалы на CSS.
- Узкий экран: боковая колонка уходит под проекты, на телефоне меню встаёт сверху.

## Доступность

- Смысловые теги (`aside`, `nav`, `header`, `main`, `section`, `article`) и заголовки по порядку: `h1` → `h2` → `h3`.
- Значки из шрифта спрятаны от читалок (`aria-hidden`), у кнопок-значков есть имена с названием проекта: «В избранное: Супер крутой проект».
- Ссылка «Перейти к содержимому» появляется при первом нажатии Tab и ведёт сразу к проектам, мимо меню.
- Контраст: синий из макета `#1992d4` давал с белым текстом 3.44:1 (ниже нормы AA 4.5:1), заменён на `#1372a4` — 5.29:1.
- Lighthouse Accessibility: 96 → 100.
