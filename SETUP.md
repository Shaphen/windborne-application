# GitHub Repository Setup Instructions

## Option 1: User Site Repository (Recommended for your URL)

Your URL `https://shaphen.github.io/windborne_application_answers.html` suggests you want to use a **user site repository**.

### Steps:

1. **Create the repository on GitHub:**
   - Go to https://github.com/new
   - Repository name: `shaphen.github.io` (must match your username exactly)
   - Make it **Public**
   - Do NOT initialize with README, .gitignore, or license
   - Click "Create repository"

2. **Push your code:**
   ```bash
   cd /Users/chepu/Desktop/windborne-application
   git remote add origin https://github.com/shaphen/shaphen.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your site:**
   - Your HTML will be available at: `https://shaphen.github.io/windborne_application_answers.html`
   - It may take a few minutes for the site to be live

## Option 2: Project Site Repository

If you prefer a project repository instead:

1. **Create the repository on GitHub:**
   - Go to https://github.com/new
   - Repository name: `windborne-application` (or any name you prefer)
   - Make it **Public**
   - Do NOT initialize with README, .gitignore, or license
   - Click "Create repository"

2. **Push your code:**
   ```bash
   cd /Users/chepu/Desktop/windborne-application
   git remote add origin https://github.com/shaphen/windborne-application.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Update your JavaScript file:**
   - Change the `submission_url` to: `https://shaphen.github.io/windborne-application/windborne_application_answers.html`

## Troubleshooting

- If GitHub Pages doesn't work immediately, wait 5-10 minutes and refresh
- Make sure the repository is set to **Public** (required for free GitHub Pages)
- Check that the file is in the root directory of the repository

