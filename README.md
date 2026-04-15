# Brand Assets

This repository is the single source of truth for all brand and design system assets. Assets are served publicly via **GitHub Pages** at:

**https://abruno-dh.github.io/brand-assets/**

---

## Folder Structure

```
brand-assets/
├── logos/        # SVG and PNG logo files
├── icons/        # Icon set (SVG preferred)
├── fonts/        # Web font files (.woff2, .woff)
├── images/       # Photography, illustrations, and other imagery
├── css/
│   ├── tokens.css   # Design tokens (colors, spacing, typography)
│   └── global.css   # Global brand styles (imports tokens.css)
└── webflow/      # Webflow-specific exports and snippets
```

---

## Usage

Reference assets directly from the GitHub Pages URL so any project always gets the latest version without copying files.

**CSS**
```html
<link rel="stylesheet" href="https://abruno-dh.github.io/brand-assets/css/global.css">
```

**Logos / Images**
```html
<img src="https://abruno-dh.github.io/brand-assets/logos/logo.svg" alt="Brand logo">
```

**Fonts** — declare `@font-face` rules in `css/tokens.css` pointing to files in `fonts/`.

---

## Contributing

1. Add assets to the appropriate folder.
2. Update `index.html` to list new assets.
3. Commit and push to `main` — GitHub Pages deploys automatically.
