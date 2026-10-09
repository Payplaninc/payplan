# PayPlan V4 — Dashboard insights and data controls

Upload `index.html` and `payplan-logo.png` to the root of the existing GitHub Pages repository.

## What's new
- Monthly pie chart on the dashboard; switch between spending and income vs outflow.
- Edit or delete existing bills, income items, and expenses.
- JSON export/restore for browser-local data.
- Responsive chart layout and monthly selector.
- V3 data preserved with the existing `payplan-v3-data` localStorage key.

## Notes
- No bank connection. Chart uses only manually logged expenses and scheduled occurrences.
- Income vs outflow chart shows combined positive values as proportions, not a net cash balance.
- Main dashboard paycheck is not automatically included as income in the chart (add it to Income to track it).
- No standalone savings ledger exists yet, so savings are not shown.
- Backups are unencrypted: keep exported JSON private.
- Data stays on the same browser/device unless manually exported and restored.
- Forecast remains a simplified estimate.

## Suggested smoke tests
1. Load with prior V3 browser data; verify records persist.
2. Add/edit/remove bill, income, and expense; verify chart updates.
3. Switch chart mode and month.
4. Export, reset, restore; verify amounts and records.
5. Check phone width and desktop.
