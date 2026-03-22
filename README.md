# ResumeForge — Free AI Resume Builder

A free, browser-based AI resume builder with 6 templates, ATS scoring, photo upload, references, and Google AdSense monetisation built in.

## Files

```
resumeforge/
├── index.html     ← The entire app (single file)
├── vercel.json    ← Vercel hosting config
└── README.md      ← This file
```

## Deploy to Vercel (Free — 3 minutes)

### Option A: Drag & Drop (No account needed)
1. Go to https://vercel.com and sign up free
2. Click **Add New → Project**
3. Scroll to the bottom — find **"Deploy without Git"**
4. Drag the entire `resumeforge` folder onto the upload zone
5. Click **Deploy** — live in 30 seconds

### Option B: Via GitHub (Recommended — auto-deploys on every update)
1. Create a free account at https://github.com
2. Click **+** → **New repository** → name it `resumeforge` → **Public** → **Create**
3. Click **uploading an existing file** → drag both `index.html` and `vercel.json` → **Commit changes**
4. Go to https://vercel.com → **Add New → Project** → **Import Git Repository**
5. Select `resumeforge` → click **Deploy**
6. Done. Every future update to GitHub auto-deploys in ~20 seconds.

## Custom Domain
1. Buy a domain at https://namecheap.com (~$12/year)
2. In Vercel: **Settings → Domains** → type your domain → **Add**
3. Copy the two DNS records Vercel shows you
4. In Namecheap: **Domain List → Manage → Advanced DNS** → add those records
5. Wait 5–30 min. Your site is live with free HTTPS.

## Google AdSense Setup
1. Apply at https://adsense.google.com (needs a live deployed site)
2. Once approved (1–3 days), go to **Ads → By ad unit → Display ads**
3. Create 4 ad units — copy each `data-ad-slot` number
4. Visit your live site at: `https://yoursite.com?admin`
5. Click the **💰 Ads** button in the top bar
6. Paste your Publisher ID (`ca-pub-XXXXXXXXXXXXXXXX`) and 4 slot numbers
7. Click **Save & apply** — ads go live immediately

## User API Keys
Users bring their own free AI key. None of your API keys are used.
- Groq: https://console.groq.com/keys (free, 14,400 req/day)
- Gemini: https://aistudio.google.com/app/apikey (free, 1,500 req/day)
- OpenRouter: https://openrouter.ai/keys (free models available)

## Browser Compatibility
Tested and working on:
- Chrome 90+ ✓
- Firefox 88+ ✓
- Safari 14+ ✓
- Edge 90+ ✓
- Mobile Chrome/Safari ✓

## License
Free to use and deploy. 
