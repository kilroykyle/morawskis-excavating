# Deploy Morawski Excavating Website

Code pushed to: https://github.com/kilroykyle/morawskis-excavating

## Deploy to Cloudflare Pages (5 minutes)

### Step 1: Create Pages Project
1. Go to https://dash.cloudflare.com/ → **Workers & Pages**
2. Click **Create application** → **Pages** → **Connect to Git**
3. Select repository: `kilroykyle/morawskis-excavating`
4. Configure:
   - **Project name**: `morawskis-excavating`
   - **Production branch**: `main`
   - **Build command**: (leave empty)
   - **Build output directory**: `/`
5. Click **Save and Deploy**
6. Wait for deployment to finish (~30 seconds)

### Step 2: Add Custom Domain
1. In the Pages project, click **Custom domains**
2. Click **Set up a custom domain**
3. Enter: `morawskis.com`
4. Click **Continue** (Cloudflare auto-creates DNS)
5. Also add: `www.morawskis.com` (optional)

Wait ~1 minute for DNS propagation and SSL provisioning.

---

## Live URLs
- **Production**: https://morawskis.com
- **Cloudflare Pages**: https://morawskis-excavating.pages.dev

---

## Features
- Modern, professional excavation company website
- Services showcase
- Video backgrounds
- Mobile responsive
- Contact information
- Orange/dark theme (brand colors)

---

## Future Updates
To update the site:
```bash
cd /home/kilroy/.openclaw/workspace/morawskis.com
# Make changes to index.html or assets
git add -A
git commit -m "Update website"
git push
```
Cloudflare will auto-deploy in ~30 seconds.

---

## Site Overview
- **Target**: Sophie's family excavation business
- **Location**: Eastern Massachusetts
- **Services**: Excavation, site development, land clearing, septic systems
- **Design**: Professional, modern, construction-focused
