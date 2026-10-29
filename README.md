# Arnab & Moumi — wedding reception invitation

Plain HTML/CSS/JS. No build step. Works on GitHub Pages as-is.

## Put it online
1. Create a new **public** repository named `moumi-arnab-reception`.
   (Its address will be https://podderarnab3.github.io/moumi-arnab-reception/ — if you pick another name,
   open index.html and replace `moumi-arnab-reception` in the two og: lines near the top.)
2. Add file → Upload files → drag in everything inside this folder (not the folder itself) → Commit changes.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save. Live in 1–2 minutes.

## Change the song or photo later
- Song: upload a new file named exactly `music.mp3` into the `audio` folder (same name replaces the old one).
- Photo: upload a new `couple.jpg` into the `images` folder (same name replaces it). Portrait 3:4 works best.
- Reception time: js/main.js → `weddingStart` (currently 6:00 PM IST, because the card says "evening").
- Map button: index.html → find `mapBtn` and replace the link with the exact Google Maps link of the venue.
