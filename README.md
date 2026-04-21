# Authenticity Verification System

This repository contains a static web page for verifying product authenticity using a QR code and Google Sheets database.

## Features
- Elegant dark‑mode UI with glass‑morphism effects
- Real‑time verification against a Google Sheets CSV export
- Responsive design for mobile and desktop

## Deploy to GitHub Pages
1. **Create a GitHub repository** (public or private).
2. Clone the repo locally:
   ```bash
   git clone https://github.com/USERNAME/REPO_NAME.git
   cd REPO_NAME
   ```
3. Copy all project files into the cloned folder (replace existing files if prompted).
4. Commit and push:
   ```bash
   git add .
   git commit -m "Initial commit – verification page"
   git push origin main
   ```
5. In the GitHub repository settings, enable **Pages**:
   - Source: `main` branch, `/ (root)`
   - Save. GitHub will publish the site at `https://USERNAME.github.io/REPO_NAME/`.

## Customization
- Edit `SHEET_CSV_URL` in `index.html` to point to your Google Sheet CSV.
- If you prefer a local JSON fallback, set `USE_SHEETS = false` and modify `BOTTLES_LOCAL`.

---
© 2026 Unimag. All rights reserved.
