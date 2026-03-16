# LoreGlass — Coming Soon Page

> Conceived & Directed by **Grey Hammond**

This repository hosts the official **LoreGlass** coming soon landing page, served via GitHub Pages.

---

## What is LoreGlass?

LoreGlass is a narrative RPG engine built in Godot 4. It combines handcrafted prose storytelling with a full RPG system — equipment slots, feats, dynamic economies, quest tracking, and cross-book travel — all driven by plain JSON that authors write without touching a line of code.

**Coming to:** PC · Mac · Android · HTML5 / Web

---

## This Repository

| File | Purpose |
|---|---|
| `index.html` | The coming soon landing page |
| `README.md` | This file |

> **Note:** Rename `loreglass_site.html` to `index.html` before pushing — GitHub Pages serves `index.html` as the root.

---

## Deployment

This site is a single self-contained HTML file with no dependencies, no build step, and no framework. Everything — fonts (via Google Fonts CDN), styles, and scripts — is inline or loaded from CDN.

**To deploy:**

```bash
git add index.html README.md
git commit -m "v0.95.8 checkpoint — coming soon page"
git push origin main
```

GitHub Pages will serve the page at:
```
https://<your-username>.github.io/<repo-name>/
```

If you're using a custom domain, add a `CNAME` file to the repository root containing your domain name.

---

## Engine Status

Current version: **v0.95.8**

The engine is in active development. The source code is not public at this time.

---

## Credits

| Role | Name |
|---|---|
| Concept & Project Direction | Grey Hammond |
| Engine | Built with Godot 4 |

---

*© 2025 Grey Hammond. All rights reserved.*
