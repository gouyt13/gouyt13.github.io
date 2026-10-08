# Yutong Gou — personal homepage

A dependency-free academic homepage built for GitHub Pages.

The design brief used to create the site is recorded in `PROMPT.md`.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repository is configured as the user site `gouyt13.github.io`. GitHub
Pages publishes the static files directly from the root of the `main` branch.

The site is available at `https://gouyt13.github.io/` after GitHub finishes a
deployment.

## Customize

- Biography, publications, and links are in `index.html`.
- Colors, typography, and layout are in `styles.css`.
- The homepage does not require JavaScript or a build step.
- The homepage uses the public GitHub avatar endpoint at
  `https://github.com/gouyt13.png`, so it follows future GitHub avatar changes
  automatically.
