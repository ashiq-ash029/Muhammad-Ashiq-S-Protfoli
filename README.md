# Muhammad Ashiq S. — Premium Portfolio

Responsive React + TypeScript portfolio with warm grey, white, charcoal and burnt-orange styling, portrait placeholders, motion effects, project links, SEO/AEO/GEO, video work, education, resume and contact sections.

## Run on Windows
Install Node.js (20+ recommended), extract the ZIP, open PowerShell in this folder, then run:
```powershell
npm install
npm run dev
```
Open the localhost URL printed by Vite.

Build:
```powershell
npm run build
npm run preview
```

## Add your assets
Place your real edited portraits here:
- `public/images/ashiq-hero.webp`
- `public/images/ashiq-about.webp`
Optional illustration: `public/images/skills-3d.webp`

Use real photographs and preserve your identity. If images are absent, the UI shows a placeholder instead of inventing a face. Suggested portrait size: 1200×1500, 4:5, WebP.

Place your actual resume at `public/resume/Muhammad_Ashiq_S.pdf`. Update its path in `src/App.tsx` if the filename differs.

## Personalise before publishing
In `src/App.tsx`, set `CONTACT_EMAIL` and `LINKEDIN_URL` to your real details. Verify all skills against your actual projects. Project descriptions are intentionally cautious; inspect each GitHub repository and edit descriptions/tags to match the implemented code.

The contact form validates input and opens an email draft; it does not submit to a backend. For server-side submissions, connect a real form service.

## Deploy
Run `npm run build`, then deploy the `dist` folder to Vercel or another static host. No backend is required for the portfolio itself.
