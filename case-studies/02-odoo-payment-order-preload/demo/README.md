# Demo Artifacts

Spanish version: [README.es.md](README.es.md)

These files are 100% synthetic.

They do not come from real suppliers, real invoices, real payments, real Odoo records, real logs, real Excel files, or real accounting data. They are included only to illustrate the design of the workflow described in the case study.

## Files

| file | what it illustrates |
|---|---|
| `sample_payment_input.json` | A fictitious payment preload input before validation. |
| `sample_dry_run_result.json` | A fictitious dry-run result showing what would happen before ERP write. |
| `sample_payment_group_result.json` | A fictitious payment group preparation result. |
| `sample_audit_summary.json` | A fictitious run summary with created, skipped, warning, and error counts. |

## How This Relates To The Architecture

```text
Excel payment input
        |
        v
sample_payment_input.json
        |
        v
Validation and dry-run
        |
        v
sample_dry_run_result.json
        |
        v
Controlled Odoo preparation record + payment group step
        |
        v
sample_payment_group_result.json
        |
        v
Audit summary
        |
        v
sample_audit_summary.json
```

## Privacy Note

All suppliers, references, amounts, journals, payment methods, dates, Odoo references, and audit results are demo values.

Do not use these files to claim production volume, success rate, savings, error reduction, or real operational performance.
