# Safety Items Desk V1

Mobile-friendly, offline-first PWA for tracking employee safety-item issues and pending requests.

## Features
- 84 employee records imported from the current roster.
- Employee search, usual-shift assignment, and per-transaction shift selection.
- Cotton Gloves and Rubber Gloves: one issue per week.
- Mask: daily issue rule.
- Helmet, Safety Boots, Chin Guard, Goggles, and Safety Jacket are separate tracked items.
- Every item has an editable issue rule (weekly limit, daily limit, damaged/replacement, supervisor approval, no limit, or not set/blocked).
- Monthly per-employee issue history and request history.
- Stock tracking, pending requests, daily reports, quick daily-close print/backup actions, CSV export, and JSON backup/restore.
- Reports tab supports editing or deleting issue records and editing or deleting pending requests; deleting an issued record returns its quantity to stock.
- Printed daily reports include the selected report date.

## Weekly periods
V1 uses day 1–7 as Week 1, 8–14 as Week 2, 15–21 as Week 3, and 22–month-end as Week 4. Confirm this matches the site's actual weekly issue cycle before relying on it for policy enforcement.

## Publish on GitHub Pages
1. Open repository Settings → Pages.
2. Select Deploy from a branch, branch `main`, folder `/(root)`, then Save.
3. Open the Pages HTTPS URL on Android Chrome and choose Add to Home screen / Install app.

## Data warning
All transaction data is stored in local browser storage on the current phone. It does not sync to other devices. Use Reports & Backup → Download full backup regularly, and restore the JSON backup if needed.
