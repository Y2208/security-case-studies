# 🔍 Audit 01 — Software Compliance Audit / Auditoría de Cumplimiento de Software

> **Year / Año:** 2025  
> **Category / Categoría:** Software Security Audit  
> **Status / Estado:** ✅ Completed / Completada  
> **Severity / Severidad:** 🟡 Medium / Media

---

## 📋 Overview / Descripción General

**EN:** Security audit focused on identifying unauthorized software installations, outdated application versions, and non-compliance with organizational software policies across all managed endpoints.

**ES:** Auditoría de seguridad enfocada en identificar instalaciones de software no autorizado, versiones desactualizadas de aplicaciones e incumplimiento de políticas organizacionales de software en todos los endpoints administrados.

---

## 🎯 Objectives / Objetivos

**EN:**
- Identify unauthorized or unlicensed software installed on endpoints
- Detect outdated software versions that represent a security risk
- Verify compliance with the organization's software usage policies
- Generate recommendations to reduce the software attack surface

**ES:**
- Identificar software no autorizado o sin licencia instalado en los endpoints
- Detectar versiones desactualizadas de software que representen un riesgo de seguridad
- Verificar el cumplimiento de las políticas de uso de software de la organización
- Generar recomendaciones para reducir la superficie de ataque de software

---

## 🛠️ Tools Used / Herramientas Utilizadas

![Kaspersky](https://img.shields.io/badge/Kaspersky_Security_Center-006D5C?style=flat-square&logo=kaspersky&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Goverlan](https://img.shields.io/badge/Goverlan-0078D4?style=flat-square&logoColor=white)

| Tool / Herramienta | Purpose / Uso |
|---|---|
| **Kaspersky Security Center 15.1** | Endpoint inventory & software registry / Inventario de endpoints y registro de software |
| **Goverlan** | Remote endpoint inspection & software enumeration / Inspección remota y enumeración de software |
| **Microsoft Excel** | Data consolidation & reporting / Consolidación de datos e informes |

---

## 🔬 Methodology / Metodología

**EN:**
1. **Inventory collection** — Extracted full software inventory from all managed endpoints via Kaspersky Security Center and Goverlan
2. **Policy comparison** — Compared installed software against the organization's authorized software list
3. **Version analysis** — Identified applications running outdated or end-of-life versions
4. **Risk classification** — Categorized findings by severity (High / Medium / Low)
5. **Reporting** — Documented findings and generated recommendations for remediation

**ES:**
1. **Recolección de inventario** — Extracción del inventario completo de software de todos los endpoints mediante Kaspersky Security Center y Goverlan
2. **Comparación con políticas** — Comparación del software instalado con la lista de software autorizado por la organización
3. **Análisis de versiones** — Identificación de aplicaciones con versiones desactualizadas o sin soporte
4. **Clasificación de riesgos** — Categorización de hallazgos por severidad (Alta / Media / Baja)
5. **Reporte** — Documentación de hallazgos y generación de recomendaciones de remediación

---

## 📊 Key Findings / Hallazgos Principales

> *Details anonymized / Detalles anonimizados*

| Finding / Hallazgo | Severity / Severidad | Status / Estado |
|---|---|---|
| Unauthorized software detected on endpoints | 🔴 High / Alta | ✅ Remediated |
| Outdated application versions identified | 🟡 Medium / Media | ✅ Remediated |
| Software policy non-compliance found | 🟡 Medium / Media | ✅ Remediated |

---

## ✅ Recommendations / Recomendaciones

**EN:**
- Implement an automated software whitelist policy through Kaspersky Security Center
- Establish a monthly patch management cycle for all critical applications
- Define and enforce a formal software usage policy across all departments
- Schedule quarterly software audits to maintain compliance

**ES:**
- Implementar una política de lista blanca de software automatizada a través de Kaspersky Security Center
- Establecer un ciclo mensual de gestión de parches para todas las aplicaciones críticas
- Definir y aplicar una política formal de uso de software en todos los departamentos
- Programar auditorías de software trimestrales para mantener el cumplimiento

---

## 📚 Lessons Learned / Lecciones Aprendidas

**EN:** This audit highlighted the importance of continuous endpoint monitoring and proactive software policy enforcement. The combination of Kaspersky Security Center and Goverlan proved effective for comprehensive software visibility across all managed devices.

**ES:** Esta auditoría destacó la importancia del monitoreo continuo de endpoints y la aplicación proactiva de políticas de software. La combinación de Kaspersky Security Center y Goverlan demostró ser efectiva para una visibilidad completa del software en todos los dispositivos administrados.

---

## 📎 Documentation / Documentación

- 📄 [Full Audit Report (PDF)](./software-audit-2025.pdf) ← *Sube aquí tu documento anonimizado*

---

## 🔗 References / Referencias

- [Kaspersky Security Center Documentation](https://support.kaspersky.com/KSC/15.1/en-US/)
- [NIST Software Asset Management](https://www.nist.gov/)
- [CIS Controls — Software Asset Management](https://www.cisecurity.org/controls/)

---

*All organizational data has been anonymized. / Todos los datos organizacionales han sido anonimizados.*
