# Ruku — Academic Portfolio Website

A responsive, dark-blue personal portfolio for Ummay Habiba Ruku. It uses plain HTML, CSS, and JavaScript, so you can edit it without installing a framework.

## Run the website on your laptop
1. Extract `Ruku_Portfolio_Website.zip`.
2. Open the extracted `ruku_portfolio_website` folder.
3. Double-click `index.html`. It should open in your browser.

For a smoother editing workflow, open the folder in VS Code and use the Live Server extension (optional).

## How to edit
- **Text and sections:** open `index.html` in Notepad or VS Code and edit the relevant text.
- **Colors, spacing, design:** edit `style.css`. The main theme colors are at the top under `:root`.
- **Menu behavior and current year:** edit `script.js`.
- Save your changes and refresh the browser.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new public repository, for example `ruku-portfolio`.
2. Upload `index.html`, `style.css`, and `script.js` to the repository's root (you may also upload this README).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for the published link to appear in the Pages section.

## Important notes
- This is an editable source-code website; changes are made in the files and then uploaded again to update the published version.
- This package does **not** include a password-protected online admin panel or database. A secure admin panel needs an authentication service and database (for example, Supabase) and should be set up separately.
- Google Fonts loads online; if offline, the browser will use fallback fonts.
