# Anshika Dahiya – Portfolio

Single-page static site (`index.html` + `assets/`). No build step.

## Deploy to GitHub Pages (free)
1. Create a public repo named `<username>.github.io` (or any repo, e.g. `portfolio`).
2. Copy everything in this folder (`index.html`, `assets/`, `Anshika_Dahiya_Resume.pdf`) to the repo root and push.
3. Repo → Settings → Pages → Source: `Deploy from a branch`, branch `main`, folder `/ (root)` → Save.
4. Site is live at `https://<username>.github.io/` (or `https://<username>.github.io/portfolio/`).
5. Put that URL into `../resume/Anshika_Dahiya_Resume.html` (the Portfolio link) and regenerate the PDF:
   `"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf=../Anshika_Dahiya_Resume.pdf ../resume/Anshika_Dahiya_Resume.html`

Alternative: drag this folder onto https://app.netlify.com/drop for an instant URL.

## Replacing content
- Photo: `assets/anshika.jpg` (square crop works best).
- Project links: the three `More` buttons in `index.html` currently point to Jivesh's Tableau Public dashboards; swap for Anshika's own once republished.
