# JustuskuNest Starter

Starter project untuk web company profile menggunakan:

- Next.js (`frontend`)
- NestJS (`backend`)

## Struktur Folder

- `frontend` - Next.js App Router + TypeScript + Tailwind CSS
- `backend` - NestJS REST API

## Menjalankan Project

Install dependency root:

```bash
npm install
```

Jalankan frontend + backend bersamaan:

```bash
npm run dev
```

Atau jalankan terpisah:

```bash
npm run dev:frontend
npm run dev:backend
```

## Endpoint Default Backend

- `GET http://localhost:4000/api` -> hello response dari NestJS

## Environment

Salin file contoh:

- `backend/.env.example` -> `backend/.env`
- `frontend/.env.example` -> `frontend/.env.local`
