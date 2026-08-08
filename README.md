# Operations Lab — V1.3.3

Definitive Hero image correction.

The previous implementation used a CSS background with `cover`, which cropped the supplied hero asset because the asset itself is portrait/composite.

This version:
- uses the hero asset as a real `<img>`;
- preserves the original aspect ratio;
- removes `background-size: cover`;
- prevents the image from being cropped on mobile;
- keeps the previously approved editorial DA and content.
