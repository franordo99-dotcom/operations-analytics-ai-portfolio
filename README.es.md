# Portfolio de Operations Analytics e IA

English version: [README.md](README.md)

Este portfolio presenta case studies seleccionados y sanitizados en la intersección entre operaciones, procurement, supply chain, workflows ERP, mejora de procesos, análisis de datos, automatización e IA aplicada.

Está pensado para recruiters, hiring managers y equipos que buscan un perfil híbrido: alguien que entiende problemas operativos, puede estructurar workflows desordenados y usa datos, sistemas e IA de forma pragmática sin quitar control de negocio.

Para un perfil breve, ver [About](ABOUT.es.md). Para el enfoque de trabajo detrás de los casos, ver [Metodología](docs/methodology.es.md).

## Foco profesional

Soy Ingeniero Industrial con experiencia en procurement, operaciones, workflows ERP, control de costos, mejora de procesos, análisis de datos y automatización con IA aplicada.

Este portfolio no es un archivo crudo de chats, scripts ni documentos internos. Es una vista pública y curada de cómo convierto fricción operativa en workflows controlados y revisables.

## Qué demuestra este portfolio

- Convertir workflows operativos desordenados en sistemas estructurados.
- Aplicar IA de forma pragmática en procesos reales de negocio.
- Diseñar automatización human-in-the-loop en lugar de automatización ciega.
- Trabajar con workflows ERP / Odoo y datos operativos.
- Construir mejoras de proceso auditables y seguras para privacidad.
- Comunicar valor de negocio sin exponer datos sensibles.

## Tracks del portfolio

Tracks publicados:

- **Procure-to-Pay Automation**: preparación de órdenes de compra, procesamiento de facturas, preparación de pagos y soporte de retenciones / workflow fiscal legacy.
- **CRM / Sales Operations Automation**: intake de leads desde Gmail/formulario web, auditoría/staging en Google Sheets y creación de leads en Odoo CRM.

Posibles tracks futuros:

- **Procurement Analytics**
- **Operations Intelligence**

Estos tracks futuros todavía no están publicados; indican hacia dónde podría expandirse el portfolio.

## Mapa de case studies

| Case study | Área de negocio | Problema principal | Métodos | Señal para recruiter |
|---|---|---|---|---|
| [Human-in-the-Loop Purchase Order Preload into Odoo](case-studies/03-human-in-the-loop-purchase-order-preload/README.es.md) | Procurement operations | Preparar órdenes de compra desde insumos de compra sin quitar aprobación humana | Preparación asistida con Codex, resolución de maestros, preload draft en Odoo, validación dry-run | Operaciones asistidas por IA, criterio ERP, control human-in-the-loop |
| [AI-Assisted Invoice Processing for Procurement Operations](case-studies/01-ai-assisted-invoice-processing/README.es.md) | Procurement / cuentas a pagar | Convertir facturas no estructuradas en borradores ERP controlados | OCR/IA, staging SQLite, validación, draft vendor bills en Odoo | IA aplicada, diseño de procesos, trazabilidad, controles AP |
| [Risk-Controlled Payment Preparation Workflow in Odoo](case-studies/02-odoo-payment-order-preload/README.es.md) | Cuentas a pagar / P2P | Preparar registros de pago sin escrituras ERP descontroladas | Dry-run, validación, control de duplicados, workflow de pagos en Odoo, auditoría | Control financiero operativo, automatización ERP, manejo de excepciones |
| [Legacy Tax Workflow Automation with Odoo and SICORE](case-studies/04-legacy-tax-workflow-automation/README.es.md) | Tax operations / sistemas legacy | Dar soporte a retenciones en un sistema desktop legacy sin API moderna | Extracción Odoo XML-RPC, archivos fixed-width, workbook de control, UI Win32 asistida | Automatización legacy, pensamiento RPA, diseño con control de riesgo |
| [CRM Lead Intake Automation with Gmail, Sheets and Odoo](case-studies/05-crm-lead-intake-automation/README.md) | CRM / Sales Operations | Convertir emails de formulario web en leads trazables de CRM sin prometer omnicanalidad completa | Gmail, Google Apps Script, Google Sheets audit/staging, Odoo CRM, deduplicación | Automatización CRM, Sales Ops, calidad de datos, intake controlado de leads |

Nota: el quinto case study está publicado por ahora en inglés. La versión completa en español puede agregarse en una tarea posterior.

## Cómo leer los case studies

Cada case study es una versión pública y sanitizada de un workflow o MVP. El foco está en:

- el problema de negocio;
- el contexto operativo;
- el diseño del proceso;
- los puntos de control;
- las herramientas y métodos usados;
- el impacto cualitativo;
- la señal profesional para recruiters.

Los archivos demo incluidos en este repositorio son sintéticos y se usan solo para ilustrar la estructura de los workflows. No representan facturas, proveedores, clientes, registros ERP, importes, credenciales ni datos reales de empresa.

## Privacidad y anonimización

Todo el contenido público está curado con foco en privacidad. Este repositorio no publica datos reales de empresa, clientes, proveedores, facturas, credenciales, API keys, documentos internos, logs, bases de datos ni capturas privadas.

Algunos casos están basados en workflows operativos reales, pero fueron adaptados para una publicación segura. Todos los datos demo son sintéticos.

Para más detalle, ver [Privacidad de Datos](docs/data-privacy.es.md).
