# शुभ नवरात्रि · Nav Durga

An interactive Navratri web experience built with plain HTML, CSS and JavaScript. One file, no frameworks, no build step.

## Features

- **Animated hero** with a red splash, rotating mandala, falling marigold petals and a live countdown
- **Nav Durga** – swipe through the 9 forms of Maa Durga, each with an illustration, mantra, description and its own theme colour
- **Light a Diya** – tap 9 diyas, with a petal burst when all are lit
- **Dandiya Beat** – a 30-second rhythm game with combo scoring, sound and a saved high score
- **Wishes card maker** – enter a name, then download or share a 4:5 card
- Scroll-reveal animations, mobile-first layout and reduced-motion support

## Run it

Open `index.html` in any modern browser. No install needed.

To host it, upload the file to GitHub Pages, Netlify, Vercel or any static host.

## Customise

| What | Where in `index.html` |
| --- | --- |
| Festival start date | `START` constant in the script |
| Roop names, mantras, colours | `R` array |
| Vahan labels | `V` array |
| Watermark handle | `.wm` link, footer link and `draw()` function |
| Game speed and difficulty | `gl()` function (`RR`, spawn timer, speed formula) |

## Tech

HTML5 · CSS3 (custom properties, animations) · Vanilla JavaScript · Canvas API · Web Audio API · Web Share API · SVG

Fonts: Tiro Devanagari Hindi, Yatra One and Cinzel (Google Fonts).

## Credits

Designed and built by [@storymint.studio](https://instagram.com/storymint.studio)

॥ जय माता दी ॥
