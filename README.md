# MD-MMJ-Tracker
Allotment Tracker for MD MMJ Patients
Maryland MMJ Allotment Tracker
A free, open-source tool to help Maryland medical cannabis patients track their 30-day rolling allotment, log purchases, monitor spending, and review products. Everything runs in your browser -- no account, no server, no data collection.
---
What it does
Maryland's medical cannabis program limits how much you can purchase in any rolling 30-day window. The limit is calculated using a shared percentage pool across dried flower and processed THC products. This tracker implements that formula so you always know where you stand before your next dispensary visit.
Allotment tracking
Implements Maryland's official percentage-pool formula: `poolPct = (flowerBought / certFlower) + (THCbought / certTHC)`
Supports custom certified amounts (your provider may have certified you for more or less than the 120g / 36g standard)
Shows estimated remaining flower and THC, pool percentage used, and a recovery timeline showing exactly when each purchase expires from your rolling window
Calendar view showing purchase dates and allotment recovery dates at a glance
Purchase log
Log dried flower purchases by weight (grams)
Log processed products (RSO, vapes, concentrates) by delta-9 THC content in grams or milligrams
Built-in THC calculator: enter product weight and potency % and let the tracker do the math
Price tracking per purchase
Medical vs. recreational toggle per purchase (recreational purchases track spending but do not count against your allotment)
Expired purchases (outside the 30-day window) auto-hide to keep the log clean, with a toggle to show them
Spending tracker
Separate totals for medical and recreational purchases with a grand total
Toggle between this week, last 30 days, this year, and all time
Bar chart breakdown by product
---
Product journal
Review your products with five-dimension star ratings: smell, taste, effects, potency, and value
Track brand, dispensary, strain type, and notes
Link reviews to purchase log entries
Auto-fill form from your purchase history
Search and filter your product database
Archive tab
Purchases older than 30 days move here automatically
Organized by month with collapsible sections
Filter by year or medical/recreational
All archived data still counts toward your spending totals
---
How to use it
First time setup
Open your OneStop account at onestop.md.gov and find your current remaining balances
Enter your certified amounts (from your provider's certification) in Step 1
Enter your current remaining balances from OneStop in Step 2, with today's date as the snapshot date
Log any purchases made after that snapshot date in Step 3
Ongoing use
After each dispensary visit, check OneStop for your updated remaining balances and update the snapshot. Then log your new purchases with dates, amounts, and prices.
Important note on THC values for processed products
For RSO, vapes, concentrates, and other processed products, use the delta-9 THC value in milligrams printed directly on the product label -- not the potency percentage and not "Total THC." The dispensary's point-of-sale system transmits the delta-9 THC value to OneStop, which may differ from what you get by multiplying the label percentage by the product weight. Set the unit toggle to mg and enter the delta-9 THC mg number you see on the label.
---
Why the tracker may not match OneStop exactly
OneStop calculates your allotment using the exact delta-9 THC values that each dispensary's POS system transmits at the time of sale. Those values come from the product's certificate of analysis for that specific lot number and may differ slightly from what is printed on the label. Since OneStop does not provide per-transaction receipts, patients have no way to see the exact values that were transmitted.
The tracker will be very close but may have a small discrepancy per processed product purchase for this reason. Dried flower purchases by weight are always exact.
Always use OneStop as your official source of truth before making a purchase.
---
Privacy and data storage
All data is saved to your browser's local storage. Nothing is sent to any server. Nothing touches GitHub's servers except the HTML file itself (which contains no user data). Clearing your browser cache will erase your data, so use the JSON export feature regularly as a backup.
The source code is entirely contained in a single HTML file. You can open it in any text editor to read every line of code before using it.
---
Exporting and backing up your data
Use the Export button in the top right to download a JSON backup of all your purchases, settings, and journal entries. You can reimport this file at any time using the Import button. A CSV export is also available if you want to open your data in a spreadsheet.
---
Disclaimer
This tool is for personal tracking purposes only. It is not affiliated with the Maryland Cannabis Administration, any dispensary, or any state agency. It does not guarantee accuracy and should not be used as a substitute for checking your official balance in OneStop before making a purchase. The developer is not responsible for any purchase decisions made based on this tool.
Maryland's allotment rules may change. Always verify current regulations at cannabis.maryland.gov.
---
Contributing
Found a bug or have a feature idea? Open an issue or submit a pull request. This project is meant to be useful to the Maryland MMJ community and improvements are welcome.
---
License
MIT License -- free to use, modify, and share. If you build something based on this, a link back would be appreciated but is not required.
