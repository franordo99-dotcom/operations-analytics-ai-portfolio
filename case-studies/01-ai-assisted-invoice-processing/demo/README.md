# Demo Artifacts

These files are 100% synthetic.

They do not come from real invoices, real suppliers, real ERP records, real logs, real SQLite databases, or real audit outputs. They are included only to illustrate the design of the workflow described in the case study.

## Files

| file | what it illustrates |
|---|---|
| `sample_invoice_payload.json` | A fictitious parsed invoice payload after PDF/OCR/AI-assisted extraction. |
| `sample_staging_record.json` | A fictitious staging record showing how parsed data could be held before ERP write. |
| `sample_audit_result.json` | A fictitious post-load audit result for a draft vendor bill. |

## How This Relates To The Architecture

```text
PDF / Telegram / Local folder
        |
        v
Parser + OCR/AI fallback
        |
        v
sample_invoice_payload.json
        |
        v
SQLite staging
        |
        v
sample_staging_record.json
        |
        v
Validation / human review
        |
        v
Odoo draft vendor bill
        |
        v
sample_audit_result.json
```

## Privacy Note

All names, tax IDs, document numbers, amounts, Odoo references, timestamps, and file paths are demo values.

Do not use these files to claim production volume, parser accuracy, success rate, savings, or real operational performance.
