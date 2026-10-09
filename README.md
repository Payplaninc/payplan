# PayPlan V2 prototype

## Files
- `index.html` — responsive PayPlan dashboard, recurring bill schedules, and local browser persistence.
- `payplan-logo.png` — approved logo image used in the header.

## Update the live GitHub Pages site
1. Open the `payplan.github.io` repository in the PayPlan organization.
2. Upload/replace `index.html` and add `payplan-logo.png` at the repository root.
3. Commit changes to the branch configured for GitHub Pages.
4. Wait for deployment, then reload the site. A hard refresh may be needed.

## V2 improvements
- Uses the approved P-and-upward-arrow logo image with tagline.
- Supports one-time, weekly, every-two-weeks, monthly, and yearly bill schedules.
- Saves the current prototype's plan and bills in local browser storage.
- Updates the simplified safe-to-spend estimate using bills due before the next payday and a cash cushion.

## Important limitations
This is still a prototype. Browser storage is local to one browser/device and is not encrypted account storage or cloud sync. Do not use shared devices for sensitive financial information. It is not bank-connected, and estimates do not include every transaction or expense. Validate all calculations before using this with real financial decisions.
