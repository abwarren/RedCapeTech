# RedCapeTech — Company Governance & Compliance

A practical, auditable operating record for the governance, financial administration and statutory compliance of **RedCapeTech**, a South African private company (Pty) Ltd.

This repository is the project control centre. It tracks what must be done, records policies and procedures, and provides a version-controlled index of company records. It is **not** a substitute for CIPC, SARS, bank, payroll or accounting systems, and a Git repository alone does not establish legal compliance.

## Objectives

- Maintain accurate company and statutory records.
- Keep company and personal finances separate.
- Track revenue, expenses, liabilities, tax and cash flow.
- Document director and shareholder decisions.
- Manage payroll and distributions using a documented approval process.
- Track recurring CIPC and SARS obligations.
- Preserve an auditable history of policies and administrative changes.

## Scope

The project covers:

1. **Company foundation:** CIPC status, registration documents, MOI, director and shareholder records.
2. **Governance:** written resolutions, minutes, delegations and decision records.
3. **Finance:** bookkeeping, bank reconciliations, revenue and expense registers.
4. **Tax:** income tax, provisional tax, VAT where applicable, PAYE, UIF and SDL where applicable.
5. **Remuneration:** director remuneration, payroll evidence and dividends.
6. **Annual compliance:** annual financial statements, tax returns, CIPC annual returns and employer reconciliations where applicable.
7. **Records management:** secure storage, retention, access control and backups.

## Suggested repository layout

```text
RedCapeTech/
├── README.md
├── TODO.md
├── .gitignore
├── docs/
│   ├── company-profile.md
│   ├── compliance-register.md
│   ├── governance-policy.md
│   ├── financial-controls.md
│   └── records-retention.md
├── governance/
│   ├── resolutions/
│   ├── minutes/
│   ├── directors/
│   └── shareholders/
├── finance/
│   ├── registers/
│   ├── monthly-close/
│   └── annual-financials/
├── payroll/
│   ├── procedures/
│   └── periods/
├── tax/
│   ├── SARS-registration/
│   ├── returns/
│   └── supporting-records/
└── compliance/
    ├── CIPC/
    ├── annual/
    └── evidence/
```

Create folders as they become necessary. Do not commit confidential source documents simply because a folder exists.

## Operating principles

- **Separate accounts:** all company receipts and payments should flow through the company bank account, except where a properly documented alternative is appropriate.
- **Evidence first:** every material transaction and decision should have supporting evidence.
- **Approval before payment:** record the authority, amount, effective date and basis before processing director remuneration or a dividend.
- **Reconcile monthly:** compare the ledger with bank statements and supporting records.
- **Tax deadlines:** maintain a dated compliance calendar and verify current filing/payment dates with SARS and CIPC.
- **Version history:** use Git to track changes to templates, policies and task status, not as the sole archive for statutory evidence.
- **Least privilege:** restrict repository and document-store access to authorised people.

## Important security rules

**Do not commit** the following to a public or private Git repository unless a deliberate, risk-reviewed process specifically requires it:

- Identity documents, personal addresses, dates of birth or signatures.
- Bank statements, account numbers, credentials, API keys or access tokens.
- SARS login details, tax reference numbers or unredacted tax returns.
- Payroll records, payslips or employee personal information.
- Unredacted contracts, customer data or commercially sensitive documents.

Store original records in an access-controlled document archive (for example, Paperless-ngx or Nextcloud). In Git, keep templates, procedures, checklists and redacted references. Encrypt backups and test restoration.

## Suggested open-source tooling

| Function | Suggested tool | Purpose |
|---|---|---|
| Document archive | Paperless-ngx | OCR, indexing and retrieval of company records |
| Files and calendar | Nextcloud | Controlled document storage, calendar and reminders |
| Bookkeeping | GnuCash | Double-entry accounting and reconciliations |
| PDF handling | Stirling-PDF | Local PDF manipulation |
| Structured registers (optional) | NocoDB | Track entities, obligations and evidence references |

Tool selection does not determine legal or tax compliance. Configure each system for the company's actual requirements.

## South African compliance references

Use current official guidance and professional advice when determining obligations:

- [CIPC](https://www.cipc.co.za/) — company registration, annual returns and beneficial ownership.
- [Companies Act 71 of 2008](https://www.gov.za/documents/companies-act) — company records, governance and distributions.
- [SARS](https://www.sars.gov.za/) — company income tax, provisional tax, VAT and employer taxes.
- [Department of Employment and Labour](https://www.labour.gov.za/) — employment and UIF guidance.

Requirements depend on the company's facts, financial year, turnover, employees, remuneration and other circumstances. Verify the current rules before filing or making payments.

## Workflow

1. Review `TODO.md`.
2. Complete foundation tasks and attach evidence in the approved document archive.
3. Record the document reference, date, owner and status in the compliance register.
4. Update task status only after the action has been completed and verified.
5. Review outstanding obligations monthly.
6. Review this repository and the compliance calendar at each financial year-end.

## Disclaimer

This repository is an administrative project and general information resource. It is not legal, accounting or tax advice. Have company-specific questions—particularly director remuneration, payroll registration, dividends, VAT and statutory filing obligations—confirmed by a South African accountant, tax practitioner or attorney.
