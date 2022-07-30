# expense-tracker

Python expense tracker that takes in transactions and creates a google sheet with appropriate data and metrics about my spending.

# APP REQUIREMENTS:

- [ ] Ingest transaction data in the form of bank statements or as JSON from API calls
- [ ] Categorize transaction data
- [ ] Store categorized transaction data in google sheets, one for the month and one for the year

### APP EXTENSIONS:

- [ ] Application with run automatically on a CRON job with the necessary inputs either uploaded and in place of available via API request from banks and loans and investments services
- [ ] Expense tracker will track more than categorized transaction data -- we will track investment data and loan payoff data

### Spreadsheet features:

Monthly

- Top Categories:
  - transaction counts
  - percentage of each category against all spending
- Category movements:
  - which categories grew in spending and by how much (dollar amount and %)
  - which categories fell in spending and by how much (dollar amount and %)
