In 'Project Management' dataset, some 'tasks' were still ongoing (no end date). When running formula to see days overdue planned end date, it was -45k days. Updated the formula to an IF formula. and used if column is blank, then use "TODAY()" instead of the blank column.  
=IF(G2="",TODAY()-F2,G2-F2)
