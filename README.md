# Personal Website

Personal portfolio site — plain HTML/CSS/JS, no build step required.

## Structure
- `index.html` — Home / About
- `resume.html` — Resume summary + PDF download
- `projects.html` — Project showcase
- `interests.html` — Interests / hobbies
- `contact.html` — Contact links
- `css/styles.css` — shared styling (light/dark via `prefers-color-scheme`)
- `js/main.js` — mobile nav toggle + active link highlighting
- `assets/resume.pdf` — placeholder resume, replace with the real one
- `assets/images/` — put project screenshots / headshot here

## Preview locally
```
python3 -m http.server 8000
```
Then open http://localhost:8000 in a browser.

## TODO before publishing
- Replace all `[Placeholder]` copy on every page with real content
- Replace `assets/resume.pdf` with your actual resume
- Fill in LinkedIn/GitHub links on `contact.html`
- Add real project entries/screenshots on `projects.html`
- Deploy to GitHub Pages as a user site (`<username>.github.io`)
