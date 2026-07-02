# UPDATES — News Thumbnails Media Guide
**Section:** Fourth section (Updates) — the Updates and Workshops lists on the right side

---

## What it is
Small square thumbnail images displayed next to each news item, award, or workshop entry
in the Updates and Workshops columns.

---

## Current files and which news items use them

| File                    | Used for                                                     |
|-------------------------|--------------------------------------------------------------|
| `Ananda_FICCIBAF.jpeg`  | Laval Virtual 2025 · Courant3D 2025 · FICCI BAF Awards 2025  |
| `Ananda_JioMAMI.jpg`    | Busan International Short Film Festival                      |
| `VR_Filmmaking_Setup.png` | VR Filmmaking Workshop · IIT Jodhpur + NID Ahmedabad       |

---

## How to replace a thumbnail
1. Prepare your image.
2. Name it clearly (e.g., `Ananda_LavalVirtual.jpeg`).
3. Place it in this folder.
4. In `index.html`, update the `<img class="news-thumb" src="...">` for the relevant news item.

---

## Recommended specs

| Setting       | Value                                                   |
|---------------|---------------------------------------------------------|
| Format        | JPEG (best for photos)                                  |
| Resolution    | **400 × 400 px** (square)                               |
| Aspect ratio  | **1:1 square** — the CSS auto-crops to square with object-fit: cover |
| File size     | Keep under 100 KB per image                             |

---

## Tips
- The thumbnail appears at **72 × 72 px** on screen — fine detail is not critical.
- **Square crops** work best; non-square images are auto-cropped from the centre.
- Use one clear, well-lit image that relates to the specific award or event.
- Ideally, use a different photo for each news item for variety — currently three items share the same image.
