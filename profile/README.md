## JAJPO: free tax and invoicing tools for US freelancers

[JAJPO](https://jajpo.com/) makes free calculators and templates for freelancers, 1099 contractors and the self-employed. Every tax figure comes from IRS publications, every result shows its working, and nothing you type leaves your device.

### Open source

| Repository | What it is |
|---|---|
| [**us-tax-data**](https://github.com/jajpo-tools/us-tax-data) | US federal tax figures for 2026 and 2027 as JSON and CSV: brackets, standard deduction, self-employment tax, QBI, 1099 thresholds, estimated tax dates, retirement limits. Each figure has its IRS source. |
| [**self-employment-tax**](https://github.com/jajpo-tools/self-employment-tax) | A JavaScript library for self-employment tax, federal income tax on 1099 income and quarterly estimated taxes. Zero dependencies, tested against IRS tables. |

### Try the tools

- [1099 Tax Calculator](https://jajpo.com/taxes/1099-tax-calculator/): self-employment tax and income tax, every step shown
- [Quarterly Estimated Tax Calculator](https://jajpo.com/taxes/quarterly-tax-calculator/): what to pay on each IRS due date
- [Free Invoice Generator](https://jajpo.com/getting-paid/invoice-generator/): a PDF invoice with no sign-up
- [All tools](https://jajpo.com/all-tools/)

### How we build

- **Official figures:** from the IRS and the Social Security Administration, with sources listed on every tool.
- **Tested:** calculations are checked against the tables and worked examples the IRS publishes ([test cases](https://jajpo.com/test-cases/)).
- **Private:** no account, and the numbers stay in your browser.

The tools give planning estimates, not tax advice.
