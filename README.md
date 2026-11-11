# brill-ar-mindar-test

Standalone one-artwork experiment comparing the open-source **MindAR** image
tracking engine against the 8th Wall engine currently used in
[Brill-AR](https://github.com/Adibrill1/Brill-AR). This is a separate test
page: nothing here changes Brill-AR, its published sites, or anyone's work on it.

**Live test page:** https://adibrill-instinct.github.io/brill-ar-mindar-test/

## What it does

Opens the phone camera (Safari on iPhone), recognizes the demo artwork
(`target-artwork.jpg`, the same `studio/assets/demo/artwork.jpg` already
public in Brill-AR), and pins the demo video on top of it so it stays glued
while the phone moves.

## How to test

1. Open the live page on the iPhone **in Safari** (not inside WhatsApp) and
   allow camera access.
2. Point it at `target-artwork.jpg` on another screen or a printout.
3. Compare with the existing Brill-AR player: recognition speed, tracking
   stability while moving, behavior at angles and in different lighting.
4. Sound needs one tap (iPhone blocks autoplay with sound) - tap the
   "הקישי להפעלת צליל" button.

## Files

- `index.html` - the whole experiment (MindAR + A-Frame from CDN)
- `targets.mind` - compiled image target for the demo artwork
- `target-artwork.jpg` - the image to point the camera at
- `5-art-video.mp4` - the demo video (name kept as uploaded; referenced from index.html)

## Credits and licenses

- [MindAR](https://github.com/hiukim/mind-ar-js) v1.2.5, MIT license, (c) hiukim 2020
- [A-Frame](https://aframe.io) v1.4.2, MIT license
- Artwork/video assets are already public in
  [Brill-AR](https://github.com/Adibrill1/Brill-AR) (`studio/assets/demo/`).
  No 8th Wall code, keys or services are used on this page.
