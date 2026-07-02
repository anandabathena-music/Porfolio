# WORK — Media Guide
**Section:** Third section — the filterable project grid

---

## What it is
Thumbnail images shown in each project card in the Work grid.

---

## Important: YouTube & Vimeo thumbnails load automatically
All current projects link to YouTube or Vimeo.
Their thumbnails are **pulled automatically** from those platforms — you do not need to provide images.

This folder is only used if you add a project with a **local video file** (stored directly on your server).

---

## How to add a custom thumbnail
1. Save your image as: `project-name-thumb.jpg` (use lowercase, hyphens for spaces)
2. Place it in this folder.
3. In `index.html`, inside the relevant `.pcard`, update the `<img src="...">` inside `.pcard-thumb`.

---

## Recommended specs

| Setting       | Value                                                    |
|---------------|----------------------------------------------------------|
| Format        | JPEG (or PNG if transparency needed)                     |
| Resolution    | **1920 × 1080 px** (1080p) — or **640 × 360 px** minimum |
| Aspect ratio  | **16:9** — the card forces this ratio                    |
| File size     | Keep under 200 KB per image                              |

---

## Tips
- The thumbnail renders at roughly **360 × 202 px** on screen — fine detail at 1920x1080 is not critical.
- High contrast, bright images read better as small thumbnails.
- When you add a project using a YouTube link, the thumbnail is the YouTube video thumbnail — no file needed here.
