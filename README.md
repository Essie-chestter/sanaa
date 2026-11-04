# SANAA

**A continent of creativity. An infinite canvas.**

SANAA (Swahili for *art*) is a digital platform and creative marketplace that showcases, connects and promotes African creative talent. This repository holds the SANAA landing page and brand assets.

## The landing page

A single responsive page (`index.html`) built with plain HTML, CSS and JavaScript. No build step and no dependencies apart from Google Fonts.

| # | Section | What it does |
|---|---|---|
| 01 | Navigation | Logo, Explore creatives, Discover work, Opportunities, About, Join SANAA. Compact menu on phones. |
| 02 | Hero | Oversized headline, collage of creative work, two calls to action. |
| 03 | The Creative Wall | Signature section: 22 works told as a story in four chapters, with discipline filters, hover captions and a project preview. |
| 04 | Meet the Creatives | Profile cards (swipeable on phones). |
| 05 | Explore Creative Disciplines | Eight colourful cards that filter the wall. |
| 06 | What You Can Do on SANAA | Showcase, Discover, Connect, Grow, each with a small animation. |
| 07 | Two sides of the community | For creatives / for businesses and clients. |
| 08 | The SANAA story | The mission: closing the gap between talent, visibility and opportunity. |
| 09 | Final call to action | "Your creativity deserves a bigger canvas." |
| 10 | Footer | Links, socials, legal, closing brand line. |

### Built for every screen
- Desktop, laptop, tablet and phone layouts (breakpoints at 1200, 1100, 900 and 600 px).
- Keyboard accessible: real buttons and links, visible focus rings, Escape closes the preview and menu.
- Descriptive alt text, readable contrast, and animations switch off for `prefers-reduced-motion`.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site appears at `https://<your-username>.github.io/sanaa/` after a minute or two.

## Structure

```
index.html          the landing page
img/                images used by the page
brand/logo/         logo, mark, app icon, avatar and favicons (SVG + PNG)
docs/brief.md       concept, audiences, structure and UX principles
```

## Brand

- **Logo:** four tilted tiles (the Creative Wall) beside the *sanaa* wordmark, underlined with a tangerine brushstroke.
- **Colours:** cream `#FDF2E0`, ink `#111111`, lime `#D5F244`, tangerine `#FF6A13`, lilac `#A982F5`, sun `#FFD54A`.
- **Type:** Archivo (condensed, 900) for headlines, Fraunces for section headings, Inter for body text, Permanent Marker for brush moments.

## Image credits

The artwork and photography on the page are used for demonstration. Creator names and project titles are placeholders. Replace them with credited work from real creatives, with their permission, before any public launch.

## Author

Esther Maina · [GitHub](https://github.com/Essie-chestter) · [LinkedIn](https://linkedin.com/in/esther-maina-w)
