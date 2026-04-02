Barcode Mobile Web App - Ready to Deploy

This package is a static web app. It does not upload CSV data to any server.
Users import CSV/TXT inside the browser, and the data is stored only in that browser via localStorage.

Recommended hosting
1) GitHub Pages
2) Netlify Drop
3) Cloudflare Pages

Files
- index.html
- manifest.webmanifest
- sw.js

Important cautions
- Serve over HTTPS only.
- Do not open via chat-app preview or drive preview.
- localStorage is tied to the exact domain and protocol.
- If you change domain/subdomain, existing saved product data will not move.
- Private browsing may clear stored data when the session ends.
- Do not add third-party analytics if the CSV is internal company data.

GitHub Pages
1. Create a new GitHub repository.
2. Upload all files in this folder.
3. In repository Settings > Pages, set source to Deploy from a branch.
4. Choose main branch and root folder.
5. Wait for the Pages URL, then open it on iPhone with Safari or Chrome.

Netlify Drop
1. Open Netlify Drop in a browser.
2. Drag this folder or a zip of these files onto the page.
3. Netlify will generate an HTTPS URL.
4. Open that URL on iPhone.

Cloudflare Pages
1. Create a new Pages project.
2. Upload the folder as a static site.
3. Use the generated HTTPS URL.

iPhone usage
1. Open the HTTPS URL in Safari.
2. Tap Share > Add to Home Screen.
3. Use Load sample data, import CSV file, or paste CSV text.
4. Tap a product, then Generate barcode.

CSV columns supported
- รหัสสินค้า
- ชื่อสินค้า
- หน่วยนับ
- บาร์โค้ด

The app also recognizes English headers like code, name, unit, barcode.
