# SQL Lab — first working version

A standalone browser-based SQL practice PWA starter with a real SQLite engine powered by sql.js.

## Run locally on Windows 11
1. Download and extract `sql-lab-v1.zip`.
2. Open the extracted `sql-lab` folder.
3. Double-click `index.html` to open it in Chrome or Edge.
4. Keep an internet connection for the first load because SQLite's browser engine is loaded from cdnjs.
5. Use Playground, Practice Arena, Micro-Projects, and My Progress.

If opening directly from a file causes browser restrictions, use VS Code with the Live Server extension:
- Open the folder in VS Code.
- Right-click `index.html` → Open with Live Server.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a public repository named `sql-lab`.
2. Upload `index.html` and `README.md` to the repository root (or use GitHub's Add file → Upload files).
3. Open repository Settings → Pages.
4. Under Build and deployment, choose `Deploy from a branch`.
5. Select `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear in Settings → Pages.

## What's included
- SQLite query runner, result tables, schema browser
- Sample HR, customer, product, orders and order-items data
- Practice questions with layered hints and worked solutions
- Challenge checking against expected SQLite output
- Three guided micro-projects
- Browser-local progress and query history
- JSON export of progress

## Important notes
- Progress is saved in the browser on the current device; it is not cloud-synced.
- The SQL engine loads from a CDN, so an internet connection is needed to start the app.
- This is a learning prototype, not a secure production database. Do not enter confidential data.
- Includes a web app manifest and service worker for installability and shell caching. The SQLite engine still needs an internet connection on first load because it is loaded from a CDN.
