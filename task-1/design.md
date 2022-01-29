# Task 1:
1. As each account should connect to the customer who is responsible for paying the bill, Account and Customer should have a association relationship. And the Customer side should have a '1'.
2. Delete the relationship between Call and MonthlyStatement at the same time.
3. As the MonthlyStatement is made by CallLog, the relationship between Call and MonthlyStatement should be move to the relationship between CallLog and MonthlyStatement. 
4. MonthlyStatement and Account should have a dependency relationship because one statement is sent to the customer contact for each account.
