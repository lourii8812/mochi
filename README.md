# Mochi! Virtual Pet
A responsive, installable virtual pet PWA with a midnight-purple look.

## Included features
- Pet care needs that change over time and while you're away
- Feed, bath, play, rest, and pet interactions
- Coins, levels, XP, daily gift, and a star-catching mini-game
- Accessory shop and wardrobe
- Memory stats, pet renaming, and local save import/export
- LocalStorage persistence and offline service-worker caching
- Responsive layout and home-screen install manifest

## Run locally
Because service workers require localhost or HTTPS, use a local server instead of opening the HTML file directly. For example, with Python installed, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser. To publish, upload the folder contents to GitHub Pages or another static HTTPS host.

## Notes
Progress is saved in the browser on the current device. Import/export lets you move a save manually. The Google Fonts import improves typography online; the system font fallback works offline.
