# rayvadams.com

Personal site of Ray V. Adams. Plain static HTML and CSS: no build step, no framework.

```
index.html      About, publications, talks
research.html   The thermal lens, in pictures (animations from the 2026 RTG talk)
contact.html    Email, phone, addresses
assets/         style.css, eclipse avatar, favicons, media/ (MP4 animations and posters)
```

## Deploying on Cloudflare Pages

Connect this repository in Cloudflare Pages with:

- Framework preset: **None**
- Build command: *(leave empty)*
- Build output directory: **/**

Every push to `main` redeploys the site. Then add `rayvadams.com` (and `www`) under the project's **Custom domains**.

## Editing

Text lives directly in the HTML files. The animations are short silent MP4s that autoplay and loop (they
pause and show controls for visitors who prefer reduced motion). To preview locally, open `index.html` in a browser.
