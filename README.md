# about — сайт-визитка

Личный сайт-визитка fullstack-разработчика (Go · Python · TypeScript · React).

Один файл `index.html` без зависимостей и сборки: анимированный фон из частиц,
эффект печатающегося текста, 3D-наклон карточек, scroll-reveal анимации,
кастомный курсор и «магнитные» кнопки. Поддерживает `prefers-reduced-motion`.

## Запуск локально

Просто откройте `index.html` в браузере.

## Хостинг на GitHub Pages

Деплой автоматический: при каждом пуше в `main` GitHub Actions
(`.github/workflows/deploy.yml`) публикует сайт в ветку `gh-pages`,
откуда его раздаёт GitHub Pages.

Сайт: **https://h1nigami.github.io/about/**

Если Pages не включился автоматически: **Settings → Pages →
Deploy from a branch → `gh-pages` / (root) → Save**.
