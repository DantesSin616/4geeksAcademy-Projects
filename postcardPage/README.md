Postcard page

This simple static postcard page follows the typical 4Geeks "postcard" project layout: an image to the left and a message/address section to the right.

Files created:
- `index.html` – the postcard HTML.
- `styles.css` – styling (responsive) and a few CSS variables to adjust.
- `assets/` – directory for the postcard image.

Using your attached image
1. Save the image you attached to this conversation into this project as `assets/postcard.png`.
   - On Linux/macOS you can copy it to the folder, or rename.
2. Open `index.html` in your browser to preview.

Adjusting exact dimensions
- If the syllabus requires a specific width/height for the image, open `styles.css` and change the `--image-width` variable in the `:root` block (currently `320px`) to the required width. The image will keep its aspect ratio because `height:auto` is used.
- You can also adjust `--postcard-width` and `--postcard-height` if needed.

Notes & verification
- I couldn't reliably extract the exact numeric dimensions from the syllabus page programmatically in this session; if you tell me the required width and/or height (for example `300px` wide), I will update `--image-width` and test again.
- To preview locally, just open `index.html` in a browser (double-click or `xdg-open index.html` on Linux).

Next steps I can do for you
- If you provide the exact required pixel dimensions, I will update `styles.css` and ensure the image displays exactly at that size.
- I can also embed the provided image as a base64 data URL into `index.html` if you'd prefer the page be self-contained.
