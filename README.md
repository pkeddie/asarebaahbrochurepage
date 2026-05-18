# PDF Single-Page Site

This project hosts a single PDF on one public web page using static files.

## Files

- `index.html` — main page with embedded PDF viewer and fallback button
- `styles.css` — lightweight styling
- `funeral-book.pdf` — hosted PDF file

## Replace the PDF later

1. Replace `funeral-book.pdf` with your new file.
2. If you use a different filename, update both references in `index.html`:
   - `href="funeral-book.pdf"`
   - `src="funeral-book.pdf"`

## Deploy to GitHub Pages (free)

1. Create a new GitHub repository.
2. Push these files to the `main` branch root.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Save and wait for deployment.

Your public URLs will be:

- Page URL (recommended for QR):
  - `https://<github-username>.github.io/<repo-name>/`
- Direct PDF URL (fallback):
  - `https://<github-username>.github.io/<repo-name>/funeral-book.pdf`

## Local preview

Open `index.html` in a browser to check rendering and fallback link behavior.
