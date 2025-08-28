# Resume Templates (Markdown → PDF via GitHub Actions)

Репозиторий с минималистичными шаблонами резюме.
- `markdown/` — Markdown-шаблоны.
- `html-css/` — (опционально) HTML-версия для печати через браузер.
- Автосборка PDF происходит в **GitHub Actions**. Готовые PDF доступны в разделе **Actions → Artifacts**.

## Как пользоваться (без установки софта на ПК)
1. Сделай форк или залей этот репозиторий к себе.
2. Отредактируй `markdown/minimal.md` под себя.
3. Сделай `git push` — GitHub Actions автоматически соберёт PDF.
4. Зайди в **Actions → последний Workflow → Artifacts → скачай PDF**.

### Локальная правка
- Правишь `markdown/minimal.md` любым редактором.
- Для HTML-версии можешь открыть `html-css/minimal.html` в браузере и распечатать в PDF (Ctrl+P → Сохранить в PDF).

---

### Планы
- Добавить ещё 4 шаблона: Sidebar, Timeline, Grid, Elegant.
- Скрипт сборки всех шаблонов сразу.
- Англоязычная версия шаблонов.
