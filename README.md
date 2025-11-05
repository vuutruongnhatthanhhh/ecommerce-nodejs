# Ecommerce Backend

A modern and responsive **Ecommerce Web App** built for scalability, security, and performance.  
This repository contains the **backend** source code of the project.

---

![Tech Stack Preview](./preview.webp)

## Tech Stack

**Frontend**

- ReactJS
- Shadcn UI
- Tailwind CSS
- Redux Toolkit
- Vite

  [View FrontEnd Repository](https://github.com/vuutruongnhatthanhhh/tjzenn-ecommerce-nodejs)

**Backend**

- Node.js / Express
- Prisma ORM
- JWT Authentication
- MySQL Database

**Cloud & Deployment**

- Cloudinary (Media Storage)
- Docker + VPS Deployment
- GitHub Actions (CI/CD)
- Sentry (Logging & Monitoring)

---

## Demo

📺 Watch the full demo on YouTube:  
[Click to Watch Demo](https://www.youtube.com/watch?v=080oQLMAtt0)

---

## Project Overview

For a complete breakdown of features, architecture, and implementation details:  
[Read Full Project Documentation](https://portfolio.tjzenn.com/projects/ecommerce)

Explore more of my work on my portfolio:  
[Visit My Portfolio](https://portfolio.tjzenn.com)

---

## Module Aliases

(package.json)

In development:

```json
"_moduleAliases": {
  "@": "src"
}
```

In production:

```json
"_moduleAliases": {
  "@": "dist"
}
```

---

## Environment Variables

All required environment variables should be declared in the `.env` file. Example: .env.example

---

## Database Scripts

Backup the database:

```bash
./script/backup.sh
```

Restore the database:

```bash
cd script
./restore.sh ../backup/[filename].sql
```

---

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create and configure your `.env` file
4. Restore db
5. npx prisma db pull
   npx prisma generate
6. Run the development server:
   ```bash
   npm run dev
   ```

For production:

```bash
npm run build
npm run start
```

---
