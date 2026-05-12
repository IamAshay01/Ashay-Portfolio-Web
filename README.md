# Ashay Sonwane Portfolio

This is a simple static portfolio website built from the content of the resume file.

## Files

- `index.html` — main portfolio page
- `styles.css` — styling for the page
- `README.md` — deployment instructions

## How to view locally

1. Open `C:\Users\Swastika\Downloads\AshayPortfolio\index.html` in your browser.

## Deploy options

### GitHub Pages

1. Install Git on Windows: https://git-scm.com/download/win
2. Create a GitHub repository named `AshayPortfolio` or similar.
3. Run these commands in PowerShell:

```powershell
Set-Location 'C:\Users\Swastika\Downloads\AshayPortfolio'
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

4. In GitHub, go to `Settings` > `Pages` and select branch `main` and folder `/ (root)`.
5. After a few minutes, your site will be available at `https://<your-username>.github.io/<repo-name>/`.

### Netlify

1. Sign in at https://app.netlify.com/.
2. Choose "Add new site" > "Deploy manually" or connect GitHub.
3. If deploying manually, drag the entire `AshayPortfolio` folder into Netlify.
4. If connecting GitHub, choose your repo and set the publish directory to `/`.

### Vercel

1. Sign in at https://vercel.com/.
2. Click "New Project" and import your GitHub repository.
3. Set the root directory to `/` and deploy.

## Manual Upload Guide

To upload new photos or a LinkedIn-style post manually:

1. Add your image files to the `AshayPortfolio` folder.
2. Update `index.html` if you want to show new photos in the gallery.
3. Save the updated files and push them to your GitHub repository again.

Example:

- Add `new-photo.jpg` to the portfolio folder.
- In `index.html`, add a new gallery item with `<img src="new-photo.jpg" alt="Description" />`.
- Place your certificate file in the folder and update the download link if it uses a different name.

### LinkedIn post idea

Share a post like this on LinkedIn:

> Excited to continue my Brand Management internship at Nilons Company while pursuing PGDM Marketing. Check out my portfolio and certifications here: `https://iamashay01.github.io/Ashay-Portfolio-Web/`

## Current Role

- Brand Management Intern at Nilons Company
- Supporting brand strategy, marketing assets, and campaign planning

## Notes

- Update the LinkedIn URL and contact details if needed.
- The site now includes a photo gallery.
- Install Git from https://git-scm.com/download/win, then use the commands above to push the site to GitHub.
- If you want, I can also help add portfolio case studies or convert this to a React app.
