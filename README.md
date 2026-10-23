# Modern Warfare: After the Shot

A small, responsive scrollytelling site recapping the story connection between *Call of Duty: Modern Warfare III* and *Call of Duty: Modern Warfare 4*.

> Fan-made project for storytelling and learning. Not affiliated with or endorsed by Activision, Xbox, or Call of Duty.

## Files

```text
index.html       Page content and structure
styles.css       Layout, colors, and animations
script.js        Scroll progress, chapter indicators, and reveal effects
assets/          Campaign images used by the page
```

## Preview locally

Keep the files together, then open `index.html` in a browser. The styles, scripts, and images use relative paths, so the site works from the folder and does not require a build step.

## Publish with GitHub Pages

1. Create a GitHub repository and upload `index.html`, `styles.css`, `script.js`, and the `assets/` folder to the repository root.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch containing the site (usually `main`) and the `/(root)` folder, then save.
5. GitHub will show the published site link in the Pages settings when deployment finishes.

See GitHub's [Pages publishing-source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) for details.

## Image credits

- `assets/mw4-reveal.jpg` — Modern Warfare 4 campaign image hosted by Battle.net.
- `assets/mw4-korea.jpg` — Modern Warfare 4 campaign image hosted by Xbox Wire.

The images are bundled locally so the page does not depend on remote image links. Their respective owners retain all rights.
