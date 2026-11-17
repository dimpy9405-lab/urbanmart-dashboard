# UrbanMart Business Intelligence Dashboard

A static, interactive dashboard built from the supplied UrbanMart transaction dataset.

## Files
- `index.html` — dashboard interface and charts
- `transactions.json` — transaction data used by the dashboard

## Run locally
Open this folder with a local web server (for example, VS Code Live Server). Because the dashboard loads `transactions.json`, opening `index.html` directly as a file may be blocked by browser security.

## Publish using GitHub Pages
1. Sign in to GitHub and create a **new public repository**, for example `urbanmart-dashboard`.
2. Upload both `index.html` and `transactions.json` to the repository root (same folder).
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the Pages deployment to finish. GitHub will show your website URL in the Pages section, usually `https://YOUR-USERNAME.github.io/urbanmart-dashboard/`.

## Dashboard features
- Revenue, transaction count, top category and repeat-purchase rate
- Monthly revenue trend
- Category revenue and return-rate charts
- Repeat-purchase rate by customer segment
- Delivery days versus customer rating
- Filters for product category, customer segment and month

The dashboard uses Chart.js from a CDN, so an internet connection is required to load the charts.
