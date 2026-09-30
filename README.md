# Uttaravalli Uma Portfolio

A responsive single-page portfolio website for Uttaravalli Uma, built with HTML5, CSS3, and Bootstrap 5.

## Project Overview

This portfolio includes:
- Hero section with profile image
- About/Career Objective section
- Skills cards
- Education table
- Internship experience timeline
- Project showcase card
- Certifications section
- Achievements section
- Contact section with clickable email, phone, LinkedIn, and GitHub links
- Resume page and resume download option

## Files

- `index.html` – main portfolio page
- `resume.html` – resume view page
- `style.css` – styling and responsive layout
- `script.js` – mobile menu and footer year behavior
- `assets/` – local images and favicon

## Local Preview

Open `index.html` directly in a browser, or run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## GitHub Upload

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repository>.git
git push -u origin main
```

## Netlify Deployment

1. Push the project to GitHub.
2. Go to Netlify.
3. Click "Add new project" > "Import an existing project".
4. Select the GitHub repository.
5. Use these settings:
   - Build command: leave empty or do not set one
   - Publish directory: `.`
6. Deploy the site.

Since this is a static site, no build command is required.

## Notes

- This site is directly deployable to Netlify.
- No backend, database, Node.js, or package installation is needed.
- All content is based only on the provided Uma resume information.
