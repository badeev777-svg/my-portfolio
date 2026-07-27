# Правила работы с проектом

## Структура

- Весь сайт — один файл `index.html`. Не создавать отдельные HTML-страницы.
- Никаких внешних библиотек (Bootstrap, jQuery и т.д.). Только чистый HTML, CSS, JavaScript.
- Стили и скрипты — встроенные, внутри `index.html`.

## Дизайн

- Фон: тёмный
- Текст: светлый
- Акцентный цвет: фиолетово-циановый градиент
- Адаптивная вёрстка — сайт должен хорошо выглядеть на мобильных устройствах.

## Стиль текста

- Простой и дружеский язык — как будто объясняешь знакомому.
- Без канцелярита: не "осуществляется реализация", а "делаю и продаю".
- Короткие предложения, никакой воды.

## Процесс работы

- Перед созданием нового файла или крупным изменением — сначала описать, что планируется сделать, и дождаться подтверждения.
- Мелкие правки (текст, цвет, ссылка) — вносить сразу без согласования.

## graphify

This project has a graphify knowledge graph at graphify-out/.

Rules:
- Before answering architecture or codebase questions, read graphify-out/GRAPH_REPORT.md for god nodes and community structure
- If graphify-out/wiki/index.md exists, navigate it instead of reading raw files
- After modifying code files in this session, run `graphify update .` to keep the graph current (AST-only, no API cost)
