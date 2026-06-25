# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Contexto del proyecto

Trabajo Final Integrador (TFI N.° 11) de la materia **Auditoría en Sistemas de Información** — UTN-FRT, 4.º año, Ciclo Lectivo 2026.

Auditoría de cumplimiento **PCI-DSS v4.0.1** sobre la empresa ficticia **CardProcess S.A.** (procesadora de pagos, ~500.000 transacciones/mes).

**Firma auditora ficticia:** Holgado, Guzmán & Asociados  
**Equipo:** Holgado Adrián (Líder), Guzmán Mauro Emir (Senior), Chumba Fernando Javier (Especialista Técnico), Gil Fadda Angel (Auditor), Sosa Leandro Martín (Auditor)

---

## Archivos del repositorio

| Archivo | Contenido |
|---|---|
| `TFI_Auditoria_PCI-DSS_CardProcess.md` | **Documento principal** — el TFI completo en Markdown (fuente de verdad) |
| `TFI_Auditoria_PCI-DSS_CardProcess.tex` | Versión LaTeX del mismo documento para exportar PDF con formato académico |
| `TEMA 11 - Tarjetas.md` | Enunciado del TFI asignado (qué hacer, los 3 OC, entregables) |
| `TIG 2026 (1).md` | Consigna general del TIG: metodología de 6 fases, rúbrica, reglas de evaluación |

El `.md` es la fuente principal; el `.tex` debe mantenerse sincronizado cuando cambie el contenido.

---

## Compilar el PDF

```bash
# Desde el directorio del proyecto
pdflatex TFI_Auditoria_PCI-DSS_CardProcess.tex
pdflatex TFI_Auditoria_PCI-DSS_CardProcess.tex  # segunda pasada para referencias y TOC
```

Requiere una instalación de LaTeX (TeX Live o MiKTeX).

---

## Estructura del TFI (6 fases obligatorias)

| Entregable | Fase | Contenido clave |
|---|---|---|
| 1 | Fase 1 | Propuesta de auditoría |
| 2 | Fase 2 | CEAC + Nivel de Confianza (COSO 2013) |
| 3 | Fase 2 | Diagrama del CDE con flujo de datos de tarjetahabientes |
| 4 | Fase 3 | Registro ficticio de logs (30 días) con anomalías |
| 5 | Fase 3 | Plan y Programa de Auditoría por OC |
| 6 | Fase 4 | Mínimo 10 PT + PT-OBS adicionales |
| 7 | Fase 5 | 5 a 8 observaciones con estructura NCCCE |
| 8 | Fase 5 | 3 a 5 controles adecuados documentados |
| 9 | Fase 6 | Parte A — Resumen Ejecutivo (máx. 3 páginas, lenguaje ejecutivo) |
| 10 | Fase 6 | Parte B — Informe Detallado para Gerente de TI con Hoja de Ruta PCI-DSS |

---

## Objetos de Control (OC)

| OC | Denominación | Requisitos PCI-DSS |
|---|---|---|
| OC-1 | Gestión de identidades, accesos y trazabilidad | Req. 7, 8, 10 |
| OC-2 | Seguridad de red, configuración y endurecimiento | Req. 1, 2 |
| OC-3 | Gestión de personal, terceros y aspectos formales | Req. 12.8, ISO 27002:2022 Controles 6.2, 6.6, 5.19 |

---

## Estructura NCCCE de observaciones

Cada observación debe seguir exactamente este esquema:

- **N** — Norma/Criterio: citar el artículo o control PCI-DSS exacto
- **C** — Condición: situación actual encontrada en CardProcess S.A.
- **C** — Consecuencia/Impacto: riesgo real o potencial (cuantificar cuando sea posible)
- **E** — Recomendación: acción concreta con responsable y plazo

---

## Normativa de referencia

- PCI-DSS v4.0.1 — Requisitos 1, 2, 7, 8, 10, 12
- Ley 25.326 (Protección de Datos Personales — Argentina)
- BCRA Comunicación "A" 7724
- ISO/IEC 27002:2022
- COSO 2013 (para clasificación del CEAC)

---

## Reglas del enunciado

- Todo el contenido ficticio (organización, logs, registros, incidentes) debe ser elaborado por el grupo, no generado íntegramente por IA.
- Cada observación debe citar el Requisito PCI-DSS exacto.
- El CEAC, la Matriz de Riesgos (mínimo 8 riesgos) y los PT son obligatorios.
- Primera entrega: **25 de junio de 2026**. Defensa oral: a partir del **2 de julio de 2026**.
