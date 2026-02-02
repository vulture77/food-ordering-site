# 🚀 Deployment Guide

## Quick Start - Upload to GitHub

### Step 1: Create New Repository

1. Go to [https://github.com/new](https://github.com/new)
2. Fill in the details:
   - **Repository name**: `food-ordering-site`
   - **Description**: "Mobile-first food ordering website"
   - **Visibility**: Public ✓
   - **Initialize**: Check "Add a README file" ✓
3. Click **"Create repository"**

### Step 2: Upload Files

You have **3 files** to upload:
- `index.html` (main website)
- `README.md` (documentation)
- `vercel.json` (deployment config)
- `.gitignore` (optional)

**Method A: Via Web Interface (Easiest)**

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from this folder
3. Scroll down and click **"Commit changes"**

**Method B: Via Command Line**

```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/food-ordering-site.git
cd food-ordering-site

# Copy all files here
# Then:
git add .
git commit -m "Initial commit: Food ordering website"
git push origin main
```

### Step 3: Deploy to Vercel

1. Go back to [Vercel Dashboard](https://vercel.com/dashboard)
2. Click **"Add New"** → **"Project"**
3. Find your `food-ordering-site` repository
4. Click **"Import"**
5. Click **"Deploy"** (no configuration needed!)
6. Wait 30-60 seconds
7. 🎉 Your site is live! Copy the URL

## Alternative: Deploy to Netlify (Faster)

1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop just the `index.html` file
3. Instant deployment - get your URL immediately!

## Your Live URLs

After deployment, you'll get URLs like:
- **Vercel**: `https://food-ordering-site.vercel.app`
- **Netlify**: `https://random-name-12345.netlify.app`

You can customize these URLs in the platform settings!

## Updating Your Site

After making changes:

1. Edit files in your repository
2. Commit and push changes to GitHub
3. Vercel/Netlify will auto-deploy updates
4. Your site updates in ~30 seconds

## Need Help?

- **Can't find repository in Vercel?** Refresh the page or adjust GitHub permissions
- **404 Error?** Make sure `index.html` is in the root directory
- **Site not updating?** Check deployment logs in Vercel/Netlify dashboard
