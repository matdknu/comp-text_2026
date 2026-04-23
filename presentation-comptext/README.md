# Presentation Folder Schema

This folder contains the COMPTEXT presentation copied from the original project and cleaned to keep only assets that are currently referenced.

## Structure

- `presentation.qmd`: main Quarto source file (edit this first).
- `presentation.html`: rendered slide deck.
- `custom.scss`: RevealJS theme customization.
- `comptext-theme.css`: custom slide classes and visual components.
- `deck-logos.html`: header snippet for conference logos.
- `image/`: figures used in slides and theme backgrounds.
- `images/`: additional figures, gifs, and logos used in slides.
- `tables/`: CSV tables rendered inside slides.
- `presentation_files/`: Quarto/RevealJS runtime dependencies generated with the HTML output.

## Keep / update workflow

1. Update content in `presentation.qmd`.
2. Keep image assets in `image/` or `images/` and reference them explicitly in `presentation.qmd` or theme files.
3. Re-render with Quarto when needed so `presentation.html` and `presentation_files/` stay in sync.

