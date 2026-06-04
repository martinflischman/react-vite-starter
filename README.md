# React Vite Starter

A personal starter template with React, Vite, Tailwind CSS v4, and daisyUI v5 — ready to build from.

## Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [daisyUI v5](https://daisyui.com/)

## What's included

- Tailwind CSS v4 configured via `@tailwindcss/vite`
- daisyUI v5 loaded as a CSS plugin
- Clean `App.jsx` with no boilerplate
- `src/components/` folder ready to go
- `.env.local` for environment variables (gitignored)
- `.gitignore` covering `node_modules`, `dist`, `.env`, and `*.local`
- Vite boilerplate removed

## How to use

Click **Use this template → Create a new repository**, name your project, then clone it locally.

```bash
git clone https://github.com/YOUR_USERNAME/your-project-name.git
cd your-project-name
npm install
```

Then open in VS Code:

```bash
code .
```

Run the dev server:

```bash
npm run dev
```

Open `localhost:5173` — you're ready to build.

## Environment variables

Add your variables to `.env.local`:

```
VITE_EXAMPLE_KEY=your_key_here
```

Vite exposes any variable prefixed with `VITE_` to the client via `import.meta.env`.
