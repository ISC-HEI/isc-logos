<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="./white/ISC%20Logo%20inline%20white%20v3%20-%20large.webp">
  <img align="right" height="50" alt="ISC Logo"
       src="./black/ISC%20Logo%20inline%20black%20v3%20-%20large.webp"/>
</picture>

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

# ISC Logos

The official logos of the [ISC bachelor degree programme](https://isc.hevs.ch) at the HES-SO Valais School of Engineering in Sion — inline wordmark, symbol-only petals and even an ANSI rendition for your terminal. This repository is the canonical source for the ISC visual identity: other ISC repositories reference these files directly rather than keeping local copies.


## Preview

| Inline logo | Symbol only |
|:---:|:---:|
| <picture><source media="(prefers-color-scheme: dark)" srcset="./white/ISC%20Logo%20inline%20white%20v3%20-%20large.webp"><img src="./black/ISC%20Logo%20inline%20black%20v3%20-%20large.webp" width="400" alt="ISC inline logo preview"></picture> | <img src="./symbol%20only/ISC_logo_rvb.svg" width="120" alt="ISC petals symbol preview"> |

The inline logo above switches automatically with your GitHub colour scheme; both black (light surfaces) and white (dark surfaces) variants are provided.

## Brand colours

The five petals of the symbol correspond to the five ISC majors. Use these exact values in any official material:

| Major | Swatch | Hex | RGB |
|---|:---:|---|---|
| Systèmes informatiques embarqués | ![#98C7BF](https://placehold.co/15x15/98C7BF/98C7BF.png) | `#98C7BF` | 152, 199, 191 |
| Sécurité informatique | ![#E2ABBA](https://placehold.co/15x15/E2ABBA/E2ABBA.png) | `#E2ABBA` | 226, 171, 186 |
| Réseaux et systèmes | ![#A890C0](https://placehold.co/15x15/A890C0/A890C0.png) | `#A890C0` | 168, 144, 192 |
| Informatique logicielle | ![#8CC6E6](https://placehold.co/15x15/8CC6E6/8CC6E6.png) | `#8CC6E6` | 140, 198, 230 |
| Ingénierie des données | ![#F7F19F](https://placehold.co/15x15/F7F19F/F7F19F.png) | `#F7F19F` | 247, 241, 159 |

## Repository contents

| Directory | Contents | Formats |
|---|---|---|
| `./black/` | Inline logo, black version (for light backgrounds) | SVG, PDF, WEBP, PNG (50/96/150/1500 px) |
| `./white/` | Inline logo, white version (for dark backgrounds) | SVG, PDF, WEBP, PNG (150/600/1500 px) |
| `./symbol only/` | The five-petal symbol alone, without text | SVG, PDF |
| `./archive/` | Previous logo generations (v1), kept for reference | SVG, PNG |

Prefer the SVG or PDF originals for print and the WEBP/PNG exports for the web; pick the PNG size closest to your target to avoid resampling artefacts.

## Using the logos in your project

Don't copy the files into your repository — hot-link the raw URLs so every project stays current when the logos are updated. The standard theme-aware header used across ISC repositories:

```html
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/ISC-HEI/isc-logos/main/white/ISC%20Logo%20inline%20white%20v3%20-%20large.webp">
  <img align="right" height="50" alt="ISC Logo"
       src="https://raw.githubusercontent.com/ISC-HEI/isc-logos/main/black/ISC%20Logo%20inline%20black%20v3%20-%20large.webp"/>
</picture>
```

The `%20` escapes in the file names are required — copy the snippet as-is.

## ANSI logo

Because every serious institution needs a terminal-ready logo (thanks Mr. Siedel):

```bash
# Display the ISC logo in your terminal
curl -sL "https://raw.githubusercontent.com/ISC-HEI/isc-logos/main/isc-logo.ans" | cat
```

---

## License

Copyright © 2026 P.-A. Mudry / ISC — HES-SO Valais. The logos are licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/): you may share them with attribution for non-commercial purposes, but modified versions may not be redistributed.

---

*Made with ♥ by mui, 2026*
