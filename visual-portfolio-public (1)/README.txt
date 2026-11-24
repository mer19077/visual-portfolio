VISUAL PORTFOLIO — PUBLISHING GUIDE

CONTENTS
- index.html: the public portfolio page.
- portfolio.json: work details (also embedded in index.html for local preview).
- media/: ALL images and videos used by the page.

IMPORTANT: KEEP THE FOLDER STRUCTURE
After extracting this ZIP, index.html, portfolio.json, and the media folder must be side by side. Do not rename the media folder and do not move its contents elsewhere.

PUBLISH WITH GITHUB PAGES
1. Unzip this file.
2. Open the extracted folder and confirm that media/ contains the image/video files.
3. Create a GitHub repository.
4. Upload ALL contents of the extracted folder to the repository root. Do not upload only index.html or portfolio.json. The media/ folder must sit beside index.html.
5. Open Settings > Pages.
6. Under Build and deployment, choose Deploy from a branch.
7. Select the main branch and the /(root) folder, then save.
8. When publishing is complete, open the URL shown in Settings > Pages.

LOCAL PREVIEW
The work list is embedded in index.html, so you can usually double-click index.html to preview the export locally. Keep media/ beside it. If your browser still blocks local media, run the folder through a local web server such as VS Code Live Server.

UPDATES
Export again and replace ALL previously published files, including the media/ folder, with the contents of the new ZIP.
