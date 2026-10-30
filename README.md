# Options Trading Lab

Static pages for learning and practicing options day trading. No build step; every page is a single self-contained HTML file with a shared top menu.

| Menu item | Path | What it is |
|---|---|---|
| Home | `/` | Landing page |
| Learning | `/learning/` | Price Action Playbook: interactive chart lessons, position size calculator, quiz |
| Learning II | `/learning/part-2/` | Part 2: VWAP and volume, timeframes, trade management, option Greeks, day types, expectancy, quiz |
| Checklist | `/checklist/` | ORB Daily Game Plan: tick-off trading day routine; dollar limits are entered by the user and kept in the browser |
| Ledger | `/ledger/` | Options P&L ledger: import a Robinhood activity CSV for daily and monthly P&L, rules check, risk stats |

## About the ledger's data

The hosted ledger keeps everything in the browser's local storage. Nothing is uploaded and no trade data is stored in this repo. Data is per browser and per device, so import your CSV again on each one. Clearing site data removes it.

## Hosting

Any static host works. For GitHub Pages: Settings > Pages > Deploy from a branch > `main` / root. For Netlify or Vercel: point at the repo with no build command and `.` as the publish directory.

## Adding a page

Create a folder with an `index.html`, then add a link to it in the nav bar of each page (the `otl-nav` block near the top) and a card on the landing page.

All prices in the lessons are illustrative. Educational only, not financial advice.
