# Ever Clean Anderson - Website

Static website for Ever Clean Anderson (Touchless Mobile Car Wash).

## Deploy on GitHub Pages
1. Create a GitHub repo (example: `ever-clean-anderson`)
2. Upload all files from this project
3. Go to **Settings → Pages**
4. Under “Build and deployment” select:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
5. Save. Your site will appear at:
   `https://YOUR-GITHUB-USERNAME.github.io/ever-clean-anderson/`

## Add your hero image
Put your image at:
`assets/img/hero.webp`

## Optional: make the form submit without opening email
The default form uses `mailto:` which opens the visitor’s email app.

If you want a real form submission (recommended), use Formspree:
1. Create a Formspree form and copy your endpoint URL
2. In `index.html`, replace the form tag:

<form class="form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">

3. Make sure inputs have `name=""` fields (they already do)
4. Optionally add a redirect:
<input type="hidden" name="_redirect" value="https://YOUR-GITHUB-USERNAME.github.io/ever-clean-anderson/#contact" />

## Update sitemap + robots
Edit:
- `robots.txt`
- `sitemap.xml`

Replace `YOUR-GITHUB-USERNAME` with your GitHub username.
