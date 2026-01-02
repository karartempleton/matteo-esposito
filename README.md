# Portfolio Gallery (Basic)

A minimal portfolio/gallery site with:
- White background, black captions under each photo.
- Upload page to add images and captions.
- Node/Express backend stores images in `/uploads` and captions in `captions.json`.

Quick start:
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Open http://localhost:3000 in your browser.
4. Upload images at http://localhost:3000/upload.html

Notes:
- Uploaded images are stored in `/uploads` (server filesystem). If deploying, consider using object storage (S3) for persistence across instances.
- If you want a static-only approach (no server) I can provide a Cloudinary or Netlify CMS setup instead.
