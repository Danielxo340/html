# Witcher Gaming Website

Темний ігровий веб-сайт присвячений іграм серії "Відьмак" з підтримкою російської мови та професійним геймінговим дизайном.

## Особливості

- ✨ Темна тема з золотими акцентами
- 🎮 Каталог ігор серії "Відьмак"
- 🗂️ Організація ігор за категоріями (Вибрані/Класика)
- 📱 Адаптивний дизайн
- 🔥 PostgreSQL база даних
- ⚡ Сучасний стек технологій

## Технології

- **Frontend**: React, TypeScript, Tailwind CSS, Wouter
- **Backend**: Express.js, Node.js
- **База даних**: PostgreSQL з Drizzle ORM
- **UI Components**: Radix UI + shadcn/ui
- **Стейт менеджмент**: TanStack Query

## Розгортання

### Vercel (Рекомендовано)
1. Форкніть цей репозиторій
2. Підключіть до Vercel
3. Додайте змінні середовища:
   - `DATABASE_URL` - URL PostgreSQL бази даних

### Railway
1. Підключіть GitHub репозиторій
2. Додайте PostgreSQL addon
3. Встановіть змінні середовища

### Render
1. Створіть новий Web Service
2. Підключіть репозиторій
3. Додайте PostgreSQL базу даних

## Змінні середовища

```env
DATABASE_URL=postgresql://username:password@host:port/database
NODE_ENV=production
```

## Локальна розробка

```bash
npm install
npm run dev
```

## База даних

```bash
npm run db:push
```

## Автор

Створено на Replit з любов'ю до серії "Відьмак" 🐺