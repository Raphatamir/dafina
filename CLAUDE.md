# Dafina Seaside Grill website

A single static landing page for Dafina Seaside Grill, 213–215 Barkly Street, St Kilda 3182, opening 2027. Hosted on GitHub Pages at dafina.com.au; anything merged into `main` goes live within a minute or two.

## Files
- `index.html`: the whole page, with styles inline in `<style>`. No build step, no framework.
- `dafina-logo.svg`: Ellie's handwritten "dafina seaside grill" logo, traced from her pencil sketch. Fill #00187A.
- `tangia.svg`: Ellie's hand-drawn tangia pot. Fill #A07C3A. Also used as the favicon.
- `CNAME`: must contain `dafina.com.au`. Do not delete or rename it, or the custom domain stops working.

## Look and feel
- Inspired by a 1928 printed restaurant menu: aged cream paper, everything printed in one ink colour, centred, sparse.
- Colours: paper `#F7EBCB`, ink ultramarine `#00187A`, ochre `#A07C3A` (tangia only), link hover `#A0522D`.
- Type: IM Fell English (mostly italic) for text; IM Fell English SC (small caps) for labels.
- Short 64px centred rules between sections; a longer 140px rule above the closing "Opening 2027" line.
- Labels and values are joined with a comma, not a dash (e.g. "Get in touch, hello@dafina.com.au").
- The owners have rejected: a blue page background, wavy/parapet line motifs, and "Coming soon" / "Summer 2027" wording.

## Content
- Email for everything: hello@dafina.com.au (the "Join the team" link pre-fills the subject "Joining the team").
- Instagram: https://www.instagram.com/dafina.seaside/

## Rules
- Keep it one self-contained page that works at phone width (rows stack under 640px).
- Test by opening `index.html` in a browser; there is nothing to build.
