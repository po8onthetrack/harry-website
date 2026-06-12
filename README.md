# Harry Zhang — Personal Portfolio

A fast, responsive, single-page portfolio built with plain HTML, CSS, and
JavaScript — no build step required.

## Files

| File | What it is |
|------|-----------|
| `index.html` | All page content (text, sections, links) |
| `styles.css` | Styling and the light/dark theme |
| `script.js` | Theme toggle, mobile menu, scroll animations |
| `Harry_Zhang_resume.pdf` | Résumé served for download |

## Editing

Open `index.html` and change the text directly — it's plain HTML.
Common edits:

- **GitHub link:** search for `yourusername` and replace it with your real
  GitHub username (appears in the hero, both project cards, and the footer).
- **Projects:** duplicate a `<article class="card">…</article>` block to add one.
- **Colors:** edit `--accent` near the top of `styles.css`.

## Preview locally

Just double-click `index.html`, or run a tiny local server:

```bash
cd ~/profolio
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy (GitHub Pages)

1. Create a repository on GitHub named **`po8onthetrack.github.io`**.
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/po8onthetrack/po8onthetrack.github.io.git
   git push -u origin main
   ```
3. Your site goes live at **`https://po8onthetrack.github.io`** within a minute.

To update the site later, just edit a file and:
```bash
git add . && git commit -m "Update" && git push
```
