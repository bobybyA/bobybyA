# GitHub Setup Instructions

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `bobybyA_website` (or your preferred name)
3. Description: "Personal trainer website for Body by A"
4. Choose **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

## Step 2: Push Your Code

After creating the repository, GitHub will show you commands. Use these commands (replace YOUR_USERNAME with your GitHub username):

```bash
git remote add origin https://github.com/YOUR_USERNAME/bobybyA_website.git
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** in the left sidebar
4. Under "Source", select **main** branch
5. Click **Save**
6. Your site will be live at: `https://YOUR_USERNAME.github.io/bobybyA_website/`

Wait a few minutes for GitHub to build and deploy your site!

