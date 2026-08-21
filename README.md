# PhotoStrip

A browser-based photostrip design and printing tool, built to replace paid software like dslrBooth for the *design* side of a photobooth setup. Guests still had their photos taken with dslrBooth, but PhotoStrip handled the layout, theming, and print-ready export, custom to the event.

What started as a one-off build for a school event (CHMSU U-Week) turned into a small business, running photobooth setups with fully custom, on-brand strips instead of generic templates.

## What it does

- Upload photos directly into a strip layout in the browser
- Switch between multiple print formats: 2-strip/3-photo, 4-pose 4R, single-strip variants, sized to real print dimensions (B5, B6, 6x4)
- Pick from several visual themes (Default, Ribbon, Airmail, Polaroid, and a Spotify-player-styled strip) or customize text like song title/artist directly on the strip
- Export the finished strip as a print-ready PDF, rendered client-side with html2canvas and jsPDF, no server or backend needed

## Tech stack

- HTML, CSS, vanilla JavaScript
- [html2canvas](https://html2canvas.hertzen.com/) for rendering the strip to canvas
- [jsPDF](https://github.com/parallax/jsPDF) for generating the print-ready PDF

## Running locally

No build step or server required. Clone the repo and open `index.html` in a browser, or serve it with any static file server.

## Background

Built originally as a lightweight, no-install alternative to commercial booth software for a school event. The photo capture still runs through dslrBooth, but PhotoStrip owns everything after that: layout, theme, branding, and the final print file.