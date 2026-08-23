# [toddchapman.io](https://toddchapman.io)

Personal website for Todd Chapman. Pure static HTML hosted on GitHub Pages at [toddchapman.io](https://toddchapman.io).

## Design

The layout follows the [Monospace Web](https://owickstrom.github.io/the-monospace-web/) pattern: semantic HTML, a bordered header table, square-bullet navigation, and monospace grid typography. Styling is adapted from [Oskar Wickström's Monospace Web](https://github.com/owickstrom/the-monospace-web) (MIT License) with a matrix green-on-black palette.

- **Font:** JetBrains Mono (CDN)
- **Colors:** `#00ff33` on `#000`, muted accents at `#046e27`
- **Stack:** Hand-written HTML and a single shared [`style.css`](style.css) — no build step, no JavaScript

Original site concept borrowed from [John Graham-Cumming](https://www.jgc.org).

## Pages

| Path | Description |
|---|---|
| [`/`](index.html) | Home — links to projects, CV, social profiles, and subpages |
| [`/writings/`](writings/index.html) | Essays and technical writing |
| [`/load-bearing-links/`](load-bearing-links/index.html) | Curated links to interesting old content on the internet |
| [`/CV/`](CV/index.html) | CV viewer (embeds [`CV/CV.pdf`](CV/CV.pdf)) |

## Local preview

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## License

MIT — see [LICENSE](LICENSE).
