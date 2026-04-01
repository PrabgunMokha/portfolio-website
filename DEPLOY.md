# Deployment Guide — Prabgun Mokha Portfolio

## How to Deploy on Vercel (Free Tier)

The revamped portfolio is a **single HTML file** — zero build step required.

### Option A: Deploy via Vercel Dashboard (Easiest)
1. Go to [vercel.com](https://vercel.com) and log in
2. Click **"Add New Project"**
3. Drag and drop the `index.html` file OR upload the folder
4. Vercel will auto-detect it as a static site
5. Click **Deploy** — done in under 30 seconds!

### Option B: Replace Files in Your Existing Repo
1. In your existing `portfolio` repo, copy `index.html` into the **`dist/`** folder (overwrite the existing one) OR into the **root** of the repo
2. If placing in root, create a `vercel.json`:
```json
{
  "rewrites": [{ "source": "/(.*)", "destination": "/index.html" }]
}
```
3. Push to GitHub — Vercel auto-redeploys

### Option C: Fresh Static Site Deploy (Recommended for clean start)
1. Create a new folder with just `index.html`
2. Run: `npx vercel --prod` from that folder
3. Done!

## "Get in Touch" Form — How it Works

The contact form uses `mailto:` links. When someone clicks **Send Message**:
- Their **default email app** (Gmail, Outlook, etc.) opens
- It pre-fills: To, Subject (with reason), and Body (with all form data)
- They click Send in their email app

**This works on Vercel free tier** with zero backend/serverless needed.

> For a true serverless form, you can upgrade later to Formspree, EmailJS, or a Vercel serverless function.

## What Was Changed

- Complete visual redesign with dark luxury aesthetic (Syne + DM Mono + Instrument Serif)
- Animated canvas starfield background
- Typewriter effect cycling through roles
- Sticky nav with scroll effect
- Hero panel with live stats
- Filterable project grid with expand/collapse
- Education cards with timeline accent
- Contact form with mailto integration
- Scroll-reveal animations throughout
- Fully responsive mobile layout
