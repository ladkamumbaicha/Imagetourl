# Image URL Converter Website — Cloud Name Pre-filled

This version has your Cloudinary Cloud Name already added:

- Cloud Name: dlyzi2ma

Your API Key and API Secret are **not** included because frontend website code is visible to everyone in the browser. Do not put your API Secret in HTML, CSS, or JavaScript files.

## What you still need

Create one unsigned upload preset in Cloudinary:

1. Open Cloudinary Dashboard.
2. Go to Settings → Upload.
3. Add upload preset.
4. Set Signing mode to Unsigned.
5. Copy the preset name.
6. Open `index.html`, click Cloudinary Setup, paste only the unsigned preset name, and save.

After that, upload any image and copy the generated URL.
