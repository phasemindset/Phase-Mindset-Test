# PHASE Mindset Test - Deploy Package

This is a clean Vite + React deploy package built from your PHASE assessment code.

## What changed
- Removed shadcn/ui, Tailwind, and framer-motion dependencies that would have broken a simple Vercel deploy.
- Rebuilt the UI with plain React + CSS so it deploys cleanly.
- Kept your assessment logic, question sets, scoring, blend summary, and results sections.

## Upload to GitHub
Upload all files in this folder to your GitHub repository root.

## Deploy to Vercel
1. Go to Vercel.
2. Import your GitHub repo.
3. Framework should detect as Vite.
4. Click Deploy.

## After deploy
Copy your Vercel URL and paste it into GoHighLevel in this iframe:

```html
<iframe
  src="https://YOUR-VERCEL-URL.vercel.app"
  width="100%"
  height="1200px"
  style="border:none;">
</iframe>
```
