# Sushil Raj · Portfolio

My personal site. The page floats on a live ink simulation (WebGL2 stable fluids) that follows the cursor or finger, and the type around it inverts where the ink passes.

## What's in it

- **Ink:** four inks (墨 sumi, 藍 indigo, 緋 ember, 極光 aurora), a calm-to-storm slider, film grain, and scrolling that stirs the ink up
- **Light and dark:** pigment that absorbs light on paper, ink that glows in the dark
- **Phones:** their own layout, with a vertical name, a swipe carousel, a full-screen menu and an ink sheet
- **English and 日本語:** Japanese browsers get Japanese automatically; a button switches either way
- **Sections:** six projects, an about section, where my interest in Japan comes from, and contact

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
