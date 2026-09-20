# Life Receipts

**Your life, in receipts.**

A quiet, single-page web app that turns ordinary data — Spotify listening history and household transactions — into a visual archive of the little things that became your life.

## Live Demo

Once GitHub Pages is enabled, the site will be available at:

**https://243sps-sys.github.io/life-receipts/**

## Features

- **Overview** — Stats + charts for top artists and spending categories
- **Timeline** — Combined chronological stream of music + money (searchable)
- **Music** — Top artists and listening activity
- **Spending** — Category breakdown
- **Daily Receipt** — Pick any date for a printable-style snapshot of that day’s music and spending
- **CSV Upload** — Load your own Spotify export + transactions CSV (everything stays in the browser)
- **Demo data** — Works immediately so you can explore before uploading

## Privacy

All processing happens **locally in your browser**. No data is sent to any server.

## How to use your own data

1. Open the site
2. In the left sidebar:
   - Upload your Spotify listening history CSV
   - Upload your household / expense transactions CSV
3. Charts, timeline and daily receipt update automatically

### Spotify export

Request your data from Spotify (Account → Privacy settings → Download your data). Use the streaming history files (they contain columns like `ts`, `track_name` / `master_metadata_track_name`, `artist_name`, etc.).

### Transactions CSV

Any CSV with columns such as `Date`, `Category`, `Amount`, `Note` (or similar) works. Flexible column name matching is built in.

## Tech

- Single self-contained HTML file
- Chart.js (CDN)
- Pure client-side JavaScript — no build step, no backend

## License

Feel free to fork, use, and adapt.
