# NoteHub

Застосунок для створення, видалення, пошуку та перегляду нотаток з пагінацією.

## Стек

React + TypeScript + Vite, TanStack Query, Axios, Formik + Yup, React Paginate,
use-debounce, CSS Modules, modern-normalize.

## Запуск

1. Отримайте персональний токен у
   [документації бекенда](https://notehub-public.goit.study/api/docs).
2. Створіть файл `.env` за зразком `.env`:

   ```
   VITE_NOTEHUB_TOKEN=your_token_here
   ```

3. Встановіть залежності та запустіть проєкт:

   ```bash
   npm install
   npm run dev
   ```

## Скрипти

- `npm run dev` — dev-сервер
- `npm run build` — продакшн-збірка
- `npm run lint` — перевірка ESLint
- `npm run format` — форматування Prettier
