# UPDATES — Polaroid Gallery Photos Media Guide
**Section:** Fourth section (Updates) — the interactive polaroid scatter gallery at the top

---

## What it is
The animated polaroid gallery that auto-plays through your photos.
Each photo appears as a physical polaroid card with a handwritten note and location pin.
Any photo orientation — **landscape, portrait, or square** — is automatically supported.

---

## How to replace a photo
1. Prepare your new photo file.
2. **Name it using the slot number you want to replace:**

   | Slot       | Filename           | Event shown                  |
   |------------|--------------------|------------------------------|
   | Slot 1     | `photo_01.jpeg`    | FICCI BAF Awards 2025        |
   | Slot 2     | `photo_02.png`     | Grand Prix · Laval Virtual   |
   | Slot 3     | `photo_03.jpeg`    | Grand Prix · Courant3D       |
   | Slot 4     | `photo_04.jpg`     | Busan Int'l Short Film Fest  |
   | Slot 5     | `photo_05.jpg`     | Jio MAMI Film Festival       |
   | Slot 6     | `photo_06.jpeg`    | Screening · NID Alpavirama   |
   | Slot 7     | `photo_07.jpeg`    | Safar Mein Sheher            |
   | Slot 8     | `photo_08.png`     | Screening · Laval Virtual    |
   | Slot 9     | `photo_09.png`     | VR Filmmaking Workshop       |

3. Drop the new file into this folder, replacing the old one.
4. The website automatically adapts to the new photo's orientation — no code changes needed.

---

## Autoplay order
photo_01 → photo_02 → photo_03 → photo_04 → photo_05 → photo_06 → photo_07 → photo_08 → photo_09 → (loops back)

---

## To change the title, note text, or location shown on the card
Edit the `PHOTOS` array in `index.html`.
Each entry looks like this:

```
{ src: 'media/04_Updates/Gallery_Photos_1200px/photo_01.jpeg',
  title: 'FICCI BAF Awards 2025',
  note:  'A defining night for Indian animation...',
  location: 'Mumbai, India',
  t: 10, l: 6, r: -12 }
```

- `title` — the small caption below the note
- `note` — the handwritten-style text on the polaroid
- `location` — the location pin label
- `t`, `l`, `r` — vertical position %, horizontal position %, rotation angle (don't change unless repositioning a card)

See `Index_Instructions.html` in the root folder for a full guide.

---

## Recommended specs

| Setting       | Value                                                         |
|---------------|---------------------------------------------------------------|
| Format        | JPEG or PNG                                                   |
| Resolution    | **1200 px on the longest side** (e.g., 1200×900 landscape, 900×1200 portrait) |
| Aspect ratio  | Any — the gallery dynamically fits any orientation            |
| File size     | Keep under 300 KB per photo (compress in Preview or Squoosh.app) |

---

## Tips
- Landscape photos appear wider; portrait photos appear taller in the polaroid.
- Keep important content away from the very edges — a small white border (the polaroid frame) is added.
- A consistent look — similar lighting and colour grading — makes the gallery feel cohesive.
- You can change a file extension if needed (e.g., from `.jpeg` to `.png`) — just update both the filename and the `src` in the `PHOTOS` array in `index.html`.
