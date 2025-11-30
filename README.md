# chapter2
# Nicole Portfolio - Next.js 14

Portfolio website modern dengan tema cokelat hangat, built with **Next.js 14 (App Router)**, **TypeScript**, dan **Tailwind CSS**.

## Fitur
- **Home & Portfolio**: Grid showcase proyek UI/UX.
- **Blog**: Sistem filtering kategori (Web Dev, UI/UX, Tutorial, dll.) dengan 6+ artikel.
- **Routing**: Dynamic routes untuk detail blog (`/blog/[slug]`).
- **SEO**: Metadata dinamis per halaman.
- **Responsive**: Mobile-first design.

## Tech Stack
- Next.js 14 + TypeScript
- Tailwind CSS
- Date-fns (untuk formatting tanggal)

## Setup Lokal
1. Clone repo: `git clone https://github.com/Abdurrosy1d/chapter2.git`
2. Install deps: `npm install`
3. Jalankan dev server: `npm run dev`
4. Buka [http://localhost:3000](http://localhost:3000)

## Deployment
- Vercel: Connect GitHub repo langsung.
- Netlify: Drag-drop `dist` folder setelah build (`npm run build`).

## Blog Data
Edit di `src/data/blogData.ts` untuk tambah post baru.

Made with ❤️ by Abdurrosyid | [Live Demo](https://your-deployed-url.com)
