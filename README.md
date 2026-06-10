# UFC VIP Experience — landing page (header + fights carousel)

Static site. No build step. Just HTML, CSS, an SVG/MP4, and a couple of JPGs.

## Files
```
index.html            ← the page
assets/
  headline.svg        ← "UFC VIP EXPERIENCE" lockup
  nav-logo.svg        ← UFC + On Location nav logo
  hero.mp4            ← hero background video (right side)
  fight-1.jpg         ← Horiguchi vs Kape poster (card 1)
  fight-2.jpg         ← McGregor vs Holloway 2 poster (card 2)
```
Cards 3–5 use a gradient placeholder until you add `assets/fight-3.jpg`,
`fight-4.jpg`, `fight-5.jpg`. Drop them in with those names and they appear
automatically. Same for an optional `assets/hero-poster.jpg` (first frame
shown while the video loads).

Fonts (Inter + Saira Condensed) load from the Google Fonts CDN, so nothing
font-related needs to be hosted.

## Put it on GitHub Pages
1. Upload the **contents of this folder** (index.html + the assets folder)
   to the root of your repo — e.g. drag them into the repo's "Add file →
   Upload files" page, or commit them with git.
2. In the repo: **Settings → Pages**.
3. Under "Build and deployment", set **Source: Deploy from a branch**,
   **Branch: main**, folder **/ (root)**, then **Save**.
4. Wait ~1 minute, then open the URL GitHub shows
   (e.g. `https://<user>.github.io/<repo>/`).

Keep `index.html` at the repo root so the Pages URL loads it directly.
