# Checkbook_Excel
 Excel Checkbook with buffers

This is a basic checkbook. I tried to keep it as simple as I could but with a couplle of advanced features.

Balance your checkbook before you start.

Cell H2 - Enter the balance from your bank statement.
Enter every item from your account that have not cleared yet.
Cell G3 - Enter a number that cauuses the cell C2 to be 0.00

Use:
Enter each transaction making sure you place the amount in the correct column.
When you are done, copy down colummn G allowing Excel to modify the formula's cell reference

Reconciling your account:
Cell H2 - Enter the new balance from your bank statement.
For each item that has cleared the bank, mark it with an X in column D.
When you have completed all your items, cell C2 should be 0.00 indicating you have balanced your acocunt.

What remains:
the very bottom cell in column G is what remains in your account.

Buffers:
If you want to tuck some money away as though it were a savings account:
Add a line in the checkbook sheet in column F and immediately mark it with an X.
Notice that C2 will no longer show 0.00
Go to the Buffers sheet and add a line with the same amount.
*There are several buffers you can use.
C2 will now show 0.00
When you want to use your buffer, enter a line on the appropriate buffer for the amount you want.
Go to the Checkbook sheet and add the line in making sure you mark it with an X.
Done.
