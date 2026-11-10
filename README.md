# NOWNET AI — Tsume Inuzuka Edition

Emotional roleplay chat powered by Puter.js, now featuring the **Tsume Inuzuka** MMD model as the live visual avatar.

## Features

- Full original NOWNET AI emotional roleplay system (Normal / Destruction modes)
- Live emotion status that drives the avatar (glow, pulse, tilt, intensity)
- Tsume Inuzuka PMX model + cleaned textures included
- Fixed female identity locked to the Tsume look while keeping the name **NOWNET AI**
- 10 dress sets, model selector, chat memory, export, etc.
- Ready for GitHub Pages

## Quick Start (GitHub Pages)

1. Create a new repository (e.g. `nownet-ai` or `Nownet-AI-Tsume`)
2. Upload **everything** in this folder (keep the `assets/` structure)
3. Go to **Settings → Pages**
4. Source: Deploy from branch `main` (or `master`), folder `/ (root)`
5. Wait 1–2 minutes, then open the URL

The model files live at:
```
assets/model/Tsume Inuzuka.pmx
assets/model/*.png
assets/model/tex/
```

## Local Preview

Any static server works:

```bash
npx serve .
# or
python3 -m http.server 8080
```

Open `http://localhost:8080`

## Notes

- The 3D model is displayed in a dedicated avatar panel. Emotion changes trigger visual reactions (color, scale, glow, subtle movement) so it “acts” with the current emotion.
- Full skeletal animation / VMD playback requires additional motion files (not included in the original MMD pack). The current integration focuses on reliable real-time emotional feedback that works on mobile and desktop.
- All original NOWNET knowledge, Nanzo Arc lore, creator credit (Navaneeth Krishna), and Puter.js chat remain intact.
- Texture paths inside the PMX were normalized for web (PNG + forward slashes).

## Credits

- Original NOWNET AI by Navaneeth Krishna / NOWNET Production
- Tsume Inuzuka MMD model: narashadows (dfw3wgm)
- Powered by Puter.js

© 2026 NOWNET Production
