# GitHub Pages Setup Guide

## Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `hadoop-viz` (or any name you like)
3. Make it **Public** (required for free GitHub Pages)
4. **Don't** initialize with README, .gitignore, or license
5. Click "Create repository"

## Step 2: Connect and Push Your Code

After creating the repo, GitHub will show you commands. Use these instead (already set up):

```bash
cd /Users/prithvikishan/hadoop-viz
git remote add origin https://github.com/YOUR_USERNAME/hadoop-viz.git
git branch -M main
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username!**

## Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under "Source":
   - Select **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **Save**

## Step 4: Your Site is Live!
Your site will be available at:
```
https://YOUR_USERNAME.github.io/hadoop-viz/
```

(It may take 1-2 minutes to deploy)

## Quick Commands Reference

```bash
# Navigate to project
cd /Users/prithvikishan/hadoop-viz

# Add remote (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/hadoop-viz.git

# Push to GitHub
git push -u origin main

# If you make changes later:
git add .
git commit -m "Update visualization"
git push
```

