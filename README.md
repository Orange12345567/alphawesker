# Alpha Wesker — Static Site for Vercel

A zero‑JS static page that displays a single image with a red caption **“Alpha Wesker”** underneath.

## How to use
1. **Replace the image**: Put your image file at the project root and name it exactly `alpha-wesker.png` (overwrite the placeholder).
   - Accepted type used here: PNG. If your file is JPG/JPEG/WebP, convert it to PNG or adjust `index.html` to match your filename.
2. **Deploy to Vercel**:
   - Go to https://vercel.com/new and select **Import Project** → **Upload**, then upload this ZIP.
   - Or push these files to a Git repo and import it into Vercel.
3. That’s it. The site only displays the image with the red caption “Alpha Wesker” beneath it.

## Notes
- The layout is centered, responsive, and uses a dark background.
- If you want to change the caption text or color, edit the `.caption` div or its CSS in `index.html`.
