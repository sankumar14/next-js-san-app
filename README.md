# next-js-san-app ✅

A small learning project to explore and practice Next.js (App Router) with TypeScript and Tailwind CSS. This repo contains a minimal e‑commerce-like UI with reusable components as my first step learning Next.js.

---

## 🚀 Quick Overview

- **Purpose:** A learning project to get comfortable with Next.js (App Router), TypeScript, and Tailwind CSS.
- **What you'll find:** basic pages, a `ProductCard` component (with CSS module), an `AddToCart` component, and a `users` page.
- **Key tech:** Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS, DaisyUI.

---

## 📁 Project Structure

- `app/` - Next.js App Router pages and layout
  - `page.tsx` - Home page
  - `layout.tsx` - Root layout
  - `globals.css` - Global styles (Tailwind)
  - `components/` - Reusable UI components
    - `AddToCart.tsx` - Add-to-cart UI
    - `ProductCard/` - `ProductCard.tsx` + `ProductCard.module.css`
  - `users/page.tsx` - Example users page
- `public/` - Static assets
- `next.config.js`, `tailwind.config.ts`, `postcss.config.js` - tool config
- `package.json` - scripts & dependencies

---

## 🛠️ Tech Stack

- Next.js 16 (App Router)
- React 19
- TypeScript
- Tailwind CSS
- DaisyUI (dev dependency)
- ESLint

---

## ⚙️ Local Development

Install dependencies and run the dev server:

```bash
npm install
npm run dev
```

Open http://localhost:3000 in your browser. The app supports hot-reloading while you edit files in `app/`.

Build and run production locally:

```bash
npm run build
npm start
```

---

## ✅ What I covered (learning notes)

- Created a Next.js app using the App Router (`app/` directory) and TypeScript.
- Integrated Tailwind CSS for utility-first styling and used a CSS module for `ProductCard` styles.
- Built small, reusable components (`ProductCard`, `AddToCart`) to practice component composition.
- Explored routing by adding a `users` page and learned how layouts and pages interact.

---

## 🔭 Next steps / Ideas

- Add state management (e.g., Zustand or React Context) for cart functionality.
- Integrate a headless CMS or mock API to serve product data.
- Add unit/integration tests for components and pages.
- Deploy to Vercel for live preview.

---

## 🙌 Contributing

This is a personal learning project. Feel free to open issues or PRs if you have suggestions — or use it as a starting point for your own learning.

---

## 📄 License

MIT — feel free to reuse and adapt for learning purposes.

---
