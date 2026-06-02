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
