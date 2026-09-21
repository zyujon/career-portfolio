# My Career Tech Portfolio
Tracking my transition into data analysis and cloud engineering.

## 🚀 Active Learning Log (Latest Notes)
- **[Today's Date]:** Working on timeline formulas. Figured out how to handle blank end dates using `TODAY()`.

## 📊 Excel Formulas & Cheat Sheet
- **Timeline Slip:** `=IF(H2="", TODAY()-F2, H2-F2)`
- **Cost Variance:** `=K2-J2`

## 🗂️ Project Tracker Notes
- (Drop your random thoughts or project blockers here)


In 'Project Management' dataset, some 'tasks' were still ongoing (no end date). When running formula to see days overdue planned end date, it was -45k days. Updated the formula to an IF formula. and used if column is blank, then use "TODAY()" instead of the blank column.  
=IF(G2="",TODAY()-F2,G2-F2)
