# Hatim Mohammed — IT Support | Networking | Cybersecurity Portfolio

A 3-page static portfolio website, ready to deploy on **GitHub Pages**.

## Pages

- `index.html` — Home: name, role, short bio, and action buttons (View Projects / Download Resume / LinkedIn / GitHub)
- `about.html` — About Me: background, education, target field, and what sets Hatim apart
- `skills.html` — Technical Skills: grouped by Operating Systems, Networking, IT Support, Virtualization, Programming, Security

## Structure

```
portfolio/
├── index.html
├── about.html
├── skills.html
├── README.md
├── resume/
│   └── (put Hatim-Mohammed-Resume.pdf here)
└── assets/
    ├── style.css
    └── script.js
```

## Before you publish — replace these placeholders

| Location | Placeholder | Replace with |
|---|---|---|
| All pages, footer & hero buttons | `https://www.linkedin.com/in/your-linkedin-handle` | Your real LinkedIn URL |
| All pages, footer & hero buttons | `https://github.com/your-github-handle` | Your real GitHub profile URL |
| All pages, footer | `your-email@example.com` | Your contact email |
| `index.html` | `resume/Hatim-Mohammed-Resume.pdf` | Add your actual resume PDF to the `resume/` folder with this filename (or update the link) |
| `index.html` | "View Projects" button (currently points to `skills.html`) | Point to a live projects page or your GitHub repositories once you have specific projects to showcase |

## Deploy on GitHub Pages

1. Create a new repository on GitHub, e.g. `hatim-portfolio`.
2. Upload all the files in this folder (keeping the same structure) to the repository — either via the GitHub web UI ("Add file → Upload files") or with git:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/your-github-handle/hatim-portfolio.git
   git push -u origin main
   ```
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. After a minute, your site will be live at:
   `https://your-github-handle.github.io/hatim-portfolio/`

## Notes on the design

- Color palette: deep violet / white with a "terminal" motif (network status dot, mono-spaced prompts, IP-style labels) to reflect the IT Support / Networking / Cybersecurity focus.
- Fonts: Space Grotesk (headings), Inter (body text), JetBrains Mono (technical accents) — loaded from Google Fonts.
- Fully responsive with a mobile navigation menu; motion is minimal and respects `prefers-reduced-motion`.
- No build tools required — it's plain HTML/CSS/JS, so it works directly with GitHub Pages.
