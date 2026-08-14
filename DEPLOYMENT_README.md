# AI English Tutor Platform — Web Prototype

A complete, single-file HTML prototype of the AI English Tutor + Competitive Exams platform.

## 🌐 Live Demo
Once deployed, your site will be live at a free `.vercel.app` URL (or a custom domain if you connect one).

## 📁 What's in this folder
- `index.html` — the entire platform (landing page + dashboard + all features)
- `vercel.json` — deployment config for Vercel
- `README.md` — this file

## 🚀 Deploy in 5 Minutes

### Option A: GitHub + Vercel (Recommended)

1. **Create a GitHub repo**
   - Go to https://github.com/new
   - Name it e.g. `ai-english-tutor-platform`
   - Keep it Public or Private, click **Create repository**

2. **Upload these files**
   - On the new repo page, click **"uploading an existing file"**
   - Drag in `index.html`, `vercel.json`, and `README.md`
   - Click **Commit changes**

3. **Connect to Vercel**
   - Go to https://vercel.com and sign up/log in with your GitHub account
   - Click **Add New → Project**
   - Select your `ai-english-tutor-platform` repo → click **Import**
   - Framework Preset: choose **Other** (it's a static site)
   - Click **Deploy**

4. **Done!**
   - Vercel gives you a live URL like `https://ai-english-tutor-platform.vercel.app`
   - Every time you push changes to GitHub, Vercel auto-redeploys

### Option B: Vercel CLI (no GitHub needed, fastest)

```bash
npm install -g vercel
cd deploy
vercel
```
Follow the prompts (login, confirm project name) — you'll get a live URL in under a minute.

### Option C: Netlify Drop (zero setup, drag & drop)

1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file onto the page
3. Get an instant live URL

### Option D: GitHub Pages (also free)

1. Push `index.html` to a GitHub repo (rename branch to `main` if needed)
2. Go to repo **Settings → Pages**
3. Source: **Deploy from branch** → `main` → `/root`
4. Save — your site is live at `https://<username>.github.io/<repo-name>/`

## 🔄 Making Updates Later
- Edit `index.html` locally (or ask Claude to generate an updated version)
- Push the change to GitHub → Vercel/Netlify auto-updates the live site
- No rebuild steps needed since it's plain HTML/CSS/JS

## 📱 Next Steps (Future)
- Add a real backend (Node.js/Express + PostgreSQL) — already scoped in earlier docs
- Connect authentication (e.g. Auth0, Firebase Auth, or custom JWT)
- Build the dedicated mobile app (React Native / Flutter) once the web platform is validated
- Add a custom domain in Vercel/Netlify settings (e.g. `www.yourbrand.com`)

## 🛠️ Tech Notes
- Pure HTML/CSS/JavaScript — no build step, no dependencies
- Fully static — works on any static hosting (Vercel, Netlify, GitHub Pages, S3, etc.)
- Mobile responsive out of the box
