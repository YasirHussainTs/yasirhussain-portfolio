# Yasir Hussain · Portfolio (v2)

A static site. No build step, no dependencies.

## Files
- `index.html` – the whole portfolio (layout, styles, interactions)
- `YasirHussain-Resume-2026.pdf` – original resume, used by every "Download CV" button
- `yasir.jpg` – profile photo (top bar)
- `favicon.svg` – browser tab icon
- `vercel.json` – Vercel settings (clean URLs)

## Deploy to Vercel
**Option A – drag and drop**
1. Go to vercel.com → Add New → Project.
2. Upload this folder (or push it to a GitHub repo and import it).
3. Framework preset: **Other**. Build command: *empty*. Output directory: *empty* (root).
4. Deploy.

**Option B – Vercel CLI**
```
npm i -g vercel
cd yasir-portfolio
vercel --prod
```

## Update the resume
Replace `YasirHussain-Resume-2026.pdf` with a new file of the **same name** and redeploy.

## Preview locally
Double-click `index.html`, or run `npx serve .` and open http://localhost:3000
