HIMANSHU — CINEMATIC PORTFOLIO

Structure
  index.html            the whole site (one page)
  assets/video/*.mp4    web-compressed films (720p, ~50 MB total)
  assets/poster/*.jpg   poster frames for each film
  assets/img/w01–w45    design + AI stills, portrait.webp

Viewing
  Videos need a web server (double-clicking index.html may block them in some browsers).
  Easiest: upload the whole "site" folder to Netlify Drop, Vercel or GitHub Pages.
  Needs internet for fonts + GSAP/Lenis (loaded from CDN).

Editing content
  - Edit-reel cards: the EDITS list near the top of the <script> (file id, title, brand, tag).
  - Design gallery per brand: DESIGN lists (image numbers). Design wall: WALL.
  - AI chapter: the five .ai-step blocks + the videos inside #aiFrame (same order).
  - Numbers row: data-count values.
