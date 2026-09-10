# Sample Restaurant Website

A single-page, mobile-responsive sample site for a Chicago-style restraunt


## Files

- `index.html` — all page content
- `style.css` — all styling (colors and fonts are set as CSS
  variables at the top of the file, under `:root`)
- `script.js` — mobile menu toggle
- `README.md` — this file

## Before you show this to a real client

Every bracketed placeholder needs to be replaced:

- `[Restaurant Name]` — appears in the page `<title>`, the header
  logo, and the footer
- `[Street Address]`, `[City]`, `[ZIP]` — in the Hours & Location
  section and the footer
- The phone number, email, and Google Maps link
- The menu items and prices — these are generic placeholders, not
  a real menu
- The "Our story" paragraph
- Swap the line-art hot dog graphic in the hero for a real photo if
  you have one — replace the `<svg>` block in `index.html` with an
  `<img>` tag

Search the project for `[` to find every remaining placeholder —
most code editors can do this with a project-wide search.

## Viewing it locally

Just open `index.html` in a browser — no server required.

## Putting it on GitHub

1. Create a new repository on GitHub (github.com → New repository).
   Don't add a README, .gitignore, or license during creation since
   this folder already has its own files.
2. On your computer, in this folder, run:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. To host it for free with GitHub Pages: go to the repo's
   **Settings → Pages**, set the source branch to `main` and the
   folder to `/ (root)`, then save. GitHub will give you a live
   `https://YOUR-USERNAME.github.io/YOUR-REPO/` URL a minute or two
   later.
4. Once the business is ready to use a real domain (e.g.
   `theirname.com`), that domain's DNS just needs to point at
   GitHub Pages — GitHub's docs walk through the exact records to
   add at your registrar.
