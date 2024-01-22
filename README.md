# Content schema

JSON схемы для контента микро курсов

Для того что бы проверить генерируемые типы, можно воспользоваться коммандой
`npm run generate:types`

Для того что бы заменить {cuid} на вызов cuid()
`npm run generate:types`

## Как подключить валидацию

### VSCode

```json
// .vscode/settings.json
{
  "yaml.schemas": {
    "./course.schema.json": "*.course.yaml"
  }
}
```
