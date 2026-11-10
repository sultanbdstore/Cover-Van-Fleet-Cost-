<p align="center"><img src="logo.png" alt="Fleet Cost logo" width="160"></p>

# Executive Fleet & Costing Intelligence Dashboard

Upload your monthly cover van trip Excel sheet. The tool separates the trips by vehicle (**DM MA 11-3260** Arabi Fashion and **DM MA 11-3261** Novel Hurricane), shows cost / trips / distance dashboards, and exports a formatted costing file for each vehicle.

The file is read in your browser; nothing is uploaded to a server.

## How to use

1. Open the page (see *Run it*).
2. Click the upload box and choose the monthly `.xlsx` / `.xls` trip sheet.
3. Check the KPI cards and charts.
4. Check the **Rate per KM** box (default 24), then download the Arabi Fashion file, the Novel Hurricane file, or both.

## Rate per KM

The **Rate per KM** box on the page sets the **RATE / PER KM** column of both exported Excel files. The default is **24**.

1. Type the rate for each vehicle (decimals allowed, for example 24.5).
2. Press **Apply Rate**. The rate is remembered in your browser, so you only change it when the rate changes.
3. Download the files. Every trip row shows the rate you set, with two decimal places.

Changing the rate does not change TOTAL COST; costs still come from your Excel sheet.

## Run it

**Locally:** open `index.html` in Chrome or Edge. An internet connection is needed because the page loads SheetJS, Chart.js, Font Awesome and Google Fonts from CDNs.

**GitHub Pages:** in *Settings → Pages* choose **Deploy from a branch** → `main` → `/ (root)`, or choose **GitHub Actions** to use the included workflow. Your site address is `https://YOUR-USERNAME.github.io/REPO-NAME/`.

**Google Sites:** after publishing on GitHub Pages, use Insert → Embed → By URL and paste the Pages address.

## Project structure

```
index.html              the whole app in one file
logo.png                root copy of the logo (used by this README)
icons/                  logo, favicons, apple-touch-icon, 192/512 and maskable icons
manifest.webmanifest    installable-app (PWA) manifest
favicon.ico             browser tab icon
.nojekyll               makes GitHub Pages serve files as-is
.github/workflows/      GitHub Pages deployment (optional)
```

## License

MIT, see [LICENSE](LICENSE).
