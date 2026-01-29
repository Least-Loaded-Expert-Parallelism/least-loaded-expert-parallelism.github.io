# LLEP Project Page

Project page for "Least-Loaded Expert Parallelism: Load Balancing An Imbalanced Mixture-of-Experts"

## Local Development

### Option 1: Python (Recommended)
```bash
cd llep-project
python3 -m http.server 8000
```
Then open http://localhost:8000

### Option 2: Node.js
```bash
npx serve .
```

### Option 3: VS Code
Install "Live Server" extension, right-click `index.html` → "Open with Live Server"

## Deploy to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Create a new repository named `llep` (or any name you prefer)
3. Keep it public for free GitHub Pages hosting

### Step 2: Push Code
```bash
cd llep-project

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: LLEP project page"

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/llep.git

# Push
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/llep/`

## Project Structure
```
llep-project/
├── index.html      # Main page
├── imgs/           # Images
│   ├── standard_ep2.png
│   ├── loadbal_ep2.png
│   ├── gptoss20b_expert_alloc.png
│   └── gptoss20b_gpu_alloc.png
└── README.md
```

## Customization

### Update Authors
Edit the `.authors` section in `index.html`:
```html
<div class="authors">
    <a href="https://author-website.com" class="author" target="_blank">
        <img src="path/to/photo.jpg" class="author-img">
        <span class="author-name">Author Name</span>
    </a>
    <!-- Add more authors -->
</div>
```

### Update Links
- Paper link: Search for `Read the Paper` button
- GitHub link: Search for `GitHub` button
- BibTeX: Search for `bibtex-code` class

## License
CC BY-SA 4.0
