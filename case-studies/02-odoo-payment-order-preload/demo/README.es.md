English version: [README.md](README.md)

# Artefactos Demo

Estos archivos son 100% sintéticos.

No provienen de proveedores reales, facturas reales, pagos reales, registros reales de Odoo, logs reales, archivos Excel reales ni datos contables reales. Se incluyen únicamente para ilustrar el diseño del workflow descrito en el case study.

## Archivos

| archivo | qué ilustra |
|---|---|
| `sample_payment_input.json` | Input ficticio de precarga de pago antes de validación. |
| `sample_dry_run_result.json` | Resultado ficticio de dry-run que muestra qué ocurriría antes de escribir en ERP. |
| `sample_payment_group_result.json` | Resultado ficticio de preparación de grupo de pago. |
| `sample_audit_summary.json` | Resumen ficticio de corrida con conteos de creados, omitidos, advertencias y errores. |

## Relación Con La Arquitectura

```text
Input Excel de pagos
        |
        v
sample_payment_input.json
        |
        v
Validación y dry-run
        |
        v
sample_dry_run_result.json
        |
        v
Registro de preparación controlado en Odoo + grupo de pago
        |
        v
sample_payment_group_result.json
        |
        v
Resumen de auditoría
        |
        v
sample_audit_summary.json
```

## Nota De Privacidad

Todos los proveedores, referencias, importes, diarios, métodos de pago, fechas, referencias de Odoo y resultados de auditoría son valores demo.

No usar estos archivos para afirmar volumen productivo, tasa de éxito, ahorros, reducción de errores ni performance operativa real.
