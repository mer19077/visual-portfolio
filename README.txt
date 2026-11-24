VISUAL ARCHIVE — PUBLISHING GUIDE

WHAT THIS ZIP CONTAINS
- index.html: the entire portfolio, self-contained. Every image and video is embedded as a data URL, so the page works by double-clicking without a server.
- Start-Portfolio.bat      (Windows)
- Start-Portfolio.command  (macOS)
- start-portfolio.sh       (Linux)
- README.txt: this file.

The launcher scripts are optional. They start a tiny local HTTP server so you can preview the exact file over http:// instead of file://. Use them only if you prefer HTTP during development.

HOW TO USE IT
Option A — No server (recommended):
  Double-click index.html. Everything loads because media is embedded in the HTML.

Option B — With local HTTP server (optional):
  Windows: double-click Start-Portfolio.bat
  macOS:   double-click Start-Portfolio.command (you may need right-click > Open the first time)
  Linux:   open a terminal here and run: bash start-portfolio.sh
The scripts require Python 3 or Node.js to be installed. If neither is available, fall back to Option A.

PUBLISH WITHOUT GITHUB PAGES
You don't have to publish anywhere. The exported index.html is the portfolio. You can:
  • Keep it on your computer and open it with a double-click.
  • Email it or put it on a USB drive.
  • Upload it to any static host later (GitHub Pages, Netlify, Cloudflare Pages, Neocities, etc.) — no media folder required.

PUBLISH ON GITHUB PAGES (if you want a public URL)
1. Unzip this file.
2. Create a GitHub repository.
3. Upload only index.html to the repository root. Do NOT upload the whole folder, do NOT create a media folder.
4. Settings > Pages > Deploy from a branch > main > /(root). Save.
5. Open the URL shown in Settings > Pages.

ABOUT FILE SIZE
Because media is inlined as base64, index.html is roughly 33% larger than the combined size of your source files. For a handful of photos this is fine. For many or very large videos, compress them before importing.

UPDATES
Re-export from the editor and replace index.html in your chosen host (or keep the new file locally). There is no media folder to keep in sync.
