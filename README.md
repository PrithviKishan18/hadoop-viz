# Hadoop Ecosystem Visualization

Interactive visualization of Hadoop's three core components: HDFS, MapReduce, and YARN.

## Hosting Options

### Option 1: Netlify Drop (Easiest - No Account Needed)
1. Go to https://app.netlify.com/drop
2. Drag and drop `index.html` onto the page
3. Get instant live URL!

### Option 2: GitHub Pages (Free & Permanent)
1. Create a new repository on GitHub
2. Push this folder to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git remote add origin YOUR_GITHUB_REPO_URL
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" → choose `main` branch → `/ (root)`
5. Your site will be live at: `https://YOUR_USERNAME.github.io/REPO_NAME`

### Option 3: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory
3. Follow the prompts

### Option 4: CodeSandbox (Quick Share)
1. Go to https://codesandbox.io
2. Create new → Static Template
3. Upload `index.html`
4. Share the link

### Option 5: Surge.sh (Command Line)
```bash
npm install -g surge
cd /Users/prithvikishan/hadoop-viz
surge
# Follow prompts to get a .surge.sh URL
```

## Local Development
Just open `index.html` in your browser - it works offline!

