# Information

Тип контента **Патент**.

- `title` - название патента.
- `description` - описание патента.
- `cover` - обложка патента.
  - `url` - адрес обложки.
  - `position-x` - позиция обложки по оси X.
  - `position-y` - позиция обложки по оси Y.
- `patent` - информация о патенте.
  - `number` - номер патента.
  - `date` - информация о датах патента.
    - `priority` - дата приоритета.
    - `registration` - дата регистрации.
    - `expiry` - дата истечения действия патента.
  - `type` - тип патента.
- `date` - дата публикации патента.

## Install

```
git submodule add https://gitlab.com/marketplace-hugo/hugo-ext-patent.git archetypes/patent
```

## Update

```
git submodule update --remote
```
