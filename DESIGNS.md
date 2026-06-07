# Portfolio Redesigns

Ten complete, independent redesigns of `index.html`. Each lives on its own branch and starts from the same baseline content — all projects, links, skills, resume URL, and contacts preserved.

To preview any design:

```
git checkout redesign-XX-name
# then open index.html in a browser, or run a local server:
npx serve .
# or:
python -m http.server 3000
```

---

## Design Index

| # | Branch | Style | Pitch |
|---|--------|-------|-------|
| 01 | `redesign-01-terminal` | Terminal / CLI emulator | Pitch-black JetBrains Mono shell with boot sequence, live clock, and CRT phosphor scanlines |
| 02 | `redesign-02-swiss` | Swiss International Typographic | Pure white + crimson grid, vertical section numbers, strict two-column rule-based layout |
| 03 | `redesign-03-brutalist` | Neo-brutalist | Cream bg, Bebas Neue headlines, thick ink borders, hard box-shadows that vanish on hover |
| 04 | `redesign-04-glassmorphic` | Glassmorphism / aurora | Deep purple with animated gradient orbs, frosted-glass cards, and gradient text |
| 05 | `redesign-05-retro-amber` | Retro amber CRT | Amber-on-black Courier Prime terminal with HTML project table, ASCII dividers, and CRT vignette |
| 06 | `redesign-06-editorial` | Editorial magazine | Newspaper masthead, Playfair Display serif, asymmetric 3-column project layout with pull quote |
| 07 | `redesign-07-minimal` | Extreme minimalist | Pure white, Inter weight-300, 720 px column, zero decoration — the content is the design |
| 08 | `redesign-08-luxury` | Dark luxury / haute couture | Near-black with Cormorant Garamond italic, gold accents, roman numerals, fractal texture overlay |
| 09 | `redesign-09-cyberpunk` | Cyberpunk neon HUD | Dark navy with cyan/pink/yellow neons, HUD corner brackets, clip-path buttons, fixed status bar |
| 10 | `redesign-10-academic` | Academic paper / arXiv | EB Garamond preprint with title block, abstract, numbered sections, figures, skill table, reference list |

---

## Quick checkout reference

```bash
git checkout redesign-01-terminal
git checkout redesign-02-swiss
git checkout redesign-03-brutalist
git checkout redesign-04-glassmorphic
git checkout redesign-05-retro-amber
git checkout redesign-06-editorial
git checkout redesign-07-minimal
git checkout redesign-08-luxury
git checkout redesign-09-cyberpunk
git checkout redesign-10-academic
```

## Screenshots

Automated screenshots were not captured (Playwright is not installed in this environment). To capture them manually: open each branch in a browser and use DevTools device emulation for mobile (375 px) alongside the default desktop view.

---

*Baseline (original design): `main` branch.*
