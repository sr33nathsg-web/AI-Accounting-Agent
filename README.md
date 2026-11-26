# AI Accounting Agent – Starter Project

A reusable prompt-and-template toolkit for analysing transaction files and drafting accounting records and financial statements for human review.

## Project contents
- `prompts/`: Claude agent prompts and workflow instructions.
- `templates/`: Excel templates for chart of accounts, journal entries and trial balance.
- `examples/`: Synthetic sample transactions (no real company data).
- `documentation/`: Workflow, accounting control principles and Singapore SME notes.

## Quick start with Claude
1. Attach transaction data (bank statements, invoices, cashbook, etc.) and, if available, opening Trial Balance and Chart of Accounts.
2. Copy `prompts/master_accounting_agent.md` into Claude, or use it as Project Instructions.
3. Ask Claude to work through all phases, produce the workbook, and list assumptions and items requiring review.
4. Review all proposed entries and adjustments before posting to accounting software or using statements externally.

## Important
This toolkit is a bookkeeping drafting aid, not an accounting system, audit, tax, or legal opinion. Automated classifications and proposed journal entries must be reviewed. Do not upload confidential or personal data to repositories. Keep real source files out of GitHub; use synthetic examples only.

## Folder structure
```text
AI-Accounting-Agent/
├── prompts/
├── templates/
├── examples/
├── documentation/
├── README.md
└── .gitignore
```
