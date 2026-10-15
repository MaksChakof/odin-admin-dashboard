# Admin Dashboard

Панель управления — проект курса [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard) (Intermediate HTML and CSS).

**Живая страница:** https://makschakof.github.io/odin-admin-dashboard/

## Что внутри

- Каркас страницы — CSS Grid с областями: `grid-template-areas` раскладывает меню, шапку и основную часть, меню тянется на всю высоту.
- Карточки проектов — `repeat(auto-fit, minmax(16rem, 1fr))`: колонок столько, сколько влезет, без `@media`.
- Мелкие ряды (меню, шапка, значки в карточке) — Flexbox.
- Иконки — шрифт Material Symbols от Google Fonts, аватары — инициалы на CSS.
- Узкий экран: боковая колонка уходит под проекты, на телефоне меню встаёт сверху.
