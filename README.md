# Стайлгайд по оформлению задач в Jira

Руководство по стилю для написания и оформления задач в Jira, разработанное
по методологии Docs as Code.

- Сайт: <https://mrundercat.github.io/style-guide-project/>
- Порядок внесения изменений: [CONTRIBUTING.md](CONTRIBUTING.md)

## Локальный запуск

```bash
pip install -r requirements.txt
mkdocs serve
```

Сайт откроется по адресу <http://127.0.0.1:8000>.

## Проверка

```bash
mkdocs build --strict
npx markdownlint-cli2 "docs/**/*.md" "*.md"
```
