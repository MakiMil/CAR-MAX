# СММ-CAR_MAX

Готовый сайт для GitHub Pages (уже собран).

## Как выложить

1. Создайте новый репозиторий на GitHub (можно без README).
2. Загрузите **все файлы из этой папки** в корень репозитория
   (index.html, assets, brands, logo.png, .nojekyll).
3. GitHub → **Settings** → **Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main** (или master), папка **/ (root)**
   - Save
4. Через 1–2 минуты сайт будет по адресу:
   `https://ВАШ_НИК.github.io/ИМЯ_РЕПОЗИТОРИЯ/`

## Важно

- Файл `.nojekyll` не удаляйте — он нужен GitHub Pages.
- Данные машин хранятся в браузере (localStorage) у каждого пользователя отдельно.

## Локальная проверка

Откройте `index.html` через любой статический сервер, либо:

```bash
npx serve .
```