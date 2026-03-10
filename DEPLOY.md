# 🚀 Deployment Guide

## Fastest Method: Netlify Drop (Recommended)

**No account needed!**

1. **Visit**: https://app.netlify.com/drop
2. **Drag and drop** the `index.html` file onto the page
3. **Done!** Your site is live instantly with a URL like: `https://random-name-123.netlify.app`

### Customize Domain (Optional)
- After deployment, click on your site
- Go to "Domain settings"
- Click "Change site name" to customize

---

## Alternative: GitHub Pages

### Step 1: Create Repository
1. Go to https://github.com/new
2. Name it (e.g., `career-metro`)
3. Make it **public**
4. Click "Create repository"

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag `index.html` and `README.md`
3. Click "Commit changes"

### Step 3: Enable Pages
1. Go to **Settings** → **Pages**
2. **Source**: Deploy from a branch
3. **Branch**: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4: Access Your Site
Your site will be live at:
`https://yourusername.github.io/career-metro`

---

## Alternative: Vercel

1. **Install Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Deploy**:
   ```bash
   cd /Users/vsk/Desktop/NENY
   vercel
   ```

3. Follow the prompts - your site will be live instantly!

---

## Alternative: Cloudflare Pages

1. Go to https://pages.cloudflare.com
2. Connect your GitHub repository
3. Select the repository
4. Build command: (leave empty)
5. Build output directory: `/`
6. Deploy!

---

## Testing Locally

Before deploying, test locally:

```bash
cd /Users/vsk/Desktop/NENY
python3 -m http.server 8000
```

Then visit: http://localhost:8000

---

## Notes

- The app fetches data dynamically from Google Sheets
- No build process needed - pure HTML/CSS/JavaScript
- Works on all modern browsers
- Fully responsive design