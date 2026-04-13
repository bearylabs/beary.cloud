# beary.cloud

Tailwind CSS site. Minimal, optimized build.

## npm Commands

| Command | Purpose |
|---------|---------|
| `npm install` | Install dependencies |
| `npm run build` | Compile & minify CSS to dist/ |
| `npm run watch` | Watch src/input.css, rebuild on change |

## Quick Start

```bash
npm install
npm run build          # One-time build
# or
npm run watch         # Development mode
```

## Structure

- `src/input.css` - Source Tailwind config + custom utilities
- `dist/output.css` - Built (minified)
- `assets/` - Logo, fonts (Fira Code latin 400/600/700)
- `index.html` - Single landing page
- `.github/workflows/deploy.yml` - Auto-deploy to GitHub Pages

