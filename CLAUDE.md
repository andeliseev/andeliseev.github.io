# andeliseev.github.io

The public website, served by GitHub Pages from `main` as it is. What's here and how it's published: [README.md](README.md).

## Working rules

- Plain HTML and CSS: no framework, build step or script libraries. Keep `.nojekyll`.
- Every page has light and dark styles (`prefers-color-scheme`) and works at phone width.
- Each app has its own folder (`unified-mail/`, `torrstream-lite/`) with `index.html`, `privacy.html`, `support.html`, `style.css` and `favicon.svg`. Don't move or rename pages: the apps, their READMEs, GitHub's Sponsor buttons and Google's OAuth settings link to them.
- Keep `google6ae5c2a97f179509.html` at the root, unchanged (Google Search Console verification).
- A privacy policy describes what its app really does. When it changes, update its effective date. The apps' repositories say when to come here: when what an app accesses or keeps changes, when its icon changes (`favicon.svg`), and for TorrStream Lite when its UI changes (its screenshots are rendered in its repo with `scripts/screenshots/make.py` and copied here).
- Both support pages list the same payment options; change them together.
- Commit messages are public and are the site's history: write them for people, starting with the app (`Unified Mail: …`, `TorrStream Lite: …`).
- Commits are authored as `Andrei Eliseev <andeliseev@gmail.com>` (set in this repository's git config). Never add `Co-Authored-By` lines or any other Claude/AI attribution.
- Publishing is pushing `main`. Check changed pages in a browser first, in light and dark.
