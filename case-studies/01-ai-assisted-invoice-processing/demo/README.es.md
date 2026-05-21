English version: [README.md](README.md)

# Artefactos Demo

Estos archivos son 100% sintéticos.

No provienen de facturas reales, proveedores reales, registros reales de ERP, logs reales, bases SQLite reales ni auditorías reales. Se incluyen únicamente para ilustrar el diseño del workflow descrito en el case study.

## Archivos

| archivo | qué ilustra |
|---|---|
| `sample_invoice_payload.json` | Payload ficticio de una factura parseada después de extracción PDF/OCR/IA. |
| `sample_staging_record.json` | Registro ficticio de staging que muestra cómo podrían retenerse datos parseados antes de escribir en ERP. |
| `sample_audit_result.json` | Resultado ficticio de auditoría post-carga para una factura de proveedor en draft. |

## Relación Con La Arquitectura

```text
PDF / Telegram / carpeta local
        |
        v
Parser + fallback OCR/IA
        |
        v
sample_invoice_payload.json
        |
        v
Staging SQLite
        |
        v
sample_staging_record.json
        |
        v
Validación / revisión humana
        |
        v
Factura de proveedor draft en Odoo
        |
        v
sample_audit_result.json
```

## Nota De Privacidad

Todos los nombres, identificadores fiscales, números de documento, importes, referencias de Odoo, timestamps y rutas son valores demo.

No usar estos archivos para afirmar volumen productivo, precisión del parser, tasa de éxito, ahorros ni performance operativa real.
