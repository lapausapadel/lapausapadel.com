# La Pausa ‚Äî Website

Static one-page site for La Pausa padel retreats. Plain HTML/CSS/JS ‚Äî no build step.

## Files
```
index.html                      The whole site
assets/hero-palms-ocean-wide.png  Hero background photo
assets/hector-perona.png          Coach portrait
fonts/Benniter.ttf                Brand display font (TRIAL license ‚Äî license before commercial use)
.nojekyll                         Tells GitHub Pages to serve files as-is
```
Keep this folder structure intact ‚Äî `index.html` references `assets/` and `fonts/` by relative path.

## Deploy with GitHub Pages
1. Create a new repository on GitHub (e.g. `lapausa-site`).
2. Upload the **contents of this folder** to the repo root (drag-and-drop on github.com ‚Üí "uploading an existing file", or push with git).
3. In the repo: **Settings ‚Üí Pages**.
4. Under **Build and deployment ‚Üí Source**, choose **Deploy from a branch**.
5. Set branch to `main` and folder to `/ (root)`, then **Save**.
6. Wait ~1 minute. Your site appears at `https://<your-username>.github.io/<repo-name>/`.

### Custom domain (optional)
- In **Settings ‚Üí Pages ‚Üí Custom domain**, enter `lapausapadel.com`.
- At your domain registrar, add the DNS records GitHub shows you (an `A`/`ALIAS` or `CNAME`). Allow up to an hour to propagate.

## Notes
- The "Apply now" buttons open the Tally form: https://tally.so/r/A7jjOl
- Fonts (Hanken Grotesk, Newsreader) and icons (Lucide) load from public CDNs, so the site needs an internet connection to render exactly as designed.
- Contact email: contact@lapausapadel.com


