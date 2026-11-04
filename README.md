# Buraq Holidays — GitHub Pages Edition

## Run locally
- Extract this folder.
- Open `index.html` in Chrome or Edge.
- For the Memory Folder feature, use a secure context: GitHub Pages HTTPS or `http://localhost` (not a `file://` tab).

## Publish with GitHub Pages
1. Create a GitHub repository, e.g. `buraq-holidays`.
2. Upload `index.html` and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then Save.
6. Wait for the deployment; GitHub will show the live URL.

## Logo
The logo is in `assets/logo.png`. Keep the exact folder name and path. Replace that file with your updated logo (same filename) to change the logo without editing HTML.

## Data and privacy
- The app stores draft data and saved bookings in the current browser's local storage. It does not upload booking records to GitHub.
- In the app, open **Memory & Storage → Choose / Connect Memory Folder** and select/create a folder on your computer. The app writes `buraq-memory.json` there when changes are saved. Reconnect the folder after reopening the browser.
- Use **Download complete memory backup** regularly and keep a second copy somewhere safe.
- GitHub Pages is static hosting and has no server-side database, multi-user sync, or login protection. Anyone with access to the app URL can open the app; browser data remains local to each browser profile. Do not treat the public page as a secure customer portal.

## Important
Never upload `buraq-memory.json`, customer records, passports, CNICs, or payment records to a public GitHub repository.
