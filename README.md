# AI Tracker

A calorie tracker that lives as a static web page and opens from an iOS Shortcut.

## How the system works

- The page (`index.html`) is hosted on **GitHub Pages** — reachable from anywhere, free.
- The **iOS Shortcut** just opens the page's URL. The shortcut never changes.
- Claude edits `index.html`, commits, and pushes. GitHub Pages redeploys automatically.
- Result: Claude changes the app, your phone shows the new version — no re-import.

## Status

Step 1: get a shortcut that opens the page. ✅ (that's the goal for now)

Next steps (later): food logging, running totals, storage.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```
