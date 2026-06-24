**TFI N.° 11 \| Auditoría de Cumplimiento PCI-DSS en una Procesadora de
Tarjetas**

**Organización de referencia:** *Procesadora \"CardProcess S.A.\"
(organización ficticia)*

**Estándar / Marco principal:** *PCI-DSS v4.0.1 --- Requisitos 1, 2, 7 y
10*

*El grupo auditará el cumplimiento del estándar PCI-DSS v4.0.1 en una
procesadora ficticia de transacciones con tarjetas, evaluando el
Cardholder Data Environment (CDE) con foco en red, configuración segura,
control de acceso y monitoreo.*

**CONTEXTO Y ELEMENTOS A CONSTRUIR (organización ficticia)**

1.  1\. Definir el CDE: servidores de procesamiento, base de datos de
    tarjetas y terminales de operación.

2.  2\. Diseñar la red interna del CDE con diagrama de flujo de datos de
    tarjetahabientes.

3.  3\. Crear configuraciones ficticias de dispositivos con
    deficiencias: puertos innecesarios abiertos, credenciales por
    defecto.

4.  4\. Inventar un registro de logs de acceso al CDE de los últimos 30
    días con anomalías ficticias detectables.

**OBJETIVOS DE CONTROL A EVALUAR (3 OC obligatorios)**

El grupo debe desarrollar pruebas de auditoría, papeles de trabajo y
observaciones para cada uno de los siguientes 3 Objetivos de Control:

**OC-1 --- Seguridad Lógica --- Control de Acceso al CDE (PCI-DSS Req. 7
y 8)**

*Verificar que el acceso al Cardholder Data Environment está restringido
a personas y sistemas con necesidad demostrada de negocio, que cada
usuario tiene credenciales individuales y que la autenticación
multifactor está habilitada para accesos remotos al CDE.*

**Pruebas de auditoría requeridas:**

-   Verificar que cada usuario del CDE tiene credenciales individuales
    (no cuentas compartidas).

-   Comprobar que la autenticación multifactor está implementada para
    todos los accesos remotos al CDE (Req. 8.4.2).

-   Verificar que las contraseñas del CDE cumplen los requisitos del
    Req. 8.3 (longitud, complejidad, expiración).

**Normativa de referencia para este OC: PCI-DSS v4.0.1 -- Requisitos 7 y
8**

**OC-2 --- Seguridad en Redes --- Configuración y Segmentación del CDE
(PCI-DSS Req. 1 y 2)**

*Evaluar que la red del CDE está correctamente segmentada del resto de
la infraestructura, que los firewalls tienen configuración restrictiva y
que no existen credenciales de proveedor por defecto en ningún
componente del CDE.*

**Pruebas de auditoría requeridas:**

-   Verificar que el diagrama de red muestra todos los flujos de datos
    del PAN y que el CDE está claramente delimitado.

-   Comprobar que los firewalls aplican regla de \'denegar todo\' el
    tráfico no explícitamente autorizado.

-   Verificar que no existen contraseñas por defecto del fabricante en
    ningún dispositivo del CDE.

**Normativa de referencia para este OC: PCI-DSS v4.0.1 -- Requisitos 1 y
2**

**OC-3 --- Acuerdos de Confidencialidad y Uso Aceptable en el Entorno
del CDE**

*Verificar que todo el personal con acceso al CDE tiene firmados
acuerdos de confidencialidad que cubren los datos de tarjetahabientes, y
que existe una política de uso aceptable de los recursos tecnológicos
del CDE.*

**Pruebas de auditoría requeridas:**

-   Revisar legajo de todo el personal con acceso al CDE: verificar
    firma de acuerdo de confidencialidad.

-   Comprobar que el acuerdo cubre explícitamente la prohibición de
    copia o extracción de datos de tarjeta.

-   Verificar si el personal técnico de proveedores con acceso al CDE
    tiene NDA firmado con la empresa.

**Normativa de referencia para este OC: PCI-DSS v4.0.1 -- Req. 12.8 /
ISO/IEC 27002:2022 -- Controles 6.2, 6.6, 5.19**

**GUÍA DE HALLAZGOS ORIENTATIVOS (no limitativos --- el grupo puede
encontrar otros)**

**✗** Hallazgo OC-2: Dos servidores del CDE utilizan credenciales por
defecto del proveedor (Req. 2.1 -- incumplimiento crítico PCI-DSS).

**✗** Hallazgo OC-1: Los logs de acceso al CDE se conservan solo 3 meses
(Req. 10.7 exige mínimo 12 meses).

**✓** Control adecuado OC-2: El firewall del CDE aplica política de
denegar todo el tráfico no explícitamente autorizado.

**NORMATIVA Y MARCOS APLICABLES**

-   PCI-DSS v4.0.1 -- Requisitos 1, 2, 7, 8 y 10

-   Ley 25.326

-   BCRA Com. A 7724 (referencia)

**ENTREGABLES REQUERIDOS**

  --------------------------------------------------------------------------
  **\#**   **ENTREGABLE**
  -------- -----------------------------------------------------------------
  **1**    Propuesta de Auditoría

  **2**    CEAC + Nivel de Confianza

  **3**    Diagrama del CDE con flujo de datos de tarjetahabientes

  **4**    Registro ficticio de logs con anomalías analizadas

  **5**    Plan y Programa de Auditoría por OC

  **6**    Mínimo 10 PT + PT-OBS adicionales

  **7**    5 a 8 observaciones NCCCE con referencia al Requisito PCI-DSS
           específico

  **8**    3 a 5 controles adecuados

  **9**    Parte A --- Resumen Ejecutivo para Alta Dirección

  **10**   Parte B --- Informe Detallado para Gerente de TI con Hoja de Ruta
           PCI-DSS
  --------------------------------------------------------------------------

**Defensa oral:** 25 minutos + 15 minutos. Cada observación debe citar
el Requisito PCI-DSS exacto y defenderlo ante el docente.
