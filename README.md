# shakyag.github.io

Personal profile site, built as a static GitHub Pages site (plain HTML/CSS, no build step).

## Before you publish — placeholders to fill in

Two things in `index.html` are placeholders and need your real details (search for them, each appears twice):

1. `your.email@example.com` — replace with the email address you want recruiters to use.
   Consider using a personal address rather than a current employer address for a job-search site.
2. `https://www.linkedin.com/in/your-linkedin-handle` — replace with your actual LinkedIn URL.

The GitHub link already points to `github.com/shakyag` — update it if your username differs.

## Publish to GitHub Pages

1. Create a new **public** GitHub repository named exactly `shakyag.github.io` (this exact name is what makes GitHub serve it at that URL).
2. Push these files (`index.html`, `assets/style.css`) to the root of the `main` branch:
   ```
   git init
   git add index.html assets/style.css
   git commit -m "Initial profile site"
   git branch -M main
   git remote add origin https://github.com/shakyag/shakyag.github.io.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, and under "Build and deployment" confirm the source is "Deploy from a branch", branch `main`, folder `/ (root)`. (For a `username.github.io` repo this is usually enabled automatically.)
4. Your site will be live at `https://shakyag.github.io` within a minute or two.

## Editing later

- All content lives in `index.html` — text only, no CMS.
- All styling lives in `assets/style.css` — colors are set as CSS variables at the top of the file (`--ink`, `--accent`, etc.) if you want to adjust the palette.
- The site uses Google Fonts (Fraunces + Inter) loaded via CDN — no local font files to manage.

## Content notes

The Experience and Impact sections reframe your Rystad Energy / Cognite technical delivery
background in product-leadership language — platform ownership, cross-org delivery, architectural
stewardship — aligned with Director/Head of Product roles in platform-heavy, technical
organisations. Update freely as your target roles shift.
