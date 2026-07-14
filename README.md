# BROTHER TILL DEATH — BTD Website

## Deploy to Vercel

### Option 1: Vercel CLI (Recommended)

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy this folder:
```bash
cd btd-vercel
vercel --prod
```

4. Your site is live! Vercel will give you a URL like:
```
https://btd-website.vercel.app
```

### Option 2: Vercel Dashboard (Drag & Drop)

1. Go to https://vercel.com
2. Sign up / Log in
3. Click "Add New..." → "Project"
4. Import from GitHub OR
5. Click "Upload" and drag this entire `btd-vercel` folder
6. Click "Deploy"

### Option 3: GitHub + Vercel (Auto-deploy)

1. Create a GitHub repo
2. Upload all files from this folder
3. Go to Vercel → "Add New Project"
4. Import your GitHub repo
5. Framework Preset: **Other**
6. Click "Deploy"
7. Every git push auto-deploys!

## Custom Domain

1. In Vercel dashboard, go to your project
2. Settings → Domains
3. Add your domain (e.g., `brothertilldeath.com`)
4. Follow Vercel's DNS instructions
5. SSL certificate is automatic (Let's Encrypt)

## File Structure

```
btd-vercel/
├── index.html          # Main website
├── vercel.json         # Vercel config
├── images/
│   ├── logo-black.png  # BTD blackletter logo
│   └── logo-gold.png   # Gold embroidery logo
└── README.md           # This file
```

## Admin Access

Click the **"Admin"** button in the top navigation to:
- Add/edit/delete products
- View and manage orders
- See analytics and AI insights
- Set drop countdown dates
- Export/backup all data

All data is stored in the browser (localStorage).

## Contact

- WhatsApp: +20 114 014 3165
- Instagram: https://www.instagram.com/249b.t.d
- TikTok: https://tiktok.com/@b.t.d2490
