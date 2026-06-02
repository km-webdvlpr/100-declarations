# Access Guide

## Best User Experience

Host this folder as a tiny static website and give the user one URL.

Good quick options:
- Netlify Drop: drag this whole folder into Netlify Drop.
- GitHub Pages: upload the files and publish the repo root.
- Any static host: serve `index.html`, `manifest.webmanifest`, `icon.svg`, and `sw.js`.

Once hosted, the user can:
- Open the URL on mobile or laptop.
- Bookmark it in the browser.
- On mobile, use "Add to Home Screen" or "Install App" where available.
- Reopen it throughout the day; progress is stored in that device browser.

## Important Progress Note

Progress is stored locally per device. If the same person uses both phone and laptop, those devices will not automatically sync.

Use the app's Backup and Restore buttons to move progress between devices when needed.

## 100-Day Spreadsheet Log

Use `100-declarations-log-template.xlsx` as the simple spreadsheet database.

Daily workflow:

1. Open the app.
2. Use it normally throughout the day.
3. Tap `CSV`.
4. Import or paste the CSV rows into the `Declaration_Log` sheet.

The workbook includes:

- `Declaration_Log` for raw app events.
- `Declarations` as the master list of all 100 declarations.
- `Daily_Summary` for the 100-day view.
- `Section_Summary` for category totals.

## Quick Local Test

From this folder, run a simple static server:

```powershell
npx serve .
```

Then open the shown local URL. For phone testing on the same Wi-Fi, use the laptop's local network IP address with the shown port.

## Files To Publish

- `index.html`
- `declarations (1).html`
- `manifest.webmanifest`
- `icon.svg`
- `sw.js`
- `100-declarations-log-template.xlsx`
- `declaration-log-import-template.csv`
