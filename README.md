# Operations Lab — V1.5

Refinement of the mobile-first editorial direction.

## Main changes
- Stronger editorial hierarchy.
- Less information density on the first screen.
- Clear separation between Statement / Idea / Industry / Explore / About.
- More breathing room between sections.
- Operations × Industry becomes a central signature.
- Hero image uses a stable `object-fit: cover` container to avoid the previous crop/layout issue.

## Image
Put the existing hero image in:

`assets/operations-hero.jpg`

The filename is intentionally isolated so the image can be swapped without touching the layout code.

## Deploy
Upload/replace `index.html`, `styles.css`, `script.js` and the `assets` folder in the GitHub repository. Vercel will redeploy automatically.
