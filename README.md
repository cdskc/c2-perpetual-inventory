# C-II perpetual inventory
## An Excel Workbook powered by macros to track controlled substance inventory.

Replace paper logs and basic spreadsheets with a more powerful alternative. From the Home sheet, scan the barcode of a stock bottle and you're taken to the page for that drug. For an NDC[^1] that's not in the system, a new sheet is created based on a blank template. When the user enters the quantity for receiving or dispensing, the new balance on hand is calculated automatically, but is highlighted in red as a reminder to backcount. Double-click the cell to confirm, which changes the visual indicator and records the date.

Version 0.3 updates:
- Minimal instructions included on Home page.
- Template cleaned and updated.
- Home button in top left of drug record functions correctly on double-click
- Added logic to select "Previous inventory" cell on a blank sheet, or the next Rx# cell for dispensing on an existing sheet.

[^1]: UPC really, and I don't understand why they're different in a non-standard way ¯\\\_(ツ)\_/¯
