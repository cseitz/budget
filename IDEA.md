
## Accounts

### Credit

- Account Balance
- Transactions
- Have statement due dates
- Can have various fees
- Can have a maximum credit limit

### Checking

- Account Balance
- Transactions

### Savings

- Account Balance
- Transactions
- % APR

### Investing

- Account Balance
- Transactions (Money In/Out, Stocks)

### Loans

- Account Balance
- Transactions (Payments & Additions)
- % APR



## Transactions

- Account
- Date (can be in the future)
  - If in the future, the transaction must be explicitly marked as "completed" and will be marked "overdue" past the date if not yet marked as completed
  - Will not affect balance until marked completed; but **will** be shown as `planned` and a portion of bars on graphs.
  - https://www.npmjs.com/package/rrule
- Amount
- Tags

### Income

- Source (where income is from)

### Purchases

Something was bought.

### Expenses

Same as a Purchase, except the thing being paid for was necessary.

### Adjustment

Manual adjustment that either sets the account balance, or adjust it by an amount.


## Budget

- Set budget for repeating intervals
- Transactions can be classified as part of the budget
- Budgets can contain other sub-budgets
- Tags can be selected for the budget
  - Any transactions matching those tags contribute to the utilization of the budget
- 











