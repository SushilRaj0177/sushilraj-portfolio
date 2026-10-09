# Sushil Raj · Portfolio

My personal site. The page floats on a live ink simulation (WebGL2 stable fluids) that follows the cursor or finger, and the type around it inverts where the ink passes.

## What's in it

- **Ink:** five inks (墨 sumi, 藍 indigo, 緋 ember, 極光 aurora, 画素 pixels), a calm-to-storm slider and optional film grain. Pixels draws the ink as pixel art in the colours of the season, changing season every 28 seconds, with small sparkles twinkling where the ink is thick. The ink follows the cursor or a finger, a click or tap drops more, and scrolling stirs it up. Ink stirred up by scrolling fades in over a moment instead of appearing all at once, so it doesn't flicker
- **Light and dark:** it starts in light mode, where the ink is pigment on paper; in dark mode it glows
- **Phones:** their own layout, with a vertical name, a swipe carousel, a full-screen menu and an ink sheet. A finger that's scrolling leaves no trail (the scroll stirs the ink instead). On the ink at the top, a stroke that starts sideways, or a press and hold, keeps the page still so the finger can paint, whirls included
- **English and 日本語:** Japanese browsers get Japanese automatically; a button switches either way
- **Japan:** a section on where my interest in Japan comes from. It started with stories (anime, manga and films), music, and the older stories: mythology, Shinto and folklore. What keeps me here is the language, the modern cityscapes and natural landscapes, and the way of life and the ideas underneath it. Each one has its kanji, brushed in from the top as it scrolls into view. I haven't been yet; I'm working towards an opportunity to study at Waseda, which would be my first time there
- **Sections:** six projects, about, Japan, and contact, signed off with a name seal (判子) reading スシル
- **Scrolling:** besides stirring the ink, the name sinks back as you leave the top, headings rise into place, and the skill columns fade up

## Run it

It's a single static page with no build step. Open `index.html`, or serve the folder:

```
python3 -m http.server 8000
```

GSAP, ScrollTrigger and Lenis load from CDNs, and the fonts from Google Fonts.

## Layout

```
index.html     the site
img/           project screenshots
original/      the first version of the site
```
