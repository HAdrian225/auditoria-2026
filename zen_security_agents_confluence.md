# Proyecto Zen — Relevamiento de Agentes de Seguridad del Mercado

> **Versión:** 1.0 | **Fecha:** Marzo 2026 | **Clasificación:** Confidencial — Uso Interno

---

## 1. Objetivo

Relevar los principales agentes de seguridad disponibles en el mercado con el objetivo de orientar el diseño y desarrollo del SIEM **Zen**. El análisis cubre cuatro plataformas líderes, detallando sus funcionalidades, base de clientes, certificaciones y modelos de servicio.

---

## 2. Metodología de Relevamiento

El relevamiento se realizó durante **marzo de 2026** utilizando las siguientes fuentes:

- Documentación oficial y páginas de producto de cada vendor
- Informes financieros (SEC filings) de empresas públicas (CrowdStrike, SentinelOne)
- Reportes de analistas: Gartner Magic Quadrant EPP 2025, Forrester Wave XDR Q2 2024
- Evaluaciones independientes: MITRE ATT&CK 2024, AV-TEST, SE Labs
- Plataformas de reviews: Gartner Peer Insights, PeerSpot, G2, Capterra

---

## 3. Agentes de Seguridad Analizados

Se cubrieron cuatro agentes representativos del mercado:

| # | Agente | Tipo | Posicionamiento |
|---|--------|------|-----------------|
| 1 | **CrowdStrike Falcon** | Comercial (SaaS) | Líder de mercado |
| 2 | **SentinelOne Singularity** | Comercial (SaaS) | Challenger premium |
| 3 | **Wazuh** | Open Source / Cloud | Referente open source |
| 4 | **Microsoft Defender for Endpoint** | Comercial (bundled) | Ecosistema Microsoft |

---

## 3.1 CrowdStrike Falcon

**CrowdStrike (NASDAQ: CRWD)** es el líder global en ciberseguridad cloud-native. Su plataforma Falcon utiliza un agente único y liviano que consolida múltiples capacidades. Al cierre del ejercicio fiscal 2026 (enero 2026), reportó un ARR de **USD 5.25 billion** con aproximadamente **29,000 clientes de suscripción activos** y una retención bruta del **97%**.

### Funcionalidades Principales

| Capacidad | Descripción |
|-----------|-------------|
| **EDR / EPP** | Protección de endpoints con agente único. Prevención de malware basada en IA (Static AI + Behavioral AI). Quarantine automático y rollback de ransomware. |
| **XDR** | Falcon XDR correlaciona telemetría de endpoints, red, identidad y nube. Genera gráficos de ataque automáticos. |
| **Next-Gen SIEM** | Ingesta de datos de terceros (hasta 1 PB/día). Charlotte AI: asistente IA generativa para threat hunting en lenguaje natural. |
| **Threat Intelligence** | Datos de más de 200 adversarios rastreados. IOC management, threat feeds y correlación en tiempo real. |
| **Identity Protection** | Falcon ITDR: protección contra credential theft, pass-the-hash, Kerberoasting y lateral movement desde AD/AAD. |
| **Cloud Security** | CNAPP + CWPP. Agentless scanning para AWS, Azure y GCP. |
| **MDR (Falcon Complete)** | Servicio gestionado 24/7 con SLA de resolución en 1 hora. |
| **IoT / OT** | Módulo XIoT para entornos industriales. |
| **AI Agents** | Charlotte AI AgentWorks: construcción de agentes de IA sin código para flujos de trabajo de seguridad. |

### Base de Clientes

- **~29,000** clientes de suscripción activos (FY2025)
- **ARR: USD 5.25 billion** (FY2026)
- Retención bruta: **97%**
- Presencia en **170+ países**
- Clientes: Fortune 100, agencias gubernamentales, MSSPs

### Certificaciones

| Certificación | Estado |
|---------------|--------|
| ISO/IEC 27001:2022 | ✅ Incluye Falcon SIEM, Charlotte AI, Falcon for IT |
| SOC 2 Type II | ✅ Seguridad, disponibilidad y confidencialidad |
| FedRAMP High | ✅ Mayor nivel de rigor del gobierno EE.UU. |
| PCI DSS | ✅ |
| HIPAA | ✅ |
| GDPR Compliance | ✅ |
| Gartner MQ EPP | ✅ Leader 2025 |
| Forrester Wave XDR | ✅ Leader Q2 2024 |
| MITRE ATT&CK 2024 | ✅ 100% detección |

### Planes de Servicio

| Plan | Descripción | Precio Aprox. |
|------|-------------|---------------|
| **Falcon Go** | Hasta 100 endpoints. NGAV + Device Control. Para SMBs. | ~USD 299.95/año (5 devices) |
| **Falcon Pro** | NGAV + EDR básico. Para empresas medianas. | ~USD 99.99/device/año |
| **Falcon Enterprise** | Pro + Threat Intelligence + Identity. | ~USD 184.99/device/año |
| **Falcon Elite** | Enterprise + Inteligencia premium. | ~USD 224.99/device/año |
| **Falcon Complete** | MDR gestionado 24/7. SLA 1 hora. | Custom |
| **Falcon Flex** | Créditos consumibles en cualquier módulo Falcon. | Custom (contrato anual) |

---

## 3.2 SentinelOne Singularity

**SentinelOne (NYSE: S)** es una plataforma de ciberseguridad impulsada por IA con agente único agnóstico de plataforma (Windows, macOS, Linux, VDI). Fundada en 2013. Leader en el **Gartner Magic Quadrant EPP durante 5 años consecutivos** (hasta 2025) y **100% detección en MITRE ATT&CK 2024**.

### Funcionalidades Principales

| Capacidad | Descripción |
|-----------|-------------|
| **NGAV** | Static AI (pre-ejecución) + Behavioral AI (tiempo real). Bloqueo de fileless attacks y exploits de memoria. |
| **EDR + Storyline™** | Tecnología patentada: construye automáticamente la historia completa del ataque (proceso árbol) sin intervención manual. |
| **XDR** | Correlación de endpoints, red (Ranger), cloud e identidad. Respuesta multi-dominio automatizada. |
| **Threat Hunting** | Deep Visibility: captura telemetría completa. Búsqueda retroactiva de hasta 365 días. |
| **Identity Protection** | Singularity Identity (ex-Attivo): ITDR en tiempo real contra ataques sobre Active Directory. |
| **Cloud Security** | Singularity Cloud: CSPM + CWPP en AWS, Azure y GCP. |
| **MDR (Wayfinder)** | Antes Vigilance. MDR Essentials / MDR Elite con Threat Advisors dedicados. Garantía USD 1M ante brechas no detectadas. |
| **Integraciones** | 100+ integraciones nativas: Splunk, IBM QRadar, Azure Sentinel, ServiceNow, VirusTotal. |

### Base de Clientes

- **Más de 11,000** clientes globales
- Clientes incluyen Fortune 500 y agencias gubernamentales
- Clientes notables: Aston Martin, JetBlue Airways, Havas Group
- ARR superó **USD 500 millones** en FY2024

### Certificaciones

| Certificación | Estado |
|---------------|--------|
| ISO/IEC 27001 | ✅ |
| SOC 2 Type II | ✅ |
| PCI DSS | ✅ |
| HIPAA | ✅ |
| GDPR Compliance | ✅ |
| FedRAMP | ⏳ En proceso |
| AV-TEST (Windows/macOS) | ✅ Certificado |
| SE Labs Enterprise | ✅ Calificación AAA |
| NSS Labs BDS | ✅ Recommended |
| Gartner MQ EPP | ✅ Leader (5 años consecutivos) |
| MITRE ATT&CK 2024 | ✅ 100% sin retrasos |

### Planes de Servicio

| Plan | Características Clave | Precio Aprox. |
|------|-----------------------|---------------|
| **Singularity Core** | NGAV cloud-native. Static AI + Behavioral AI. | ~USD 69.99/endpoint/año |
| **Singularity Control** | Core + Firewall Management + Device Control. | ~USD 79.99/endpoint/año |
| **Singularity Complete** | Control + EDR (Storyline) + Deep Visibility. Retención 14 días. | ~USD 130-160/endpoint/año |
| **Singularity Commercial** | Complete + Identity (ITDR) + MDR (Vigilance). Retención 90 días. | ~USD 190-230/endpoint/año |
| **Singularity Enterprise** | Máximas capacidades + multi-tenant + 365 días retención + TAM. | Custom |
| **Wayfinder MDR** | Add-on MDR para cualquier plan. | ~USD 17-50/endpoint/año adicional |

---

## 3.3 Wazuh

**Wazuh** es la plataforma open source de ciberseguridad más adoptada del mundo, unificando XDR y SIEM en una única solución. Creada en 2015 como fork de OSSEC. Arquitectura modular: agente liviano → Wazuh Manager (análisis) → Indexer (OpenSearch) → Dashboard web. **Costo de licencia: USD 0** para despliegue self-hosted.

### Funcionalidades Principales

| Capacidad | Descripción |
|-----------|-------------|
| **Log Analysis / SIEM** | Recolección y análisis de logs de OS y aplicaciones. Decoders y reglas 100% personalizables. Integración nativa con Elasticsearch/OpenSearch + Kibana. |
| **FIM** | File Integrity Monitoring: monitoreo en tiempo real de cambios en archivos (contenido, permisos, propietario). Clave para PCI DSS y CIS Benchmarks. |
| **Vulnerability Detection** | Correlación de inventario de software contra CVE databases (NVD, Microsoft, Canonical). Alertas automáticas por riesgo. |
| **Security Config. Assessment** | SCA: escaneos contra CIS Benchmarks y políticas de hardening. Alertas con recomendaciones de remediación. |
| **HIDS** | Detección de rootkits, archivos ocultos, procesos cloaked. Análisis de syscalls para detectar anomalías. |
| **Active Response** | Respuestas automáticas: bloqueo de IPs, cuarentena de procesos, ejecución remota de comandos en agentes. |
| **Container Security** | Integración nativa con Docker Engine: monitoreo de imágenes, volúmenes y contenedores en ejecución. |
| **Cloud Monitoring** | AWS (CloudTrail, GuardDuty, S3), Azure y GCP. Alertas y visibilidad de seguridad cloud. |
| **Compliance** | Controles mapeados a PCI DSS, HIPAA, GDPR, NIST 800-53, GPG13, TSC SOC2 e ISO 27001. |
| **MITRE ATT&CK** | Correlación automática de alertas con técnicas del framework. |

### Base de Clientes

- **Más de 100,000** organizaciones enterprise
- Protege **más de 15 millones** de endpoints
- Clientes destacados: **NASA, Salesforce, eBay, Verifone, Walgreens**

### Certificaciones

> ⚠️ Como plataforma open source, Wazuh no posee certificaciones corporativas propias. Sin embargo, el producto está **diseñado para ayudar** a las organizaciones a cumplir con los siguientes estándares:

| Estándar | Soporte en Wazuh |
|----------|-----------------|
| PCI DSS v4.0 | ✅ Controles nativos + dashboards |
| HIPAA | ✅ Controles técnicos + reportes |
| GDPR | ✅ Monitoreo de accesos y datos |
| NIST 800-53 | ✅ Mapeado de controles |
| TSC SOC2 | ✅ Ayuda a implementar controles |
| ISO/IEC 27001 | ✅ Controles técnicos auditables |
| CIS Benchmarks | ✅ SCA nativo |
| GPG13 (UK) | ✅ Protective Monitoring |

### Planes de Servicio

| Plan | Descripción | Precio |
|------|-------------|--------|
| **Open Source (Self-Hosted)** | Descarga y despliegue libre. Sin costo de licencia. Soporte vía comunidad (Slack, GitHub). | **Gratis** |
| **Wazuh Cloud — Small** | Servicio gestionado cloud. Hasta 100 agentes. Storage 30 GB. | Desde ~USD 571/mes |
| **Wazuh Cloud — Medium** | Hasta 500 agentes. Storage 100 GB. Soporte Standard (8/5, SLA 8h). | Contactar ventas |
| **Wazuh Cloud — Large** | Hasta 5,000+ agentes. Storage escalable. Soporte Premium (24/7, SLA 4h). | Contactar ventas |
| **Soporte Standard** | 8/5 para deployments on-premise. SLA 8 horas. | Contactar ventas |
| **Soporte Premium** | 24/7. SLA 4 horas. Para entornos HA. | Contactar ventas |
| **Servicios MSSP/Partner** | Partners Gold y Platinum certificados: SOC 24/7, MDR, desarrollo custom. | Variable |

---

## 3.4 Microsoft Defender for Endpoint

**Microsoft Defender for Endpoint** es la solución EDR/EPP de Microsoft, integrada nativamente en el ecosistema Microsoft 365 y Azure. Evolucionó desde el antivirus gratuito de Windows hacia una plataforma enterprise completa. Su mayor ventaja: integración sin fricciones con Azure AD, Microsoft 365, Intune y Microsoft Sentinel. Named **Leader en Gartner Magic Quadrant EPP 2025** y **Forrester Wave XDR Q2 2024**.

### Funcionalidades Principales

| Capacidad | Descripción |
|-----------|-------------|
| **NGAV** | Protección cloud-delivered, análisis comportamental y ML para malware conocido y desconocido. |
| **EDR** | Telemetría completa del endpoint. Advanced Hunting con KQL. Investigación forense y respuesta automatizada. |
| **Microsoft Defender XDR** | Correlación de endpoints (Defender for Endpoint) + identidades (Defender for Identity) + email (Defender for Office 365) + cloud apps (Defender for Cloud Apps). |
| **TVM** | Threat & Vulnerability Management: descubrimiento continuo, priorización por riesgo real, integración con flujos de remediación. |
| **ASR Rules** | Attack Surface Reduction: bloqueo de comportamientos de alto riesgo, protección de red, control de aplicaciones, firewall gestionado. |
| **AIR** | Automated Investigation & Response: análisis automático de alertas, correlación de evidencia y respuesta autónoma. |
| **Microsoft Sentinel** | SIEM nativo en Azure con KQL, workbooks, playbooks (SOAR) y hunting queries sobre todo el ecosistema Microsoft. |
| **Copilot for Security** | IA generativa para análisis de incidentes, threat hunting y consultas en lenguaje natural. |
| **Threat Experts** | Servicio gestionado: expertos de Microsoft que monitorean el ambiente y alertan proactivamente. |

### Base de Clientes

- **Cientos de millones** de dispositivos protegidos (bundled con Windows y Microsoft 365)
- No publica número de clientes independientes de Defender for Endpoint
- Mayor mindshare en el mercado enterprise dado su bundling con Microsoft 365 E3/E5
- Líder en Gartner Magic Quadrant EPP 2025 y Forrester Wave XDR Q2 2024

### Certificaciones

| Certificación | Estado |
|---------------|--------|
| ISO/IEC 27001 | ✅ |
| SOC 1 Type II | ✅ |
| SOC 2 Type II | ✅ |
| SOC 3 (público) | ✅ |
| FedRAMP High | ✅ |
| DoD IL5 | ✅ |
| PCI DSS | ✅ |
| HIPAA / HITECH | ✅ |
| GDPR | ✅ |
| CSA STAR Level 2 | ✅ |
| Gartner MQ EPP | ✅ Leader 2025 |
| Forrester Wave XDR | ✅ Leader Q2 2024 |
| MITRE ATT&CK 2024 | ✅ 100% protección |

### Planes de Servicio

| Plan | Incluye / Descripción | Precio |
|------|-----------------------|--------|
| **Defender for Business** | Para SMBs (hasta 300 usuarios). NGAV + EDR simplificado. | USD 3/usuario/mes |
| **Defender for Endpoint P1** | NGAV, ASR, Device Control, Web Protection, Firewall. Sin EDR avanzado. | USD 3/usuario/mes |
| **Defender for Endpoint P2** | P1 + EDR completo + Advanced Hunting + TVM + AIR + Threat Experts. 180 días de retención. | USD 5.20/usuario/mes |
| **Microsoft 365 E3** | Incluye Defender P1 + Microsoft 365 Apps + Teams + Exchange + Intune. | USD 36/usuario/mes |
| **Microsoft 365 E5** | Incluye Defender P2 + Defender XDR completo + AAD P2 + Microsoft Sentinel. | USD 57/usuario/mes |
| **P2 Add-on** | Add-on para suscriptores M365 E3/Business Premium. | USD 2.20/usuario/mes adicional |

---

## 4. Cuadro Comparativo

| Criterio | CrowdStrike Falcon | SentinelOne Singularity | Wazuh | Microsoft Defender |
|----------|-------------------|------------------------|-------|-------------------|
| **Tipo** | Comercial (SaaS) | Comercial (SaaS) | Open Source / Cloud | Comercial (bundled) |
| **EDR / XDR** | ✅ Completo | ✅ Completo | ✅ Básico-Avanzado | ✅ Completo |
| **SIEM Nativo** | ✅ Next-Gen SIEM | ✅ Singularity SIEM | ✅ Core SIEM | ✅ Microsoft Sentinel |
| **IA / ML** | ✅ Charlotte AI | ✅ Behavioral AI | ⚠️ Parcial | ✅ Copilot for Security |
| **Threat Hunting** | ✅ Overwatch MDR | ✅ Vigilance/Wayfinder | ✅ Manual + reglas | ✅ Defender Experts |
| **Cloud Security** | ✅ CNAPP, CWPP | ✅ Singularity Cloud | ✅ AWS/Azure/GCP | ✅ Nativo Azure |
| **Código Abierto** | ❌ Propietario | ❌ Propietario | ✅ 100% Open Source | ❌ Propietario |
| **Precio base** | ~USD 99/device/año | ~USD 70/endpoint/año | Gratis (self-hosted) | USD 3/user/mes (P1) |
| **Clientes aprox.** | ~29,000+ | ~11,000+ | ~100,000+ orgs. | Cientos de millones |
| **ISO 27001** | ✅ | ✅ | Ayuda a cumplirla | ✅ |
| **SOC 2 Type II** | ✅ | ✅ | Ayuda a cumplirla | ✅ |
| **FedRAMP** | ✅ High | ⏳ En proceso | N/A | ✅ High |
| **MITRE ATT&CK** | ✅ 100% 2024 | ✅ 100% 2024 | ✅ Mapeado | ✅ 100% 2024 |

---

## 5. Conclusiones y Relevancia para el Proyecto Zen

### 5.1 Arquitectura de Agente Unificado
Todos los competidores convergen en la tendencia de un **agente único y liviano** que reporta a un servidor centralizado. Para Zen, se recomienda adoptar un modelo de agente liviano con capacidad de reporte tanto cloud como on-premise, priorizando la **flexibilidad de despliegue**.

### 5.2 Funcionalidades Diferenciadores
Las capacidades que más diferencian a los líderes:
1. **IA/ML** para detección conductual (Charlotte AI, Behavioral AI)
2. **Contexto automático de ataque** (Storyline de SentinelOne, Attack Graph de CrowdStrike)
3. **Respuesta automatizada y autónoma**

> 💡 **Para Zen**: Incorporar detección basada en reglas + ML desde el inicio, con roadmap hacia respuesta autónoma.

### 5.3 Modelo Open Source como Ventaja Competitiva
Wazuh demuestra que el modelo open source genera una comunidad masiva (+100,000 organizaciones). Sin embargo, presenta brechas en soporte enterprise y capacidades de IA.

> 💡 **Para Zen**: Posicionamiento **open-core** — núcleo open source + capacidades avanzadas (IA, correlación, respuesta) como producto comercial.

### 5.4 Certificaciones como Requisito de Mercado
ISO/IEC 27001, SOC 2 Type II y FedRAMP son certificaciones mínimas esperadas por clientes enterprise.

> 💡 **Para Zen**: Incluir en el roadmap SOC 2 Type II e ISO 27001 desde etapas tempranas. Diseñar controles técnicos alineados a PCI DSS e HIPAA desde el inicio.

### 5.5 Modelos de Pricing de Referencia
El mercado opera principalmente con **pricing por endpoint por año**:
- Rango market: USD 70 — USD 230+ por endpoint/año (planes comerciales)
- Microsoft introduce bundling con el ecosistema existente
- Wazuh introduce el benchmark de cero costo de licencia

> 💡 **Para Zen**: Un modelo **freemium** (open source gratuito) con planes de valor agregado podría ser competitivo frente a los jugadores comerciales.

---

## 6. Referencias

- CrowdStrike Holdings, Inc. — SEC Filings FY2025/FY2026. [ir.crowdstrike.com](https://ir.crowdstrike.com)
- CrowdStrike Falcon Platform — Documentación oficial. [crowdstrike.com](https://crowdstrike.com)
- SentinelOne Singularity Platform — Documentación y pricing. [sentinelone.com](https://sentinelone.com)
- Wazuh — Documentación oficial y GitHub. [wazuh.com](https://wazuh.com) / [github.com/wazuh](https://github.com/wazuh/wazuh)
- Microsoft Defender for Endpoint — Microsoft Docs. [learn.microsoft.com](https://learn.microsoft.com/en-us/defender-endpoint)
- Gartner Magic Quadrant for Endpoint Protection Platforms — Julio 2025
- Forrester Wave: Extended Detection and Response Platforms — Q2 2024
- MITRE ATT&CK Evaluations — Enterprise 2024
- CheckThat.ai — SentinelOne Pricing Analysis (Feb. 2026)
- Devoteam — Wazuh XDR Platform Analysis (Nov. 2024)
- Sirius Open Source — Unbiased Review of Wazuh Platform

---

*Documento preparado por el equipo de desarrollo Zen — Confidencial, uso interno únicamente.*
