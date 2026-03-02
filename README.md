# Joseph Richards - Portfolio Website

A modern, responsive portfolio website showcasing professional experience, skills, and education.

## Files Included
- `index.html` - Main HTML structure
- `style.css` - Styling and responsive design
- `script.js` - Interactive features and smooth scrolling

## Features
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Animated timeline for experience
- ✅ Modern gradient hero section
- ✅ Interactive skill tags
- ✅ Clean, professional design

## How to Deploy to GitHub Pages

### Step 1: Set Up Git (If Not Already Done)
1. Download and install Git from https://git-scm.com
2. Open VS Code
3. Open Terminal in VS Code (View → Terminal or Ctrl+`)

### Step 2: Create GitHub Repository
1. Go to https://github.com
2. Click the "+" icon in top right → "New repository"
3. Name it `portfolio` (or any name you prefer)
4. Keep it PUBLIC so GitHub Pages works for free
5. Do NOT add README, .gitignore, or license (we'll add our own)
6. Click "Create repository"

### Step 3: Initialize Git in VS Code
Open Terminal in VS Code and run these commands one by one:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
```

### Step 4: Connect to GitHub
Replace `YOUR-USERNAME` with your GitHub username:

```bash
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

You'll be prompted to sign in to GitHub - follow the authentication steps.

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub.com
2. Click "Settings" tab
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

Your website will be live at: `https://YOUR-USERNAME.github.io/portfolio/`

## Customization Tips

### Update Your LinkedIn URL
In `index.html`, line 147, replace the LinkedIn URL with your actual profile:
```html
<a href="https://www.linkedin.com/in/YOUR-PROFILE" target="_blank">LinkedIn Profile</a>
```

### Change Colors
Edit the CSS variables in `style.css` (lines 9-18):
```css
:root {
    --primary-color: #2563eb;  /* Change this to your preferred color */
    --primary-dark: #1e40af;
    /* ... */
}
```

### Update Content
- Edit experience, skills, or education directly in `index.html`
- All content is clearly labeled with comments

## Local Testing
To test locally before deploying:
1. Open `index.html` in your browser
2. Or use VS Code's Live Server extension

## Troubleshooting

**Problem: Changes not showing on GitHub Pages**
- Solution: Wait 2-3 minutes after pushing changes
- Solution: Clear your browser cache (Ctrl+Shift+R)

**Problem: CSS/JS not loading**
- Solution: Make sure all files are in the same directory
- Solution: Check file names are exactly: `index.html`, `style.css`, `script.js`

**Problem: Git authentication fails**
- Solution: Use GitHub's personal access token instead of password
- Guide: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

## Need Help?
Feel free to reach out at jar679@miami.edu

---
Built with HTML, CSS, and JavaScript | Deployed on GitHub Pages
