# Gazprom Business Online

Набор HTML-страниц для входа, регистрации и восстановления данных. Проект оформлен как статическая веб-страница.

<!-- Скриншот проекта: ./docs/screenshot.png (файл пока не добавлен) -->

## Быстрый старт

Сборка не требуется. Откройте `login.html`, `registration.html` или `forgot-data.html` в браузере либо запустите любой HTML-файл через расширение Live Server в VS Code.

## Стек

- HTML — страницы интерфейса.
- CSS — стили в `css/`.
- Шрифт Noto Sans в форматах WOFF и WOFF2.
- SVG-спрайт и отдельные SVG-иконки; изображения PNG.

SCSS, JavaScript и система сборки по имеющимся файлам не подтверждены.

## Возможности

- Страницы входа, регистрации и восстановления данных.
- Изображение CAPTCHA на странице восстановления данных.
- В коммите `307ba52` заявлен сброс состояния ошибки; детали поведения требуют уточнения.

## Структура проекта

```text
css/
  global/visually-hidden.css
  normalize.css
  style.css
fonts/
  noto-sans-regular.woff
  noto-sans-regular.woff2
images/
  captcha.png
  logo-head.png
  sprite.svg
  sprite/                 # SVG-иконки
forgot-data.html
login.html
registration.html
```

## О доработке

Исходная версия находится в `base/original` (тег `original-source`).
Подробности изменений приведены в [CHANGES.md](./CHANGES.md).
Актуальный diff: [base/original...main](https://github.com/romiusricco/gazprom_buisness-online/compare/base/original...main).
Исходник: [дерево `base/original`](https://github.com/romiusricco/gazprom_buisness-online/tree/base/original).

## Лицензия

См. файл [LICENSE](./LICENSE).
