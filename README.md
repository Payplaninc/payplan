# PayPlan V3 — Cash-flow tools

Upload `index.html` and `payplan-logo.png` to the root of the GitHub Pages repository.

## New in V3
- Added a Spending section for manual expense logging.
- Added an Income section for expected income items with recurrence.
- Added a scheduled activity view and 30-day fallback forecast when no payday is entered.
- Improved date validation and monthly recurrence handling.
- Continues saving prototype data in the current browser using localStorage.

## Deployment
In the `payplan.github.io` repository, upload/replace `index.html` and ensure `payplan-logo.png` is present at the same root level. Commit to the Pages branch, wait for deployment, then refresh the live site.

## Important limitations
This is a prototype, not a bank-connected financial service. Data is stored only in the browser/device and is not synced or protected by an account system. The forecast is simplified and may not reflect pending transactions or all real-world spending. Do not rely on it as a guarantee of available funds.
