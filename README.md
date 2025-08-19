# Vite React SPA → Static on Vercel

**Deploy (Dashboard):**
1. Import repo/folder in Vercel.
2. Framework: **Vite**. Build Command: `npm run build`. Output Directory: `dist`.
3. Deploy.

**Deploy (CLI):**
```bash
npm i -g vercel
npm i
npm run build
vercel deploy --prebuilt  # or just `vercel`
vercel --prod
```

SPA deep links work via `vercel.json` rewrite to `/index.html`.
