# Educate! In-school Exhibition 2026 – live results dashboard

`index.html` reads the scoring Google Sheet directly (tabs Schools, Teams, CU Summary) and refreshes every 5 minutes. No data is stored in the page.

## 1. Let the page read the sheet (choose one)
- Share → General access → "Anyone with the link: Viewer", or
- File → Share → Publish to web → "Entire document" → Publish. Copy the id from the link (the part after `/d/e/`, starting `2PACX-`) into `PUB_ID` at the top of the script in `index.html`.

## 2. Publish on GitHub Pages
Upload `index.html` to a repository → Settings → Pages → Deploy from a branch → `main` / root.

## Privacy
Anyone who can open the page can read the school, project and judge names in those tabs. Keep the repository and sheet access in line with who should see them.
