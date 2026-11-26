# Fynesse Budget Tracker

Static single-page app (no build step, no environment variables, no backend).
Data is kept in memory and resets on reload.

## Deploy to Vercel via GitHub
1. Create a new repository on GitHub and push this folder:
   ```
   git init
   git add .
   git commit -m "Fynesse Budget Tracker"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo>.git
   git push -u origin main
   ```
2. Go to https://vercel.com/new and sign in with GitHub.
3. Import the repository.
4. Framework Preset: **Other**. Leave Build Command and Output Directory empty. Root Directory: `./`.
5. Click **Deploy**. Every push to `main` redeploys automatically.

## Deploy with the Vercel CLI
```
npm i -g vercel
vercel          # preview deployment
vercel --prod   # production deployment
```

## Local preview
Open `index.html` in a browser.
