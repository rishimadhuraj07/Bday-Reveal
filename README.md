# Birthday Surprise — Vercel Ready

A mobile-first, cinematic interactive birthday experience built with Next.js, React, TypeScript and Framer Motion.

## Important deployment detail

This project intentionally uses the **Next.js Pages Router**. The entry point is:

- `pages/index.tsx`
- `pages/_app.tsx`

The `pages` directory is directly at the repository root so Vercel can detect it without a Root Directory override.

## Run locally

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm start
```

## Personalization

Edit `lib/config.ts`:

- `name` — birthday person's name
- `senders` — sender names
- `messages` — customizable messages
- `theme` — accent colors

## Deploy to Vercel

Push the contents of this directory to the root of your GitHub repository and import that repository into Vercel.

Use the default project root (`./`). No environment variables are required.
