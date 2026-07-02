# SHOWREEL — Media Guide
**Section:** First section on the page — full-screen background video above the fold

---

## What it is
A full-screen looping video that plays automatically when the page loads.
It plays muted with no controls visible. Covers the entire viewport height.

---

## How to replace the video
1. Export or compress your showreel as an MP4 file.
2. **Keep the filename exactly:** `Ha Why?_Final Music Video.mp4`  
   *(or update the filename in index.html if you rename it — look for `<source src="...">` inside the `#showreel` section)*
3. Drop the new file into this folder, replacing the old one.

---

## Recommended specs

| Setting       | Value                                        |
|---------------|----------------------------------------------|
| Format        | MP4 (H.264 video codec)                     |
| Resolution    | **1920 × 1080 px** (1080p HD)               |
| Aspect ratio  | 16:9 (widescreen)                            |
| Duration      | 20–60 seconds (loops seamlessly)             |
| File size     | Keep under 30 MB for fast page loading       |
| Frame rate    | 24 fps or 30 fps                             |
| Audio         | Can include audio — it is muted on the page  |

---

## Tips
- Keep the most important action in the **centre of the frame** — edges may be cropped on narrow screens.
- The video plays muted, so it must work without sound.
- Avoid small text in the video — it won't be readable at smaller screen sizes.
- Compress with **HandBrake** (free app) using the "Web Optimised" preset for fast loading.
- A clean 20-second loop with a fade-out works better than a raw long video.
