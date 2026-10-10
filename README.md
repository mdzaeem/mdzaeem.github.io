# Mohammed Zaeem – Portfolio

A simple static website. No build step and no installs needed.

## Files
- `index.html` – all the text and page structure (projects, experience, about, contact)
- `style.css` – colors, fonts, spacing and layout
- `script.js` – project pop-ups (case studies), dark mode button, mobile menu
- `assets/` – photos, diagrams and the résumé PDF

## How to change things
- **Text** (headline, about, experience, project cards): edit `index.html`.
- **Project pop-up text** (challenge, what I built, stack): edit the `projects` list at the top of `script.js`.
- **Colors and fonts**: edit the `:root{...}` line at the top of `style.css`.
- **Photos and diagrams**: replace the file in `assets/` with a new file that has the same name.
- **Résumé**: replace `assets/Mohammed_Zaeem_Resume.pdf` with your new PDF, keeping the same name.

## Preview on your computer
Open `index.html` in a browser, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

## Publish on GitHub Pages
Upload all of these files and the `assets` folder to the repository `mdzaeem.github.io`
(Add file > Upload files), then commit. In Settings > Pages, use branch `master` and folder `/ (root)`.
The site updates a minute or two after each commit.
