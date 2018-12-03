# Kali Linux - Forensics mode

## Подготовка к работе

```
npm install -g gulp
npm install
```

## Структура проекта

- app/pages - страницы, которые должны будут скомпилированы в HTML
- app/templates - nunjucks-части и другие nunjucks-файлы, которые добавляются к файлам в app/pages
- app/public - скомпилированные страницы

## Компиляция страниц
```
gulp nunjucks
```