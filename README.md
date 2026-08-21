# MyImportantStuf — Drive Files Prototype

An installable iPad web app (PWA) that lists files from one Google Drive folder, with optional metadata from a Google Sheet.

## Version 1
- GitHub Pages / iPad Home Screen app
- Read-only Drive access
- Tap a file to open it in Google Drive
- Optional Sheet columns: `driveFileId | name | category | notes`

## Google setup
1. Enable Google Drive API and Google Sheets API in a Google Cloud project.
2. Configure OAuth consent/testing.
3. Create a Web application OAuth Client ID.
4. Add `https://glynsuejoint-stack.github.io` as an Authorized JavaScript origin.
5. In the app Settings enter the OAuth Client ID, Drive Folder ID, and optionally Sheet ID.

No client secret belongs in this repository.

Expected Pages address: `https://glynsuejoint-stack.github.io/MyImportantStuf/`

On iPad: open the site in Safari → Share → Add to Home Screen.
