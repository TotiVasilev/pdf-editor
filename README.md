# PDF Studio — static PDF editor

A starter website that opens PDFs, adds visible text, dates, checkmarks, and signatures, then saves an edited PDF.

## Publish using GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html` to the repository root (or use **Add file → Create new file** and paste its code).
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, then **main / (root)**, and save.
5. Open your GitHub Pages link once GitHub shows it.

No server, build step, or credentials required. An internet connection is needed to load pdf.js and pdf-lib from their CDNs.

## Limitations

- Overlays content onto PDFs; does not rewrite existing text.
- Handwritten signatures are visible marks, not certificate-based digital signatures.
- Designed for ordinary non-encrypted, non-rotated PDFs. Complex forms, rotations and password-protected PDFs may need additional work.
- Files are processed in the browser; the app has no upload backend.
