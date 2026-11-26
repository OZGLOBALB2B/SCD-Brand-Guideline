# SCD — Brand Guidelines

Static brand-guidelines site (single `index.html`, no build step) with side navigation.

**Sources**
- Brand assets: SCD logo, regional logos, values, shapes and display alphabet (`downloads/source-ai`)
- Colors: SCD Brandbook v4
- Imagery: `Imagery/` (13 approved images, one gallery, no segments)
- UI, typography, IR spectrum and value cards: Figma "SCD-Website-UI" (`qQN2yPcu2UAOIms0iFzTSO`)

**Structure**
```
index.html                 the site
Imagery/                   gallery images (SCD_Imagery_01–13.jpg)
downloads/
  Logos/ Regional/ Values/ Type/   SVG + PNG (2400 px, transparent)
  Shapes/<shape>/                  SVG in all 12 brand colors
  colors/                          scd-palette.json, scd-tokens.css
  source-ai/                       original Illustrator files
  SCD_Brand-Assets.zip             everything above except source-ai
```

**Notes**
- Avenir Next is a licensed font; the site previews it with Nunito Sans where it isn't installed.
- Negative value lockups (`*_Negative.svg`) use live text in Avenir Next; use the PNG where the font isn't installed.

**Deploy**
Import this repo into Vercel as a static project (Framework: Other, no build command, output = root).
