# cojovo

A personal outbound link portfolio and link-in-bio site with a retro terminal aesthetic 💜 💜 💜 

This site deliberately avoids using CMS or a static site generator. It's pure HTML and CSS. No dependencies, no problem. 

This is a scrapbook, not a blog. [Use Ghost](https://ghost.org/) if you need that. 

## Structure

```
├── index.html          # Main portfolio link page 
├── links.html          # Link-in-bio page 
├── README.md           # This file
└── .gitignore          # Git ignore 
```

## Design

- **Color scheme**: Purple💜 retro terminal aesthetic
- **Typography**: Berkeley Mono + IBM Plex Mono
- **Effects**: Static CRT scanlines, phosphor glow, minimal animations
- **Layout**: 
  - `index.html`: Left aligned, terminal inspired
  - `links.html`: Centered, card based, mobile first

### Color Palette

```css
--purple-dark: #1a0d2e      /* Background */
--purple-medium: #2d1b4e    /* Borders, secondary elements */
--purple-accent: #7b4fb8    /* Accent elements, prompts */
--purple-light: #b794f6     /* Headers, highlights */
--purple-bright: #d4b3ff    /* Brightest elements, cursor */
--text-primary: #e8dff5     /* Primary text */
--text-secondary: #b8a3d9   /* Secondary text */
--text-dim: #7b6b8f         /* Dimmed text, metadata */
```

## Deployment

Deploy anywhere that serves static HTML:
- GitHub Pages
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any basic web server

Just serve the files.

## Maintenance

To update content, edit the HTML directly:
- Update project links in the `<section>` elements
- Modify social links in the Connect section
- Change personal info in the header

The color scheme is defined in CSS variables at the top of each file for easy theming.

## License

MIT License

Copyright (c) 2026 Courtney Johnston von Nieda

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.