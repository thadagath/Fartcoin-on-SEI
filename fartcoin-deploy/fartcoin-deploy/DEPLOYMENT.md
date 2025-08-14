# Deployment Guide

This folder contains a complete, deployment-ready Fartcoin on SEI landing page.

## Quick Deploy Options

### 1. Netlify (Recommended)
1. Drag and drop the `fartcoin-deploy` folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a generated URL
3. Configuration is already included in `netlify.toml`

### 2. Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. In the folder: `vercel`
3. Follow the prompts
4. Configuration is included in `vercel.json`

### 3. GitHub Pages
1. Create a GitHub repository
2. Upload all files from this folder
3. Enable GitHub Pages in repository settings
4. Select "Deploy from a branch" → main branch

### 4. Replit
1. Create a new Repl
2. Upload the `index.html` file
3. Run with: `python3 -m http.server 5000`

### 5. Traditional Hosting
Upload all files to any web server that supports static HTML/CSS/JS.

## File Structure
```
fartcoin-deploy/
├── index.html          # Main website file (complete)
├── README.md           # Project documentation
├── DEPLOYMENT.md       # This deployment guide
├── package.json        # Project metadata
├── netlify.toml        # Netlify configuration
├── vercel.json         # Vercel configuration
└── .gitignore         # Git ignore rules
```

## Features Included
- ✅ Dynamic animated logo with particle effects
- ✅ Red/black/white pixelated design theme
- ✅ Interactive pie chart (90% community, 10% other)
- ✅ Responsive mobile design
- ✅ SEI blockchain branding and benefits
- ✅ Real social media links (X and Telegram)
- ✅ Easter eggs and interactive animations
- ✅ Optimized for performance and SEO

## Testing Locally
Run any of these commands in the folder:
```bash
python3 -m http.server 3000
# or
python3 -m http.server 8000
# or  
npm start
```

## Domain Setup
After deployment, you can:
1. Connect a custom domain through your hosting provider
2. Set up SSL certificate (usually automatic)
3. Configure CDN for better performance

## Social Links Included
- **X (Twitter)**: https://x.com/suifartcoin
- **Telegram**: https://t.me/+NAPif_uwnyU0ZWM1

---

**Ready to deploy!** Just upload this folder to any static hosting service.