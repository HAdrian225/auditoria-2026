El Estándar de Seguridad de Datos de Payment Card Industry (PCI DSS) proporciona una base de requisitos técnicos y operativos, organizados en 12 requisitos principales y requisitos de seguridad detallados. PCI DSS ha sido desarrollada para asegurar los datos del titular de la tarjeta que son almacenados, procesados y/o transmitidos por comerciantes, proveedores de servicios y otras organizaciones (denominadas, colectivamente, "organizaciones" en lo sucesivo). Por su carácter integral, PCI DSS proporciona una gran cantidad de información sobre seguridad, tanta que algunos responsables de la seguridad de los datos del titular de la tarjeta pueden preguntarse por dónde empezar. Con este fin, PCI Security Standards Council ofrece el Enfoque Prioritario para ayudar a las organizaciones a comprender cómo pueden reducir el riesgo en una fase más temprana de su recorrido por PCI DSS. 

## **¿Qué es el Enfoque Prioritario?** 

El Enfoque Prioritario asigna todos los requisitos PCI DSS en seis hitos de seguridad basados en los riesgos destinados a ayudar a las organizaciones a protegerse de manera incremental contra los factores de mayor riesgo y las amenazas crecientes mientras se encuentran en el camino hacia la conformidad PCI DSS. Ningún hito único en el Enfoque Prioritario proporciona una seguridad integral, pero seguir sus directrices ayudará a las organizaciones a proteger los datos del titular de la tarjeta con mayor rapidez. El Enfoque Prioritario y sus hitos (descritos en la página 2) están destinados a proporcionar los siguientes beneficios: 

- Proporciona una hoja de ruta que una organización puede utilizar para abordar sus riesgos en orden de prioridad 

- Permite obtener "victorias rápidas" utilizando un enfoque pragmático 

- Apoya la planificación financiera y operativa 

## **ASPECTOS DESTACADOS** 

   - Ayuda a las organizaciones a identificar los objetivos de mayor riesgo. 

   - Crea un lenguaje común en torno a los esfuerzos de implementación y evaluación de PCI DSS. 

   - Permite a las organizaciones demostrar el progreso de conformidad. 

- Promueve indicadores de progreso objetivos y medibles 

- Ayuda a promover la consistencia entre los asesores 

## **Objetivos del Enfoque Prioritario** 

El Enfoque Prioritario proporciona una hoja de ruta de los requisitos PCI DSS basados en el riesgo asociado con el almacenamiento, el procesamiento y/o la transmisión de datos del titular de la tarjeta. La hoja de ruta ayuda a las organizaciones a priorizar los esfuerzos para lograr la conformidad, establecer hitos y reducir el riesgo de infracciones a los datos del titular de la tarjeta en la fase más temprana del proceso de conformidad. Además, la hoja de ruta ayuda a los adquirentes a medir objetivamente las actividades de conformidad y la reducción de riesgos de las organizaciones. El Enfoque Prioritario se desarrolló después de revisar los datos de las infracciones reales y los comentarios de los Asesores de Seguridad Cualificados, los investigadores forenses y la Junta de Asesores de PCI Security Standards Council. La hoja de ruta no pretende ser un sustituto, un atajo o un enfoque provisional para la conformidad PCI DSS, ni es un marco único aplicable a todas las organizaciones. 

Las preguntas sobre el uso del Enfoque Prioritario y cómo el uso del Enfoque Prioritario puede afectar a las obligaciones de conformidad de una organización deben dirigirse a su adquirente o a las marcas de pago ante las que una organización informa conformidad. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

1 

## **Hitos para Priorizar los Esfuerzos de Conformidad PCI DSS** 

El Enfoque Priorizado incluye seis hitos. La siguiente tabla resume los objetivos de alto nivel de cada hito. 

## **LA CONFORMIDAD PCI DSS ES UN PROCESO CONTINUO** 

|**Hito**|**Objetivos**|
|---|---|
|**1**|**No almacenar datos de autenticación sensibles y limitar la retención**<br>**de datos de tarjetahabiente.**Este hito se dirige a un área clave de riesgo<br>para las entidades que se han visto comprometidas. Recuerde: si no se<br>almacenan datos de autenticación sensibles y otros datos del titular de la<br>tarjeta los efectos de un compromiso se reducirán en gran medida. Si no lo<br>necesita,no lo almacene.|
|**2**|**Proteja los sistemas y las redes y esté preparado para responder a**<br>**una infracción del sistema.**Este hito tiene como objetivo los controles de<br>los puntos de acceso a la mayoría de los compromisos y a los procesos de<br>respuesta.|
|**3**|**Aplicaciones de pago seguras.**Este hito se dirige a los controles de las<br>aplicaciones, los procesos de aplicación y los servidores de aplicaciones.<br>Los puntos débiles en estas áreas son presa fácil para comprometer los<br>sistemasyobtener acceso a los datos de tarjetahabiente.|
|**4**|**Supervise y controle el acceso a sus sistemas.**Los controles de este<br>hito le permiten detectar el quién, el qué, el cuándo y el cómo en relación<br>con el acceso a su redyal entorno de datos de tarjetahabiente.|
|**5**|**Proteger los datos de tarjetahabiente almacenados.**Para aquellas<br>organizaciones que han analizado sus procesos de negocio y han<br>determinado que deben almacenar Números de Cuenta Primarios, este<br>hito se centra en los mecanismos de protección clave para los datos<br>almacenados.|
|**6**|**Finalice los esfuerzos de conformidad restantes y asegúrese de que**<br>**todos los controles están implementados.**Este hito completa los<br>requisitos PCI DSS y finaliza todas las políticas, procedimientos y<br>procesos relacionados restantes necesarios para proteger el entorno de<br>datos de tarjetahabiente.|



## **Descargo de Responsabilidad** 

Este documento no modifica ni reduce a PCI DSS ni a ninguno de sus requisitos y puede ser modificado sin previo aviso. 

PCI SSC no se hace responsable de los errores o daños de cualquier tipo resultantes del uso de la información aquí contenida. PCI SSC no ofrece ninguna garantía o representación en relación con la información proporcionada en este documento, y no asume ninguna responsabilidad en relación con el uso o el mal uso de dicha información. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

2 

## **Asignación de los Hitos del Enfoque Priorizado a los Requisitos de PCI DSS v4.0.1** 

El resto de este documento asigna los hitos a cada requisito y Sub-requisito PCI DSS v4.0.1. Tenga en cuenta que los requisitos PCI DSS v4.0.1 en la siguiente sección no incluyen las Notas de Aplicabilidad y otra información importante que se encuentra en PCI DSS. Las Notas de Aplicabilidad incluyen información que puede afectar a la interpretación de un requisito y se consideran una parte integral de PCI DSS que debe ser considerada en su totalidad durante una evaluación. 

_Las Notas de Aplicabilidad también indican los requisitos que son nuevos en PCI DSS v4.0.1 y que son las mejores prácticas hasta el 31 de marzo de 2025. Estos nuevos requisitos se indican con la siguiente nota: “Este Requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025; consulte las Notas de Aplicabilidad en PCI DSS para más detalles” en la tabla siguiente._ 

## _**Se insta a las organizaciones a consultar a PCI DSS v4.0.1 para ver las Notas de Aplicabilidad y otra información importante incluida en ella.**_ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

3 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|

**----- End of picture text -----**<br>


**Requisito 1: Instalar y Mantener los Controles de Seguridad de la Red** 

**1.1** Se definen y comprenden los procesos y mecanismos para instalar y mantener los controles de seguridad de la red. 

**==> picture [498 x 493] intentionally omitted <==**

**----- Start of picture text -----**<br>
||||
|---|---|---|
|1.1.1|Todas las políticas de seguridad y los procedimientos operativos que|6|
|se identifican en el Requisito 1 son:|
|• Documentados.|
|• Actualizados.|
|• En uso.|
|• Conocidos por todas las partes involucradas.|
|1.1.2|Los roles y responsabilidades para realizar las actividades del|6|
|Requisito 1 están documentados, asignados y comprendidos.|
|Se configuran y mantienen los controles de seguridad de la red (NSC).|
|1.2.1|Los estándares de configuración para el conjunto de reglas de los|2|
|NSC son:|
|• Definidos.|
|• Implementados.|
|• Mantenida.|
|1.2.2|Todos los cambios en las conexiones de red y en las configuraciones|6|
|de los NSC se aprueban y gestionan de acuerdo con el proceso de control|
|de cambios definido en el Requisito 6.5.1.|
|1.2.3|Se mantienen los diagramas de red precisos que muestran todas las|1|
|conexiones entre el CDE y otras redes, incluyendo las redes inalámbricas.|
|1.2.4|Se mantienen diagramas de flujo de datos precisos que cumplen con|1|
|lo siguiente:|
|• Muestran todos los flujos de datos del titular de la tarjeta a través de  Muestran todos los flujos de datos del titular de la tarjeta a través de|
|sistemas y redes.|
|• Se actualizan según sea necesario ante cambios en el entorno.|
|1.2.5|Todos los servicios, protocolos y puertos permitidos están|2|
|identificados, aprobados y tienen una necesidad de negocio definida.|
|1.2.6|Las configuraciones de seguridad son definidas e implementadas|2|
|para todos los servicios, protocolos y puertos que están en uso y que son|
|considerados inseguros, de tal manera que el riesgo es mitigado.|

**----- End of picture text -----**<br>


**1.2** Se configuran y mantienen los controles de seguridad de la red (NSC). 

- Muestran todos los flujos de datos del titular de la tarjeta a través de  Muestran todos los flujos de datos del titular de la tarjeta a través de sistemas y redes. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

4 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**1.2.7**Las configuraciones de los NSC se revisan al menos una vez cada<br>seis meses para confirmar que son relevantes y eficientes.||||||6|
|**1.2.8**Los archivos de configuración de los NSC están:<br>•Asegurados contra el acceso no autorizado.<br>•Se mantienen consistentes con las configuraciones de red activas.||2|||||
|**1.3**El acceso a la red hacia y desde el entorno de datos de tarjetahabiente está<br>restringido.|||||||
|**1.3.1**El tráfico de entrada al CDE está restringido de la siguiente manera:<br>•Sólo al tráfico necesario.<br>•Todo el resto del tráfico está específicamente denegado.||2|||||
|**1.3.2**El tráfico saliente del CDE se restringe de la siguiente manera:<br>•Sólo al tráfico necesario.<br>•Todo el resto del tráfico está específicamente denegado.||2|||||
|**1.3.3**Los NSC se implementan entre todas las redes inalámbricas y el<br>CDE; esto es independientemente de que la red inalámbrica sea parte CDE<br>o no, de manera que:<br>•Todo el tráfico inalámbrico de las redes inalámbricas hacia el CDE es<br>denegado de forma explícita.<br>•Sólo se permite el tráfico inalámbrico al CDE que tenga un propósito de<br>negocio autorizado.||2|||||
|**1.4**Se controlan las conexiones de red entre las redes fiables y las que no lo<br>son.|||||||
|**1.4.1**Los NSC se implementan entre redes confiables y no confiables.||2|||||
|**1.4.2**El tráfico entrante de redes que no son confiables a redes confiables<br>está restringido a:<br>•Las comunicaciones con componentes del sistema autorizados para<br>proveer servicios de acceso público, protocolos y puertos.<br>•Respuestas las comunicaciones previamente iniciadas por componentes<br>del sistema en una red confiable, esto para protocolos con dicho<br>comportamiento.<br>•Todo el tráfico restante está denegado.||2|||||
|**1.4.3**Se implementan medidas_Antispoofing_para detectar y bloquear la<br>entrada a la red confiable de direcciones IP origen falsas o suplantadas.||2|||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

5 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**1.4.4**Los componentes del sistema que almacenan datos de||2|||||||
|tarjetahabiente no son accesibles directamente desde redes no confiables.|||||||||
|**1.4.5**La divulgación de las direcciones IP internas y la información de||2|||||||
|enrutamiento se limita sólo a las partes autorizadas.|||||||||
|**1.5**Se mitigan los riesgos para el CDE desde dispositivos informáticos que|||||||||
|pueden conectarse tanto a redes no confiables como al CDE.|||||||||
|**1.5.1**Los controles de seguridad se implementan en cualquier dispositivo||2|||||||
|informático, incluyendo los dispositivos propiedad de la empresa y de los|||||||||
|empleados, que se conectan tanto a redes no confiables (incluida Internet)|||||||||
|como al CDE manera siguiente:|||||||||



- Se definen los parámetros de configuración específicos para impedir que se introduzcan amenazas en la red de la entidad. 

- Los controles de seguridad se están ejecutando activamente. 

- Los usuarios de los dispositivos informáticos no pueden alterar los controles de seguridad a menos que estén específicamente documentados y autorizados por el nivel gerencial, caso por caso, durante un período limitado. 

## **Requisito 2: Aplicar Configuraciones Seguras a Todos los Componentes del Sistema** 

**2.1** Se definen y comprenden los procesos y mecanismos para aplicar configuraciones seguras a todos los componentes del sistema. 

|**2.1.1**Todas las políticas de seguridad y los procedimientos operativos que||||||6|
|---|---|---|---|---|---|---|
|se identifican en el Requisito 2 están:|||||||
|•Documentados.|||||||
|•Actualizados.|||||||
|•En uso.|||||||
|•Conocidos por todas las partes involucradas.|||||||
|**2.1.2**Los roles y responsabilidades para realizar las actividades del||||||6|
|Requisito 2 son documentados, asignados y comprendidos.|||||||



- Actualizados. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

6 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>**----- End of picture text -----**<br>


**2.2** Los componentes del sistema se configuran y administran de forma segura. 

**==> picture [390 x 469] intentionally omitted <==**

**----- Start of picture text -----**<br>
||||
|---|---|---|
|2.2.1|Los estándares de configuración se desarrollan, implementan y|2|
|mantienen para:|
|• Cubrir todos los componentes del sistema.  Cubrir todos los componentes del sistema.|
|• Cubrir todas las vulnerabilidades de seguridad conocidas.   Cubrir todas las vulnerabilidades de seguridad conocidas.|
|• Brindar coherencia con los estándares de  Brindar coherencia con los estándares de|hardening|del sistema|
|aceptados por el sector o con las recomendaciones de|hardening|del|
|proveedor.|
|• Ser actualizadas a medida que se identifican nuevos problemas de  Ser actualizadas a medida que se identifican nuevos problemas de|
|vulnerabilidad, como se define en el Requisito 6.3.1.|
|• Ser aplicadas cuando los nuevos sistemas sean configurados y  Ser aplicadas cuando los nuevos sistemas sean configurados y|
|verificadas como establecidas antes o inmediatamente después de que|
|un componente del sistema se conecte a un entorno de producción.|
|2.2.2|Las cuentas predeterminadas del proveedor se gestionan de la|2|
|siguiente manera:|
|• Si se utilizan las cuentas predeterminadas del proveedor, la contraseña  Si se utilizan las cuentas predeterminadas del proveedor, la contraseña|
|predeterminada se cambia según el Requisito 8.3.6.|
|• Si no se van a utilizar las cuentas predeterminadas del proveedor, la  Si no se van a utilizar las cuentas predeterminadas del proveedor, la|
|cuenta se elimina o se desactiva.|
|2.2.3|Las funciones principales que requieren distintos niveles de seguridad|2|
|se manejan como sigue:|
|• Solo existe una función principal en un componente del sistema,  Solo existe una función principal en un componente del sistema,|
|O|
|• Las funciones principales con distintos niveles de seguridad que existen  Las funciones principales con distintos niveles de seguridad que existen|
|en el mismo componente del sistema están aisladas entre sí,|
|O|
|• Las funciones primarias con distintos niveles de seguridad en el mismo  Las funciones primarias con distintos niveles de seguridad en el mismo|
|componente del sistema están todas aseguradas al nivel requerido por|
|la función que requiera un nivel mayor de seguridad.|
|2.2.4|Sólo se habilitan los servicios, protocolos, «demonios» y funciones|2|
|necesarias, y se eliminan o deshabilitan todas las funciones innecesarias.|
|2.2.5|2|

**----- End of picture text -----**<br>


- Cubrir todos los componentes del sistema.  Cubrir todos los componentes del sistema. 

- Cubrir todas las vulnerabilidades de seguridad conocidas.   Cubrir todas las vulnerabilidades de seguridad conocidas. 

- Brindar coherencia con los estándares de  Brindar coherencia con los estándares de _hardening_ del sistema aceptados por el sector o con las recomendaciones de _hardening_ del proveedor. 

- Ser actualizadas a medida que se identifican nuevos problemas de  Ser actualizadas a medida que se identifican nuevos problemas de vulnerabilidad, como se define en el Requisito 6.3.1. 

- Ser aplicadas cuando los nuevos sistemas sean configurados y  Ser aplicadas cuando los nuevos sistemas sean configurados y verificadas como establecidas antes o inmediatamente después de que un componente del sistema se conecte a un entorno de producción. 

- **2.2.2** Las cuentas predeterminadas del proveedor se gestionan de la siguiente manera: 

- Si se utilizan las cuentas predeterminadas del proveedor, la contraseña  Si se utilizan las cuentas predeterminadas del proveedor, la contraseña predeterminada se cambia según el Requisito 8.3.6. 

- Si no se van a utilizar las cuentas predeterminadas del proveedor, la  Si no se van a utilizar las cuentas predeterminadas del proveedor, la cuenta se elimina o se desactiva. 

- Solo existe una función principal en un componente del sistema,  Solo existe una función principal en un componente del sistema, **O** 

- Las funciones principales con distintos niveles de seguridad que existen  Las funciones principales con distintos niveles de seguridad que existen en el mismo componente del sistema están aisladas entre sí, 

- Las funciones primarias con distintos niveles de seguridad en el mismo  Las funciones primarias con distintos niveles de seguridad en el mismo componente del sistema están todas aseguradas al nivel requerido por la función que requiera un nivel mayor de seguridad. 

## **2.2.5** Si existen servicios, protocolos o «demonios» inseguros: 

- La justificación de negocio está documentada. 

- Se documentan e implementan características de seguridad adicionales que reducen el riesgo de utilizar servicios, protocolos o «demonios» inseguros. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

7 

**==> picture [498 x 108] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|
|2.2.6|Los parámetros de seguridad del sistema están configurados para|2|
|impedir su uso indebido.|
|2.2.7|Todo el acceso administrativo sin consola está cifrado utilizando|2|
|criptografía robusta.|

**----- End of picture text -----**<br>


**2.3** Los entornos inalámbricos se configuran y administran de forma segura. 

**2.3.1** Para entornos inalámbricos conectados al CDE o que transmiten 2 datos del titular de la tarjeta, todos los valores predeterminados de los proveedores inalámbricos se cambian en la instalación o se confirma que son seguros, incluidos, entre otros: • Claves de cifrado inalámbricas predeterminadas.  Claves de cifrado inalámbricas predeterminadas. • Contraseñas o puntos de acceso inalámbricos.  Contraseñas o puntos de acceso inalámbricos. • Valores predeterminados de SNMP.  Valores predeterminados de SNMP. • Cualquier otro proveedor inalámbrico predeterminado relacionado con la  Cualquier otro proveedor inalámbrico predeterminado relacionado con la seguridad. **2.3.2** Para los entornos inalámbricos conectados al CDE o que transmitan 2 datos del titular de la tarjeta, las claves cifradas inalámbricas se cambian como sigue: 

- Claves de cifrado inalámbricas predeterminadas.  Claves de cifrado inalámbricas predeterminadas. 

- Contraseñas o puntos de acceso inalámbricos.  Contraseñas o puntos de acceso inalámbricos. 

- Valores predeterminados de SNMP.  Valores predeterminados de SNMP. 

- Cualquier otro proveedor inalámbrico predeterminado relacionado con la  Cualquier otro proveedor inalámbrico predeterminado relacionado con la seguridad. 

- Siempre que el personal con conocimiento de la clave deje la empresa o la función para la que era necesario el conocimiento. 

- Siempre que se sospeche o se sepa que una clave está comprometida. 

## **Requisito 3: Proteger los Datos del Titular de la Tarjeta Almacenados** 

**3.1** Se definen y comprenden los procesos y mecanismos para proteger los datos del titular de la tarjeta almacenados. 

**3.1.1** Todas las políticas de seguridad y procedimientos operativos que se 6 identifican en el Requisito 3 son: • Documentados.  Documentados. • Actualizados.  Actualizados. • En uso.  En uso. • Conocidos por todas las partes involucradas.  Conocidos por todas las partes involucradas. **3.1.2** Los roles y responsabilidades para realizar las actividades del 6 Requisito 3 están documentados, asignados y comprendidos. 

- Documentados.  Documentados. 

- Actualizados.  Actualizados. 

- En uso.  En uso. 

- Conocidos por todas las partes involucradas.  Conocidos por todas las partes involucradas. 

**3.2** El almacenamiento de los datos del titular de la tarjeta se mantiene al mínimo. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

8 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>**----- End of picture text -----**<br>


**3.2.1** El almacenamiento de datos del titular de la tarjeta se mantiene al mínimo mediante la implementación de políticas y procedimientos de retención y eliminación de datos que incluyan al menos lo siguiente: 

1 

- Cubren todas las ubicaciones donde hay datos del titular de la tarjeta. 

- Cubren todos los datos de autenticación sensibles (SAD) almacenado antes de completar la autorización. _Este punto es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- Limitar la cantidad de datos almacenados y su tiempo de retención a lo requerido por los requisitos legales o reglamentarios y/o de negocios. 

- Requisitos de retención específicos para los datos del titular de la tarjeta que definen la duración del período de retención e incluyen una justificación de negocio documentada. 

- Procesos para el borrado seguro o para hacer que los datos del titular de la tarjeta sean irrecuperables cuando ya no se necesitan según la política de retención. 

- Un proceso para verificar, al menos una vez cada tres meses, que los datos del titular de la tarjeta que excedan el período de retención definido se han eliminado de forma segura o se han vuelto irrecuperables. 

**3.3** Los datos de autenticación sensibles (SAD) no se almacenan después de la autorización. 

**3.3.1** Los SAD no se almacenan después de la autorización, incluso si están cifrados. Todos los datos de autenticación sensibles recibidos se vuelven irrecuperables una vez finalizado el proceso de autorización. 

- **3.3.1.1** El contenido completo de cualquier pista no se almacena una vez finalizado el proceso de autorización. 

**3.3.1.2** El código de verificación de la tarjeta no se almacena una vez finalizado el proceso de autorización. 

**3.3.1.3** El número de identificación personal (PIN) y el bloque del PIN no se almacenan una vez finalizado el proceso de autorización. 

**3.3.2** Los SAD que se almacenan electrónicamente antes de completar la autorización se cifran mediante criptografía robusta. 

1 1 1 1 1 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

9 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**3.3.3****_Requisito adicional para emisores y empresas que apoyan_**|1||||||||
|**_servicios de emisión y que almacenan datos de autenticación_**|||||||||
|**_sensibles:_**Cualquier almacenamiento de datos de autenticación sensibles|||||||||
|está:|||||||||



- Limitado a lo que se necesita para una necesidad legítima de negocio de emisión y está asegurado. 

|• Limitado a lo que se necesita para una necesidad legítima de negocio deLimitado a lo que se necesita para una necesidad legítima de negocio de|• Limitado a lo que se necesita para una necesidad legítima de negocio deLimitado a lo que se necesita para una necesidad legítima de negocio de<br>emisión y está asegurado.|
|---|---|
|•Cifrado utilizando criptografía robusta.|Cifrado utilizando criptografía robusta._Este punto es la mejor práctica_|
||_recomendada hasta el 31 de marzo de 2025, consulte las Notas de_|
||_Aplicabilidad de PCI DSS para obtener más detalles._|



- **3.4** El acceso a las pantallas de datos PAN completas y la capacidad de copiar los datos PAN están restringidos. 

|**3.4.1**Los datos PAN están enmascarados cuando se muestra (el BIN y los|||||5|
|---|---|---|---|---|---|
|últimos cuatro dígitos**constituyen el número máximo**de dígitos que se||||||
|muestran), de manera que sólo el personal con una necesidad legítima de||||||
|negocio pueda ver**más que**el BIN y los últimos cuatro dígitos de los datos||||||
|PAN.||||||
|**3.4.2**Cuando se utilicen tecnologías de acceso remoto los controles|||||5|
|técnicos impiden la copia y/o la reubicación de los datos PAN para todo el||||||
|personal, excepto para aquellos con autorización explícita y documentada y||||||
|una necesidad legítima de negocio y definida.||||||
|_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_||||||
|_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_||||||
|_detalles._||||||



- **3.5** El número de cuenta principal (PAN) está protegido donde sea que se almacene. 

   - **3.5.1** Los datos PAN se hace ilegible en cualquier lugar donde se almacene 5 utilizando cualquiera de los siguientes enfoques: 

   - _Hashes_ unidireccionales basados en criptografía robusta del PAN completo. 

   - Truncamiento (los _hashes_ no pueden utilizarse para reemplazar el segmento truncado de la PAN). 

      - Si en un entorno hay versiones truncadas y con _hash_ del mismo PAN, o diferentes formatos de truncamiento del mismo PAN, se establecen controles adicionales de manera que las diferentes versiones no puedan correlacionarse para reconstruir el PAN original. 

   - Índice de _tokens._ 

   - Criptografía robusta con procesos y procedimientos de gestión de claves asociados. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

10 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**3.5.1.1**Los_hash_utilizados para hacer ilegibles los datos PAN (según<br>el primer punto del Requisito 3.5.1) son_hashes_criptográficos con clave<br>de todos los datos PAN, con procesos y procedimientos de gestión de<br>claves asociados de acuerdo con los Requisitos 3.6 y 3.7.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles. Este requisito reemplazará el punto del Requisito 3.5.1_<br>_para hashes unidireccionales una vez que se alcance su fecha de_<br>_efectividad._|||||5||
|**3.5.1.2**Si se utiliza un cifrado a nivel de disco o de partición (en lugar<br>de un cifrado de base de datos a nivel de archivo, columna o campo)<br>para hacer que los datos PAN sea ilegibles, sólo se implementará de la<br>siguiente manera:<br>•En medios electrónicos extraíbles<br>**O**<br>•Si se utiliza para medios electrónicos no extraíbles, los datos PAN<br>también se hacen ilegibles mediante otro mecanismo que cumpla<br>con el Requisito 3.5.1.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._|||||5||
|**3.5.1.3**Si se utiliza el cifrado a nivel del disco o de partición (en lugar<br>del cifrado de la base de datos a nivel de archivo, columna o campo)<br>para hacer que los datos PAN sea ilegibles, sólo se implementará de la<br>siguiente manera:<br>•El acceso lógico se gestiona por separado e independientemente de<br>la autenticación del sistema operativo nativo y de los mecanismos<br>de control de acceso.<br>•Las claves de descifrado no están asociadas a las cuentas de<br>usuarios.<br>•Los factores de autenticación (contraseñas, frases de paso o claves<br>criptográficas) que permiten el acceso a los datos no cifrados se<br>almacenan de forma segura.|||||5||



- En medios electrónicos extraíbles 

- Si se utiliza para medios electrónicos no extraíbles, los datos PAN también se hacen ilegibles mediante otro mecanismo que cumpla con el Requisito 3.5.1. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- El acceso lógico se gestiona por separado e independientemente de la autenticación del sistema operativo nativo y de los mecanismos de control de acceso. 

- Las claves de descifrado no están asociadas a las cuentas de usuarios. 

- Los factores de autenticación (contraseñas, frases de paso o claves criptográficas) que permiten el acceso a los datos no cifrados se almacenan de forma segura. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

11 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**3.6**Las claves criptográficas utilizadas para proteger los datos del titular de la<br>tarjeta almacenados están protegidas.|||||||
|**3.6.1**Los procedimientos se definen e implementan para proteger las<br>claves cifradas utilizadas para proteger los datos del titular de la tarjeta<br>almacenados contra la divulgación y el uso indebido que incluyen:<br>•El acceso a las claves está restringido al menor número de custodios<br>necesarios.<br>•Las claves de cifrado de claves son al menos tan seguras como las<br>claves de cifrado de datos que estas protegen.<br>•Las claves de cifrado de claves se almacenan por separado de las<br>claves de cifrado de datos.<br>•Las claves se almacenan de forma segura en el menor número posible<br>de formas y ubicaciones.|||||5||
|**3.6.1.1****_Requisito adicional sólo para proveedores de servicios:_**<br>Se mantiene una descripción documentada de la arquitectura<br>criptográfica que incluye:<br>•Detalles de todos los algoritmos, protocolos y claves utilizados<br>para la protección de los datos del titular de la tarjeta, incluyendo la<br>fuerza de la clave y la fecha de caducidad.<br>•Evitar el uso de las mismas claves criptográficas en entornos de<br>producción y de prueba._Este punto es la mejor práctica_<br>_recomendada hasta el 31 de marzo de 2025, consulte las Notas de_<br>_Aplicabilidad de PCI DSS para obtener más detalles._<br>•Descripción del uso de claves para cada clave.<br>•Inventario de los módulos de seguridad de hardware (HSM),<br>sistemas de gestión de claves (KMS) y otros dispositivos<br>criptográficos seguros (SCD) utilizados para la gestión de claves,<br>incluido el tipo y la ubicación de los dispositivos para apoyar el<br>cumplimiento del Requisito 12.3.4.|||||5||
|**3.6.1.2**Las claves secretas y privadas que se utilizan para proteger<br>los datos del titular de la tarjeta se almacenan en una (o más) de las<br>siguientes formas en todo momento:<br>•Cifrado con una clave de cifrado de clave, que sea al menos tan<br>fuerte, como la clave de cifrado de datos y que se almacene por<br>separado de la clave de cifrado de datos.<br>•Dentro de un dispositivo criptográfico seguro (SCD), como un<br>módulo de seguridad de hardware (HSM) o un dispositivo de punto<br>de interacción aprobado por PTS.<br>•Como mínimo dos componentes clave de longitud completa<br>o recursos compartidos de clave, de acuerdo con un método<br>aceptado por la industria.|||||5||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

12 

**Hito Requisitos de PCI DSS v4.0.1 1 2 3 4 5 6 3.6.1.3** El acceso a los componentes de claves criptográficas de texto 5 no cifrado está restringido al menor número posible de custodios que sean necesarios. **3.6.1.4** Las claves criptográficas se almacenan en el menor número 5 posible de ubicaciones. **3.7** Cuando se usa criptografía para proteger datos del titular de la tarjeta almacenados, se definen e implementan procesos y procedimientos de administración de claves que cubren todos los aspectos del ciclo de vida de las claves. **3.7.1** Las políticas y procedimientos de administración de claves se 5 implementan para incluir la generación de claves criptográficas fuertes utilizadas para proteger los datos del titular de la tarjeta almacenados. **3.7.2** Las políticas y los procedimientos de administración de claves son 5 implementados para incluir la distribución segura de las claves criptográficas utilizadas para proteger los datos del titular de la tarjeta almacenados. **3.7.3** Se implementan políticas y procedimientos de gestión de claves para 5 incluir el almacenamiento seguro de las claves criptográficas utilizadas para proteger los datos del titular de la tarjeta almacenados. **3.7.4** Se implementan políticas y procedimientos de gestión de claves para 5 los cambios de claves criptográficas de para aquellas claves que han llegado al final de su criptoperíodo, según lo definido por el proveedor de la aplicación asociada o el propietario de la clave, y basado en las mejores prácticas y directrices de la industria, incluyendo lo siguiente: • Un criptoperíodo definido para cada tipo de clave en uso. • Un proceso para el cambio de claves al final del criptoperíodo definido. **3.7.5** Los procedimientos de políticas de gestión de claves se implementan 5 para incluir el retiro, sustitución o destrucción de las claves utilizadas para proteger los datos del titular de la tarjeta almacenados, según se considere necesario cuando: 

- La clave haya llegado al final de su criptoperíodo definido. 

- La integridad de la clave se haya debilitado, incluso cuando el personal con conocimiento de un componente de la clave en texto no cifrado abandone la empresa, o la función por la que conocía la clave. 

- Cuando se sospecha o se sabe que las claves están comprometidas. 

- Las claves retiradas o reemplazadas no se utilizan para operaciones de cifrado. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

13 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**3.7.6**Cuando el personal realiza operaciones manuales de gestión de|||||||5||
|claves criptográficas en texto no cifrado, se implementan políticas y|||||||||
|procedimientos de gestión de claves que incluyen la gestión de estas|||||||||
|operaciones utilizando conocimiento dividido y control dual.|||||||||
|**3.7.7**Se implementan políticas y procedimientos de administración de|||||||5||
|claves para incluir la prevención de la sustitución no autorizada de claves|||||||||
|criptográficas.|||||||||
|**3.7.8**Las políticas y los procedimientos de administración de claves se|||||||5||
|implementan para incluir que los custodios de claves criptográficas|||||||||
|reconozcan formalmente (por escrito o electrónicamente) que comprenden|||||||||
|y aceptan sus responsabilidades como custodios de claves.|||||||||
|**3.7.9****_Requisito adicional sólo para proveedores de servicios:_**Cuando|||||||5||
|un proveedor de servicios comparte claves criptográficas con sus clientes|||||||||
|para la transmisión o el almacenamiento de datos del titular de la tarjeta, se|||||||||
|documenta y distribuye a los clientes de los proveedores de servicios|||||||||
|orientación sobre la transmisión, el almacenamiento y la actualización|||||||||
|segura de dichas claves.|||||||||



**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la Transmisión a Través de Redes Abiertas y Públicas** 

|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**<br>**Transmisión a Través de Redes Abiertas y Públicas**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|**Requisito 4: Proteger los Datos de Tarjetahabiente con una Criptografía Robusta Durante la**|
|---|---|---|---|---|---|---|
|**4.1**Los procesos y mecanismos para proteger los datos de tarjetahabiente con|||||||
|criptografía robusta durante la transmisión a través de redes públicas abiertas|||||||
|están definidos y comprendidos.|||||||
|**4.1.1**Todas las políticas de seguridad y procedimientos operativos que se||||||6|
|identifican en el Requisito 4 son:|||||||
|•Documentados.|||||||
|•Actualizados.|||||||
|•En uso.|||||||
|•Conocidos por todas las partes involucradas.|||||||
|**4.1.2**Los roles y responsabilidades para realizar las actividades del||||||6|
|Requisito 4 están documentados, asignados y comprendidos.|||||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

14 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



**4.2** Los datos PAN está protegidos con criptografía robusta durante la transmisión. 

- **4.2.1** Se implementan fuertes protocolos de seguridad y criptografía robusta 2 de la siguiente manera para proteger los datos PAN durante la transmisión a través de redes públicas abiertas: • Sólo se aceptan claves y certificados confiables.  Sólo se aceptan claves y certificados confiables. • Los certificados utilizados para proteger los datos PAN durante la  Los certificados utilizados para proteger los datos PAN durante la transmisión a través de redes públicas abiertas se confirman como válidos y no están vencidos ni revocados. _Este punto es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- • El protocolo en uso sólo apoya versiones o configuraciones seguras y no  El protocolo en uso sólo apoya versiones o configuraciones seguras y no apoya el uso de versiones, algoritmos, tamaños de clave o implementaciones inseguras. 

- • La fuerza del cifrado es apropiada para la metodología de cifrado en  La fuerza del cifrado es apropiada para la metodología de cifrado en uso. **4.2.1.1** Se mantiene un inventario de las claves y certificados 2 confiables de la entidad utilizados para proteger los datos PAN durante la transmisión. _Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ **4.2.1.2** Las redes inalámbricas que transmiten datos PAN o están 2 conectadas al CDE utilizan las mejores prácticas de la industria para implementar criptografía robusta para autenticación y transmisión. 

- **4.2.2** Los datos PAN están protegidos con criptografía robusta siempre que 2 se envíen a través de tecnologías de mensajería para el usuario final. 

- Sólo se aceptan claves y certificados confiables.  Sólo se aceptan claves y certificados confiables. 

- Los certificados utilizados para proteger los datos PAN durante la  Los certificados utilizados para proteger los datos PAN durante la transmisión a través de redes públicas abiertas se confirman como válidos y no están vencidos ni revocados. _Este punto es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- El protocolo en uso sólo apoya versiones o configuraciones seguras y no  El protocolo en uso sólo apoya versiones o configuraciones seguras y no apoya el uso de versiones, algoritmos, tamaños de clave o implementaciones inseguras. 

- La fuerza del cifrado es apropiada para la metodología de cifrado en  La fuerza del cifrado es apropiada para la metodología de cifrado en uso. 

## **Requisito 5: Proteger Todos los Sistemas y Redes de Software Malicioso** 

**5.1** Se definen y comprenden los procesos y mecanismos para proteger todos los sistemas y redes del software malicioso. 

**5.1.1** Todas las políticas de seguridad y procedimientos operativos que se 6 identifican en el Requisito 5 son: 

- Documentados. 

- Actualizados. 

- En uso. 

- Conocidos por todas las partes involucradas. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

15 

**==> picture [522 x 373] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|
|5.1.2|Los roles y responsabilidades para realizar las actividades del|6|
|Requisito 5 están documentados, asignados y comprendidos.|
|5.2|El software malintencionado|(malware)|es evadido, o se detecta y se|
|soluciona.|
|5.2.1|Una solución|antimalware|se aplicará a todos los componentes del|2|
|sistema, excepto a aquellos componentes del sistema identificados en|
|evaluaciones periódicas según el Requisito 5.2.3 que concluye que los|
|componentes del sistema no están en riesgo de|malware.|
|5.2.2|Las soluciones|antimalware|implementadas:|2|
|• Detectan todos los tipos conocidos de|malware.|
|• Eliminan, bloquean o contienen todos los tipos conocidos de|malware.|
|5.2.3|Todos los componentes del sistema que no se encuentren en riesgo|2|
|de|malware|se evalúan periódicamente para incluir lo siguiente:|
|•|Una lista documentada de todos los componentes del sistema que no|
|están en riesgo de|malware|.|
|•|Identificación y evaluación de amenazas de|malware|en evolución para|
|los componentes del sistema.|
|• Confirmación de si dichos componentes del sistema continúan sin|
|requerir protección|antimalware.|
|5.2.3.1|2|

**----- End of picture text -----**<br>


- **5.2.3.1** La frecuencia de las evaluaciones periódicas de los componentes del sistema identificados como no en riesgo de malware se define en el análisis de riesgo específico de la entidad, el cual se realiza de acuerdo con todos los elementos especificados en el Requisito 12.3.1. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**5.3** Los mecanismos y procesos _antimalware_ están activos, mantenidos y monitoreados. 

**5.3.1** Las soluciones _antimalware_ se mantienen actualizadas a través de procesos de actualización automáticos. 

- **5.3.2** Soluciones antimalware: 

2 2 

- Realizan escaneados periódicos y escaneados activos o en tiempo real. **O** 

- Realizan un análisis continuo del comportamiento de los sistemas o procesos. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

16 

**==> picture [498 x 460] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>5.3.2.1  Si se realizan escaneos periódicos de malware para cumplir  2<br>con el Requisito 5.3.2, la frecuencia de los escaneos se define en el<br>análisis de riesgos específico de la entidad, que se realiza de acuerdo<br>con todos los elementos especificados en el Requisito 12.3.1.<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo<br>de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener<br>más detalles.<br>5.3.3  Para los medios electrónicos extraíbles, la solución  antimalware :  2<br>• Realiza escaneos automáticos cuando el medio es insertado, conectado<br>o montado lógicamente,<br>O<br>• Realiza un análisis continuo del comportamiento de los sistemas o<br>procesos cuando el medio está insertado, conectado o montado<br>lógicamente.<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo de<br>2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más<br>detalles.<br>5.3.4  Los registros de auditoría de la solución  antimalware  están habilitados  2<br>y se conservan de acuerdo con el Requisito 10.5.1.<br>5.3.5  Los mecanismos  antimalware  no pueden ser desactivados o alterados  2<br>por los usuarios, a menos que esté específicamente documentado y<br>autorizado por la administración en cada caso, por un período de tiempo<br>limitado.<br> Los mecanismos contra  antiphishing  protegen a los usuarios contra los<br>phishing .<br>5.4.1  Existen procesos y mecanismos automatizados para detectar y  2<br>proteger al personal contra ataques de phishing.<br>**----- End of picture text -----**<br>


**5.4** Los mecanismos contra _antiphishing_ protegen a los usuarios contra los ataques de _phishing_ . 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

17 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|

**----- End of picture text -----**<br>


**Requisito 6: Desarrollar y Mantener Sistemas y Softwares Seguros** 

**6.1** Se definen y comprenden los procesos y mecanismos para desarrollar y mantener sistemas y software seguros. 

**==> picture [522 x 413] intentionally omitted <==**

**----- Start of picture text -----**<br>
||||
|---|---|---|
|6.1.1|Todas las políticas de seguridad y procedimientos operativos que se|6|
|identifican en el Requisito 6 son:|
|• Documentados.|
|• Actualizados.|
|• En uso.|
|• Conocidos por todas las partes involucradas.|
|6.1.2|Las roles y responsabilidades para realizar las actividades del|6|
|Requisito 6 están documentados, asignados y comprendidos.|
|6.2|El software a medida y personalizado se desarrolla de forma segura.|
|6.2.1|El software a medida y personalizado se desarrolla de forma segura,|3|
|de la siguiente manera:|
|• Basándose en estándares de la industria y/o mejores prácticas para un|
|desarrollo seguro.|
|• De acuerdo con PCI DSS (por ejemplo, autenticación segura y registro).|
|• Considerando la incorporación de la información de problemas de|
|seguridad durante cada etapa del ciclo de vida del desarrollo de|
|software.|
|6.2.2|El personal de desarrollo de software que trabaja en software a|3|
|medida y personalizado recibe capacitación al menos una vez cada 12|
|meses de la siguiente manera:|
|• Sobre la seguridad del software relevante para su función laboral y|
|lenguajes de desarrollo.|
|• Incluyendo diseño de software seguro y técnicas de codificación segura.|
|• Incluyendo, si se utilizan herramientas de prueba de seguridad, cómo  Incluyendo, si se utilizan herramientas de prueba de seguridad, cómo|
|utilizar las herramientas para detectar vulnerabilidades en el software.|
|6.2.3|3|

**----- End of picture text -----**<br>


- Incluyendo, si se utilizan herramientas de prueba de seguridad, cómo  Incluyendo, si se utilizan herramientas de prueba de seguridad, cómo utilizar las herramientas para detectar vulnerabilidades en el software. 

- **6.2.3** El software a medida y personalizado es revisado antes de ser lanzado a producción o para los clientes, a fin de identificar y corregir posibles vulnerabilidades de codificación, de la siguiente manera: 

- Las revisiones de código garantizan que el código se desarrolle de acuerdo con las pautas de codificación segura. 

- Las revisiones de código buscan vulnerabilidades de software tanto existente como emergente. 

- Las correcciones apropiadas se implementan antes de la publicación. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

18 

||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**||||||||
||**1**|**2**|**3**||**4**|**5**|**6**|
|**6.2.3.1**Si las revisiones manuales de código son realizadas para|||3|||||
|software hecho a medida y personalizado antes de ser liberado a||||||||
|producción, los cambios de código son:||||||||
|•Revisados por personas que no sean el autor del código original, y||||||||
|que conozcan las técnicas de revisión de código y las prácticas de||||||||
|codificación segura.||||||||
|•Revisados y aprobados por la dirección antes de su publicación.||||||||
|Las técnicas de ingeniería de software u otros métodos están|||3|||||



- **6.2.4** Las técnicas de ingeniería de software u otros métodos están definidos y en uso para el software a medida y personalizado por el personal de desarrollo de software a fin de impedir o mitigar los ataques de software comunes y las vulnerabilidades relacionadas, incluyendo, pero no limitado a lo siguiente: 

- Ataques de inyección, incluyendo SQL, LDAP, XPath u otros fallos de flujo de tipo comando, parámetro, objeto, defecto o de inyección. 

- Ataques a datos y estructuras de datos, incluyendo intentos de manipulación de buffers, punteros, datos de entrada o datos compartidos. 

- Ataques al uso de criptografía, incluyendo intentos de explotar implementaciones criptográficas débiles, inseguras o inapropiadas, algoritmos, suites de cifrado o modos de operación. 

- Ataques a la lógica del negocio, incluyendo los intentos de abusar o eludir las características y funcionalidades de la aplicación a través de la manipulación de las APIs, los protocolos y canales de comunicación, la funcionalidad del lado del cliente, u otras funciones y recursos del sistema/aplicación. Esto incluye los scripts entre sitios (XSS) y la falsificación de petición entre sitios (CSRF). 

- Ataques a los mecanismos de control de acceso, incluidos los intentos de eludir o abusar de los mecanismos de identificación, autenticación o autorización, o los intentos de aprovechar las debilidades en la implementación de dichos mecanismos. 

- Ataques a través de cualquier vulnerabilidad de "alto riesgo" identificada en el proceso de identificación de vulnerabilidades, tal como se define en el Requisito 6.3.1. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

19 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|

**----- End of picture text -----**<br>


**6.3** Las vulnerabilidades de seguridad se identifican y son abordadas. 

- **6.3.1** Las vulnerabilidades de seguridad se identifican y gestionan de la siguiente manera: 

- Las nuevas vulnerabilidades de seguridad se identifican utilizando fuentes reconocidas por la industria de información de vulnerabilidades de seguridad, incluyendo alertas de equipos internacionales y nacionales de respuesta a emergencias informáticas (CERTs). 

- A las vulnerabilidades se les asigna una clasificación de riesgo basada en las mejores prácticas de la industria y considerando su impacto potencial. 

- Las clasificaciones de riesgo identifican, como mínimo, todas las vulnerabilidades consideradas de alto riesgo o críticas para el entorno. 

- Se cubren las vulnerabilidades de los programas informáticos a medida y de terceros (por ejemplo, sistemas operativos y bases de datos). 

**6.3.2** A fin de facilitar la gestión de vulnerabilidades y parches se mantiene un inventario del software a medida y personalizado y de los componentes del software de terceros incorporados en el software a medida y personalizado. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**6.3.3** Todos los componentes del sistema están protegidos contra vulnerabilidades conocidas mediante la instalación de 

3 3 3 

parches/actualizaciones de seguridad aplicables de la siguiente manera: 

- Los parches/actualizaciones para vulnerabilidades críticas (identificados de acuerdo con el proceso de clasificación de riesgos del Requisito 6.3.1) se instalan dentro del período de un mes de su emisión. 

- Todos los demás parches/actualizaciones de seguridad aplicables se instalan dentro de un período de tiempo apropiado según determine la entidad de acuerdo a la evaluación de la criticidad del riesgo para el entorno, tal como se identifica en el proceso de clasificación de riesgos del Requisito 6.3.1 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

20 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**6.4**Las aplicaciones web públicas están protegidas contra ataques.|||||||
|**6.4.1**Para las aplicaciones web de cara al público, las nuevas amenazas y<br>vulnerabilidades se abordan de forma continua y están protegidas contra<br>los ataques conocidos de la siguiente manera:<br>•Revisión de las aplicaciones web de cara al público mediante<br>herramientas o métodos de evaluación de la seguridad de las<br>vulnerabilidades de las aplicaciones, sean manuales o automatizadas,<br>como sigue:<br>– Al menos una vez cada 12 meses y después de cambios<br>significativos.<br>– Por una entidad especializada en seguridad de aplicaciones.<br>– Incluyendo, como mínimo, todos los ataques de software comunes<br>descritos en el Requisito 6.2.4.<br>– Todas las vulnerabilidades se clasifican de acuerdo con el Requisito<br>6.3.1.<br>– Se corrigen todas las vulnerabilidades.<br>– La aplicación se vuelve a evaluar después de las correcciones<br>**O**<br>•Instalación de soluciones técnicas automatizadas que detecten e<br>impidan continuamente los ataques basados en la web de la siguiente<br>manera:<br>– Instaladas frente a las aplicaciones web de cara al público para<br>detectar e impedir los ataques basados en la web.<br>– Funcionando activamente y actualizándose según corresponda.<br>– Generando registros de auditoría.<br>– Configurados ya sea para bloquear los ataques basados en la web o<br>para generar una alerta que se investigue inmediatamente.|||3||||
|**6.4.2**Para aplicaciones web de cara al público se implementa una solución<br>técnica automatizada que detecta e impide continuamente ataques<br>basados en la web, con al menos lo siguiente:<br>•Se instala frente a aplicaciones web de cara al público y está<br>configurado para detectar e impedir ataques basados en la web.<br>•Funcionando activamente y actualizándose según corresponda.<br>•Generando registros de auditoría.<br>•Configurados ya sea para bloquear los ataques basados en la web o<br>para generar una alerta que se investigue inmediatamente.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._|||3||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

21 

- **Hito** 

- **Requisitos de PCI DSS v4.0.1 1 2 3 4 5 6** 

- **6.4.3** Todos los _scripts_ de las páginas de pago que se cargan y ejecutan en 2 el navegador del consumidor se gestionan de la siguiente manera: • Se implementa un método para confirmar que cada _script_ está autorizado. 

- • Se implementa un método para asegurar la integridad de cada _script_ . • Se mantiene un inventario de todos los scripts con una justificación empresarial o técnica por escrito que explique su necesidad. 

- _Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- **6.5** Los cambios en todos los componentes del sistema se gestionan de forma segura. **6.5.1** Los cambios en todos los componentes del sistema en el entorno de 6 producción se realizan de acuerdo con los procedimientos establecidos que incluyen: • Motivo y descripción del cambio. • Documentación del impacto a la seguridad. • Aprobación documentada del cambio por las partes autorizadas. • Pruebas para verificar que el cambio no afecta negativamente la seguridad del sistema. 

- • En el caso de los cambios de software a la medida y personalizados, todas las actualizaciones se comprueban para determinar la conformidad con el Requisito 6.2.4 antes de ser instalados para producción. 

- • Procedimientos para hacer frente a los fallos y volver a un estado seguro. 

- **6.5.2** Al completar un cambio significativo, se confirma que todos los 6 requisitos PCI DSS están vigentes en todos los sistemas y redes nuevas o modificadas, y la documentación se actualiza según corresponda. **6.5.3** Los entornos de preproducción se separan de los entornos de 3 producción y la separación se aplica con controles de acceso. **6.5.4** Los roles y las funciones se separan entre los entornos de producción 3 y pre-producción para asignar responsabilidades de manera tal que sólo se desplieguen los cambios revisados y aprobados. **6.5.5** Los datos PAN activos no se utilizan en entornos de pre-producción, 3 excepto cuando esos entornos están incluidos en el CDE y protegidos de acuerdo con todos los requisitos PCI DSS aplicables. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

22 

||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**||||||||
||**1**|**2**|**3**||**4**|**5**|**6**|
|**6.5.6**Los datos de prueba y las cuentas de pruebas se eliminan de los|||3|||||
|componentes del sistema antes de que el sistema entre en producción.||||||||



**Requisito 7: Restringir el Acceso a los Componentes del Sistema y a los Datos de Tarjetahabiente Según la Necesidad de Conocimiento de la Empresa** 

**7.1** Se definen y comprenden los procesos y mecanismos para restringir el acceso a los componentes del sistema ya los datos de tarjetahabiente según la necesidad de negocio. 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**6.5.6**Los datos de prueba y las cuentas de pruebas se eliminan de los<br>componentes del sistema antes de que el sistema entre en producción.|||3||||
|**Requisito 7: Restringir el Acceso a los Componentes del Sistema y a los Datos de**<br>**Tarjetahabiente Según la Necesidad de Conocimiento de la Empresa**|||||||
|**7.1**Se definen y comprenden los procesos y mecanismos para restringir el<br>acceso a los componentes del sistema ya los datos de tarjetahabiente según la<br>necesidad de negocio.|||||||
|**7.1.1**Todas las políticas de seguridad y procedimientos operativos que se<br>identifican en el Requisito 7 son:<br>•Documentados.<br>•Actualizados.<br>•En uso.<br>•Conocidos por todas las partes involucradas.||||||6|
|**7.1.2**Los roles y responsabilidades para realizar las actividades del<br>Requisito 7 están documentados, asignados y son comprendidos.||||||6|
|**7.2**El acceso a los componentes y datos del sistema se define y asigna<br>adecuadamente.|||||||
|**7.2.1**Se define un modelo de control de acceso que incluye la autorización<br>de acceso como sigue:<br>•Acceso apropiado según el tipo de negocios de la entidad y las<br>necesidades de acceso.<br>•Acceso a los componentes del sistema y a los recursos de datos<br>basados en la clasificación y las funciones del trabajo de los usuarios.<br>•Los privilegios mínimos requeridos (por ejemplo, usuario, administrador)<br>para realizar una función laboral.||||4|||
|**7.2.2**El acceso se asigna a los usuarios, incluidos los privilegiados, en<br>función de:<br>•La clasificación y función del trabajo.<br>•Los privilegios mínimos necesarios para realizar las responsabilidades<br>del trabajo.||||4|||
|**7.2.3**Los privilegios requeridos son aprobados por el personal autorizado.||||4|||



**7.2** El acceso a los componentes y datos del sistema se define y asigna adecuadamente. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

23 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**7.2.4**Todas las cuentas de usuario y los privilegios de acceso relacionados,<br>incluyendo las cuentas de terceros/proveedores, se revisan de la siguiente<br>manera:<br>•Al menos una vez cada seis meses.<br>•Para asegurarse de que las cuentas de usuario y el acceso sigan siendo<br>apropiados según la función del trabajo.<br>•Se aborda cualquier acceso inadecuado.<br>•La gerencia reconoce que el acceso sigue siendo apropiado.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._||||4|||
|**7.2.5**Todas las aplicaciones y cuentas del sistema y los privilegios de<br>acceso relacionados se asignan y administran de la siguiente manera:<br>•Basado en los privilegios mínimos necesarios para la operatividad del<br>sistema o aplicación.<br>•El acceso está limitado a los sistemas, aplicaciones o procesos que<br>específicamente requieren su uso.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._||||4|||
|**7.2.5.1**Todo el acceso de aplicaciones y cuentas del sistema y los<br>privilegios de acceso relacionados se revisan de la siguiente manera:<br>•Periódicamente, (a una frecuencia definida en el análisis de riesgos<br>específico de la entidad, el cual se desarrolla de acuerdo a todos los<br>elementos especificados en el Requisito 12.3.1).<br>•El acceso a la aplicación/sistema sigue siendo apropiado para la<br>función que se está realizando.<br>•Se aborda cualquier acceso inadecuado.<br>•La gerencia reconoce que el acceso sigue siendo apropiado.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||||4|||
|**7.2.6**Todo acceso por parte de los usuarios a las bases de datos de<br>tarjetahabiente está restringido de la siguiente manera:<br>•A través de aplicaciones u otros métodos programáticos, con acceso y<br>acciones permitidas basadas en las funciones y privilegios mínimos del<br>usuario.<br>•Solo los administradores autorizados pueden acceder directamente o<br>consultar las bases de datos de CHD almacenados.||||4|||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

24 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**7.3**El acceso a los componentes y datos del sistema se gestiona a través de un<br>sistema de control de acceso.|||||||
|**7.3.1**Existen sistemas de control de acceso que restringen el acceso según<br>la necesidad del usuario y cubre todos los componentes del sistema.||||4|||
|**7.3.2**Los sistemas de control de acceso están configurados para aplicar los<br>permisos asignados a individuos, aplicaciones, y sistemas basados en la<br>clasificación y función del trabajo.||||4|||
|**7.3.3**El sistema de control de acceso está configurado para "denegar todo"<br>predeterminadamente.||||4|||
|**Requisito 8: Identificar a los Usuarios y Autenticar el Acceso a los Componentes del**<br>**Sistema**|||||||
|**8.1**Los procesos y mecanismos para identificar a los usuarios y autenticar el<br>acceso a los componentes del sistema están definidos y comprendidos.|||||||
|**8.1.1**Todas las políticas de seguridad y procedimientos operativos que se<br>identifican en el Requisito 8 son:<br>•Documentados.<br>•Actualizados.<br>•En uso.<br>•Conocidos por todas las partes involucradas.||||||6|
|**8.1.2**Los roles y responsabilidades para realizar las actividades del<br>Requisito 8 están documentados, asignados y son comprendidos.||||||6|
|**8.2**La identificación de usuarios y las cuentas relacionadas para usuarios y<br>administradores se gestionan estrictamente durante el ciclo de vida de una<br>cuenta.|||||||
|**8.2.1**A todos los usuarios se les asigna un ID único antes de permitirles el<br>acceso a los componentes del sistema o a los datos de tarjetahabiente.||2|||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

25 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**8.2.2**Las identificaciones IDs de grupos, compartidas o genéricas, u otras<br>credenciales de autenticación compartidas sólo se usan cuando es<br>necesario, de manera excepcional, y se administran de la siguiente<br>manera:<br>•Se impide el uso de la ID a menos que se requiera por una circunstancia<br>excepcional.<br>•Su uso está limitado al tiempo necesario para la circunstancia<br>excepcional.<br>•La justificación de negocio para su uso está documentada.<br>•El uso está explícitamente aprobado por la dirección.<br>•La identidad del usuario individual se confirma antes de que se conceda<br>el acceso a una cuenta.<br>•Cada acción realizada es atribuible a un usuario individual.||2|||||
|**8.2.3****_Requisito adicional solo para proveedores de servicios:_**Los<br>proveedores de servicios con acceso remoto a las instalaciones del cliente<br>deben utilizar factores de autenticación únicos para las instalaciones de<br>cada cliente.||2|||||
|**8.2.4**La creación, eliminación y modificación de_IDs_de usuario, factores de<br>autenticación y otros objetos de identificación se gestiona de la siguiente<br>manera:<br>•Autorizado con la aprobación correspondiente.<br>•Implementado solo con los privilegios especificados en la aprobación<br>documentada.||2|||||
|**8.2.5**El acceso para los usuarios rescindidos se revoca inmediatamente.||2|||||
|**8.2.6**Las cuentas de usuario inactivas se eliminan o inhabilitan dentro de<br>los 90 días de inactividad.||2|||||
|**8.2.7**Las cuentas utilizadas por terceros para acceder, dar apoyo o<br>mantener componentes del sistema a través de acceso remoto se<br>administran de la siguiente manera:<br>•Son habilitadas solamente durante el período de tiempo necesario y son<br>deshabilitadas cuando no están en uso.<br>•El uso es monitoreado para detectar actividad inesperada.||2|||||
|**8.2.8**Si una sesión de usuario ha estado inactiva durante más de 15<br>minutos, se requiere que el usuario vuelva a autenticarse para reactivar el<br>terminal o la sesión.||2|||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

26 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|

**----- End of picture text -----**<br>


**8.3** Se establece y gestiona una autenticación robusta para usuarios y administradores. 

**==> picture [390 x 368] intentionally omitted <==**

**----- Start of picture text -----**<br>
||||
|---|---|---|
|8.3.1|Todo acceso por parte de los usuarios y administradores a|2|
|componentes del sistema se autentifica utilizando al menos uno de los|
|siguientes factores de autenticación:|
|• Algo que uno sabe, como una contraseña o frase de paso.|
|• Algo que uno tiene, como un dispositivo|token|o una tarjeta inteligente.|
|• Algo que uno es, como un elemento biométrico.|
|8.3.2|Se utiliza criptografía robusta para que todos los factores de|2|
|autenticación sean ilegibles durante la transmisión y el almacenamiento en|
|todos los componentes del sistema.|
|8.3.3|La identidad del usuario se verifica antes de modificar cualquier factor|2|
|de autenticación.|
|8.3.4|Los intentos de autenticación inválidos se limitan mediante:|2|
|• El bloqueo del  El bloqueo del|ID|de usuario después de no más de 10 intentos.|
|• El establecimiento de la duración del bloqueo a un mínimo de 30|
|minutos o hasta que se confirme la identidad del usuario.|
|8.3.5|Si las contraseñas/frases de paso se utilizan como factores de|2|
|autenticación para cumplir con el Requisito 8.3.1, estas se establecen y|
|restablecen para cada usuario tal y como sigue:|
|• Se establece un valor único para la primera vez que se utilizan y al  Se establece un valor único para la primera vez que se utilizan y al|
|restablecerse.|
|• Existe la obligatoriedad de cambiarlos inmediatamente después del  Existe la obligatoriedad de cambiarlos inmediatamente después del|
|primer uso.|
|8.3.6|2|

**----- End of picture text -----**<br>


- El bloqueo del  El bloqueo del _ID_ de usuario después de no más de 10 intentos. 

- Se establece un valor único para la primera vez que se utilizan y al  Se establece un valor único para la primera vez que se utilizan y al restablecerse. 

- Existe la obligatoriedad de cambiarlos inmediatamente después del  Existe la obligatoriedad de cambiarlos inmediatamente después del primer uso. 

**8.3.6** Si las contraseñas/frases de paso se utilizan como factores de autenticación para cumplir el Requisito 8.3.1, estas deberán cumplir el siguiente nivel mínimo de complejidad: 

- Una longitud mínima de 12 caracteres (o SI el sistema no admite 12 caracteres, una longitud mínima de ocho caracteres). 

- Contener tanto caracteres numéricos como alfabéticos. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

_Hasta el 31 de marzo de 2025, las contraseñas deben tener una longitud mínima de siete caracteres, de acuerdo con el Requisito 8.2.3 PCI DSS v3.2.1._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

27 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**8.3.7**Las personas no pueden enviar una nueva contraseña / frase de paso<br>que sea igual a cualquiera de las últimas cuatro contraseñas / frases de<br>paso utilizadas.||2|||||
|**8.3.8**Las políticas y los procedimientos de autenticación están<br>documentados y son comunicados a todos los usuarios, incluyendo:<br>•Orientación sobre la selección de factores de autenticación robustos.<br>•Orientación sobre cómo los usuarios deben proteger sus factores de<br>autenticación.<br>•Instrucciones para no reutilizar contraseñas/frases de paso utilizadas<br>anteriormente.<br>•Instrucciones para cambiar contraseñas/frases de paso si existe alguna<br>sospecha o conocimiento de que la contraseña/frase de paso se ha visto<br>comprometida y cómo reportar el incidente.||||4|||
|**8.3.9**Si las contraseñas/frases de paso se utilizan como el único factor de<br>autenticación para el acceso del usuario (es decir, en cualquier<br>implementación de autenticación de factor único), entonces:<br>•Las contraseñas/frases de paso se cambian al menos una vez cada 90<br>días,<br>**O**<br>•La postura de seguridad de las cuentas se analiza dinámicamente y el<br>acceso a los recursos en tiempo real se determina automáticamente de<br>acuerdo a dicha postura de seguridad.||2|||||
|**8.3.10****_Requisito adicional solo para proveedores de servicios:_**Si las<br>contraseñas / frases de paso contraseña se utilizan como el único factor de<br>autenticación para el acceso del usuario del cliente a los datos de<br>tarjetahabiente (es decir, en cualquier implementación de autenticación de<br>factor único), entonces se brinda orientación a los usuarios del cliente, que<br>incluye:<br>•Orientación para que los clientes cambien sus contraseñas/frases de<br>paso periódicamente.<br>•Orientación sobre cuándo y bajo qué circunstancias se cambian las<br>contraseñas/frases de paso.||2|||||



- Orientación sobre la selección de factores de autenticación robustos. 

- Orientación sobre cómo los usuarios deben proteger sus factores de autenticación. 

- Instrucciones para no reutilizar contraseñas/frases de paso utilizadas anteriormente. 

- Instrucciones para cambiar contraseñas/frases de paso si existe alguna sospecha o conocimiento de que la contraseña/frase de paso se ha visto comprometida y cómo reportar el incidente. 

- Las contraseñas/frases de paso se cambian al menos una vez cada 90 días, 

- La postura de seguridad de las cuentas se analiza dinámicamente y el acceso a los recursos en tiempo real se determina automáticamente de acuerdo a dicha postura de seguridad. 

## **8.3.10** _**Requisito adicional solo para proveedores de servicios:**_ Si las 

contraseñas / frases de paso contraseña se utilizan como el único factor de autenticación para el acceso del usuario del cliente a los datos de tarjetahabiente (es decir, en cualquier implementación de autenticación de factor único), entonces se brinda orientación a los usuarios del cliente, que incluye: 

- Orientación para que los clientes cambien sus contraseñas/frases de paso periódicamente. 

- Orientación sobre cuándo y bajo qué circunstancias se cambian las contraseñas/frases de paso. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

28 

**==> picture [498 x 500] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>8.3.10.1  Requisito adicional sólo para proveedores de servicios:  Si  2<br>las contraseñas/frases de paso se utilizan como el único factor de<br>autenticación para el acceso del usuario del cliente (es decir, en<br>cualquier implementación de autenticación de factor único), entonces:<br>• Las contraseñas/frases de paso se cambian al menos una vez cada<br>90 días,<br>O<br>• La postura de seguridad de las cuentas se analiza dinámicamente y<br>el acceso a los recursos en tiempo real se determina<br>automáticamente de acuerdo a dicha postura de seguridad.<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo<br>de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener<br>más detalles.<br>8.3.11  Cuando se utilizan factores de autenticación como  tokens  de  4<br>seguridad físicos o lógicos, tarjetas inteligentes o certificados:<br>• Los factores se asignan a un usuario individual y no se comparten entre<br>varios usuarios.<br>• Los controles físicos y/o lógicos garantizan que sólo el usuario previsto  Los controles físicos y/o lógicos garantizan que sólo el usuario previsto<br>pueda utilizar ese factor para acceder.<br>Se implementa la autenticación múltiples factores (MFA) para proteger el<br>8.4.1  Los MFA se implementan para todos los accesos al CDE sin consola,  2<br>para el personal con acceso administrativo.<br>8.4.2  Los MFA se implementan para todos los ingresos al CDE.  2<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo de<br>2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más<br>detalles.<br>8.4.3  Los MFA se implementan para todos los accesos a redes remotas  2<br>que se originan fuera de la red de la entidad y que podrían ingresar o<br>impactar el CDE.<br>**----- End of picture text -----**<br>


- Los controles físicos y/o lógicos garantizan que sólo el usuario previsto  Los controles físicos y/o lógicos garantizan que sólo el usuario previsto pueda utilizar ese factor para acceder. 

**8.4** Se implementa la autenticación múltiples factores (MFA) para proteger el ingreso al CDE. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

29 

**==> picture [404 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>**----- End of picture text -----**<br>


**8.5** Los sistemas de autenticación de múltiples factores (MFA) están configurados para evitar su uso indebido. 

- **8.5.1** Los sistemas MFA se implementan de la siguiente manera: 2 • El sistema MFA no es susceptible a ataques de repetición. • Los sistemas MFA no pueden ser omitidos por ningún usuario, incluyendo los usuarios administrativos, a menos que esté específicamente documentado y autorizado por la administración de manera excepcional durante un período de tiempo limitado. 

- Se utilizan al menos dos tipos diferentes de factores de autenticación. 

- Se requiere el éxito de todos los factores de autenticación antes de que se otorgue el acceso. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**8.6** El uso de cuentas de aplicaciones y sistemas y factores de autenticación asociados se gestiona estrictamente. 

- **8.6.1** Si las cuentas utilizadas por los sistemas o aplicaciones pueden ser 4 utilizadas para el inicio de sesión interactivo, se gestionan de la siguiente manera: • Se impide el uso interactivo a menos que se requiera por una  Se impide el uso interactivo a menos que se requiera por una circunstancia excepcional. 

- • El uso está limitado al tiempo necesario para la circunstancia  El uso está limitado al tiempo necesario para la circunstancia excepcional. 

- • La justificación de negocio para su uso interactivo está documentada.  La justificación de negocio para su uso interactivo está documentada. • El uso interactivo está explícitamente aprobado por la dirección.   El uso interactivo está explícitamente aprobado por la dirección. • La identidad del usuario individual se confirma antes de que se conceda  La identidad del usuario individual se confirma antes de que se conceda el acceso a una cuenta. 

- • Cada acción realizada es atribuible a un usuario individual.   Cada acción realizada es atribuible a un usuario individual. _Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ **8.6.2** 4 

- Se impide el uso interactivo a menos que se requiera por una  Se impide el uso interactivo a menos que se requiera por una circunstancia excepcional. 

- El uso está limitado al tiempo necesario para la circunstancia  El uso está limitado al tiempo necesario para la circunstancia excepcional. 

- La justificación de negocio para su uso interactivo está documentada.  La justificación de negocio para su uso interactivo está documentada. 

- El uso interactivo está explícitamente aprobado por la dirección.   El uso interactivo está explícitamente aprobado por la dirección. 

- La identidad del usuario individual se confirma antes de que se conceda  La identidad del usuario individual se confirma antes de que se conceda el acceso a una cuenta. 

- Cada acción realizada es atribuible a un usuario individual.   Cada acción realizada es atribuible a un usuario individual. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**8.6.2** Las contraseñas/frases de paso para cualquier aplicación y cuentas de sistema que puedan ser utilizadas para el inicio de sesión interactivo no están codificadas en scripts, archivos de configuración/propiedades, o código fuente a la medida y personalizado. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

30 

|||||**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**||||||||
||**1**|**2**|**3**|**3**|**4**|**5**|**6**|
|**8.6.3**Las contraseñas/frases de paso para cualquier cuenta de aplicación y|||||4|||
|de sistema están protegidas contra el uso indebido de la siguiente manera:||||||||



- Las cuentas de sistema y de aplicación se cambian periódicamente, (a una frecuencia definida en el análisis de riesgos específico de la entidad, el cual se desarrolla de acuerdo con todos los elementos especificados en el Requisito 12.3.1) y ante la sospecha o la confirmación de que estén comprometidas. 

- Las contraseñas/frases de acceso se construyen con la complejidad necesaria y apropiada para la frecuencia con la que la entidad cambia las contraseñas/frases de acceso. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

## **Requisito 9: Restringir el Acceso Físico a los Datos de Tarjetahabiente** 

**9.1** Se definen y comprenden los procesos y mecanismos para restringir el acceso físico a los datos de tarjetahabiente. 

|**9.1.1**Todas las políticas de seguridad y procedimientos operativos que se||||||6|
|---|---|---|---|---|---|---|
|identifican en el Requisito 9 están:|||||||
|•Documentados.|||||||
|•Actualizados.|||||||
|•En uso.|||||||
|•Conocidos por todas las partes involucradas.|||||||
|**9.1.2**Los roles y responsabilidades para realizar las actividades del||||||6|
|Requisito 9 están documentados, asignados y comprendidos.|||||||
|Los controles de acceso físico gestionan la entrada a las instalaciones y|||||||
|sistemas que contengan datos de tarjetahabiente.|||||||
|**9.2.1**Existen controles de entrada a las instalaciones apropiados para||2|||||
|restringir el acceso físico a los sistemas en el CDE.|||||||



- Documentados. 

- Actualizados. 

- En uso. 

- Conocidos por todas las partes involucradas. 

**9.2** Los controles de acceso físico gestionan la entrada a las instalaciones y sistemas que contengan datos de tarjetahabiente. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

31 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**9.2.1.1**El ingreso físico individual a las áreas sensibles dentro del CDE<br>se monitoriza con cámaras de video vigilancia o mecanismos de<br>control de acceso físico (o ambos) como sigue:<br>•Los puntos de entrada y salida hacia/desde las áreas sensibles<br>dentro del CDE son monitorizados.<br>•Los dispositivos o mecanismos de monitorización están protegidos<br>contra la manipulación o la desactivación.<br>•Los datos recogidos se revisan y se correlacionan con otras<br>entradas.<br>•Los datos recogidos se almacenan durante al menos tres meses, a<br>menos que la ley lo restrinja.||2|||||
|**9.2.2**Se implementan controles físicos y/o lógicos para restringir el uso de<br>tomas (o puertos) de red de acceso público dentro de la instalación.||2|||||
|**9.2.3**El ingreso físico a los puntos de acceso inalámbricos, puertas de<br>enlace (gateways), hardware de redes y de comunicaciones y líneas de<br>telecomunicaciones dentro de la instalación está restringido.||2|||||
|**9.2.4**El acceso a las consolas en áreas sensibles está restringido mediante<br>bloqueo cuando no están en uso.||2|||||
|**9.3**Se autoriza y gestiona el acceso físico de personal y visitantes.|||||||
|**9.3.1**Se implementan procedimientos para autorizar y administrar el<br>acceso físico del personal al CDE, que incluyen:<br>•Identificación de personal.<br>•Gestionar cambios en los requisitos de ingreso físico de una persona.<br>•Revocación o rescisión de la identificación del personal.<br>•Limitar el acceso al proceso o sistema de identificación al personal<br>autorizado.|||||5||
|**9.3.1.1**El acceso físico a áreas sensitivas dentro del CDE para el<br>personal se controla de la siguiente manera:<br>•El acceso está autorizado y se basa en la función del trabajo<br>individual.<br>•El acceso se revoca inmediatamente después de la terminación.<br>•Todos los mecanismos de acceso físico, como llaves, tarjetas de<br>acceso, etc., se devuelven o desactivan al finalizar.||2|||||



**9.3** Se autoriza y gestiona el acceso físico de personal y visitantes. 

- Identificación de personal. 

- Gestionar cambios en los requisitos de ingreso físico de una persona. 

- Revocación o rescisión de la identificación del personal. 

- Limitar el acceso al proceso o sistema de identificación al personal autorizado. 

**9.3.1.1** El acceso físico a áreas sensitivas dentro del CDE para el personal se controla de la siguiente manera: 

- El acceso está autorizado y se basa en la función del trabajo individual. 

- El acceso se revoca inmediatamente después de la terminación. 

- Todos los mecanismos de acceso físico, como llaves, tarjetas de acceso, etc., se devuelven o desactivan al finalizar. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

32 

**==> picture [522 x 532] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>9.3.2  Se implementan procedimientos para autorizar y administrar el  5<br>acceso de visitantes al CDE, que incluyen:<br>• Los visitantes son autorizados antes de ingresar.<br>• Los visitantes están acompañados en todo momento.<br>• Los visitantes están claramente identificados y reciben un gafete u otra<br>identificación con fecha de caducidad.<br>• Los gafetes de visitante u otra identificación distinguen visiblemente a<br>los visitantes del personal.<br>9.3.3  Los gafetes de visitante o la identificación se devuelven o desactivan  5<br>antes de que los visitantes abandonen las instalaciones, o en su fecha de<br>caducidad.<br>9.3.4  Se registros de visitantes se utilizan para mantener un registro físico  5<br>de las actividades de los visitantes tanto dentro de la instalación como en<br>las áreas sensibles, que incluye:<br>• El nombre del visitante y la organización representada.<br>• La fecha y hora de la visita.<br>• El nombre del personal que autoriza el acceso físico.<br>• Conservar el registro al menos durante al menos tres meses, a menos<br>que la ley lo restrinja.<br>9.4  Los medios con datos de tarjetahabiente se almacenan, acceden, distribuyen<br>y destruyen de forma segura.<br>9.4.1  Todos los medios que contienen datos de tarjetahabiente están  5<br>protegidos físicamente.<br>9.4.1.1  Las copias de seguridad sin conexión con los datos de  5<br>tarjetahabiente se almacenan en una ubicación segura.<br>9.4.1.2  La protección de las ubicaciones de las copias de seguridad  5<br>fuera de línea que contienen los datos de tarjetahabiente se revisa al<br>menos una vez cada 12 meses.<br>9.4.2  Todos los datos de tarjetahabiente se clasifican de acuerdo con la  5<br>confidencialidad de esos datos.<br>**----- End of picture text -----**<br>


©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

33 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**9.4.3**Los apoyos con datos de tarjetahabiente enviados fuera de las<br>instalaciones se protegen de la siguiente manera:<br>•Los datos enviados fuera de las instalaciones se registran.<br>•Los datos se envían por mensajería segura u otro método de entrega<br>que pueda ser rastreado con precisión.<br>•Los registros de seguimiento fuera de las instalaciones incluyen detalles<br>sobre la ubicación de los datos.|||||5||
|**9.4.4**La gerencia aprueba todos los movimientos de apoyos con datos de<br>tarjetahabiente que se trasladan fuera de las instalaciones (incluso cuando<br>son distribuidos a particulares).|||||5||
|**9.4.5**Se mantienen registros de inventario de todos los apoyos electrónicos<br>con datos de tarjetahabiente.|||||5||
|**9.4.5.1**Los inventarios de apoyos electrónicos con datos de<br>tarjetahabiente se realizan al menos una vez cada 12 meses.|||||5||
|**9.4.6**Los materiales impresos con datos de tarjetahabiente se destruyen<br>cuando ya no se necesitan por razones de negocios o legales, de la<br>siguiente manera:<br>•Los materiales se trituran transversalmente, se incineran o se pulverizan<br>de forma que los datos de tarjetahabiente no puedan reconstruirse.<br>•Los materiales se guardan en contenedores de almacenamiento seguro<br>antes de su destrucción.|1||||||
|**9.4.7**Los medios de almacenamiento electrónicos con datos de<br>tarjetahabiente se destruyen cuando ya no se necesitan por razones de<br>negocio o legales mediante una de las siguientes opciones:<br>•El medio de almacenamiento electrónico se destruye.<br>•Los datos de tarjetahabiente se vuelven irrecuperables, de modo que no<br>pueden reconstruirse.|1||||||



- El medio de almacenamiento electrónico se destruye. 

- Los datos de tarjetahabiente se vuelven irrecuperables, de modo que no pueden reconstruirse. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

34 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



**9.5** Los dispositivos de Punto de Interacción (POI) están protegidos contra manipulaciones y sustituciones no autorizadas. 

|**9.5.1**Los dispositivos POI que capturan los datos de las tarjetas de pago a|**9.5.1**Los dispositivos POI que capturan los datos de las tarjetas de pago a||2|
|---|---|---|---|
|través de la interacción física directa con el factor de forma de la tarjeta de||||
|pago están protegidos contra la manipulación y la sustitución no autorizada,||||
|incluyendo lo siguiente:||||
|•|Mantener una lista de dispositivos de POI.|||
|•|Inspeccionar periódicamente los dispositivos POI en busca de|||
||manipulaciones o sustituciones no autorizadas.|||
|•|Formar al personal para que esté atento a los comportamientos|||
||sospechosos y denuncie las manipulaciones o sustituciones no|||
||autorizadas de los dispositivos.|||
||**9.5.1.1**Se mantiene una lista actualizada de los dispositivos POI, que||2|
||incluye:|||
||•Marca y modelo del dispositivo.|||
||•Ubicación del dispositivo.|||
||•Número de serie del dispositivo u otros métodos de identificación|||
||única.|||
||**9.5.1.2**Las superficies de los dispositivos POI se inspeccionan||2|
||periódicamente para detectar manipulaciones y sustituciones no|||
||autorizadas.|||
||**9.5.1.2.1**La frecuencia de las inspecciones a los dispositivos POI||2|
||y el tipo de inspección que se realice se define en el análisis de|||
||riesgos específico de la entidad, que se realiza de acuerdo con|||
||todos los elementos especificados en el Requisito 12.3.1.|||



- Mantener una lista de dispositivos de POI. 

- Inspeccionar periódicamente los dispositivos POI en busca de manipulaciones o sustituciones no autorizadas. 

- Formar al personal para que esté atento a los comportamientos sospechosos y denuncie las manipulaciones o sustituciones no autorizadas de los dispositivos. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

35 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**9.5.1.3**Se proporciona capacitación para que el personal en entornos||2|||||||
|POI esté al tanto de los intentos de manipulación o reemplazo de|||||||||
|dispositivos POI, lo que incluye: manipulación o reemplazo de|||||||||
|dispositivos POI, lo que incluye:|||||||||
|•Verificar la identidad de cualquier tercero que afirme ser personal de|||||||||
|reparación o mantenimiento, antes de otorgarles acceso para|||||||||
|modificar o solucionar problemas en los dispositivos.|||||||||



- Procedimientos para garantizar que los dispositivos no se instalen, reemplacen o devuelvan sin verificación. 

- Ser consciente de comportamientos sospechosos alrededor de los dispositivos. 

- Informar sobre comportamientos sospechosos e indicaciones de manipulación o sustitución de dispositivos al personal apropiado. 

## **Requisito 10: Registrar y Supervisar Todos los Accesos a los Componentes del Sistema y a los Datos de Tarjetahabiente** 

**10.1** Se definen y entienden los procesos y mecanismos para ingresar y monitorear todos los accesos a los componentes del sistema y a los datos de tarjetahabiente. 

|**10.1.1**Todas las políticas de seguridad y procedimientos operativos que se||||||6|
|---|---|---|---|---|---|---|
|identifican en el Requisito 10 está:|||||||
|•Documentados.|||||||
|•Actualizados.|||||||
|•En uso.|||||||
|•Conocidos por todas las partes involucradas.|||||||
|**10.1.2**Los roles y responsabilidades para realizar las actividades del||||||6|
|Requisito 10 están documentados, asignados y comprendidos.|||||||
|**10.2**Los registros de auditoría se implementan para apoyar la detección de||||4|||
|anomalías y actividades sospechosas, y el análisis forense de eventos.|||||||
|**10.2.1**Los registros de auditoría están habilitados y activos para todos los||||4|||
|componentes del sistema y los datos de tarjetahabiente.|||||||
|**10.2.1.1**Los registros de auditoría capturan todo el acceso de los||||4|||
|usuarios individuales a los datos de tarjetahabiente.|||||||
|**10.2.1.2**Los registros de auditoría almacenan todas las acciones||||4|||
|realizadas por cualquier individuo con acceso administrativo,|||||||
|incluyendo cualquier uso interactivo de la aplicación o cuentas del|||||||
|sistema.|||||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

36 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**10.2.1.3**Los registros de auditoría capturan todo el acceso a los<br>mismos.||||4|||
|**10.2.1.4**Los registros de auditoría capturan todos los intentos de<br>acceso lógico inválidos.||||4|||
|**10.2.1.5**Los registros de auditoría capturan todos los cambios en la<br>identificación y credenciales de autenticación, lo que incluye, entre<br>otros:<br>•Creación de nuevas cuentas.<br>•Elevación de privilegios.<br>•Todos los cambios, adiciones o eliminaciones de cuentas con<br>acceso administrativo.||||4|||
|**10.2.1.6**Los registros de auditoría capturan lo siguiente:<br>•Toda inicialización de nuevos registros de auditoría y<br>•Todo inicio, la detención o la pausa de los registros de auditoría<br>existentes.||||4|||
|**10.2.1.7**Los registros de auditoría capturan toda la creación y<br>eliminación de objetos a nivel del sistema.||||4|||
|**10.2.2**Los registros de auditoría guardan los siguientes detalles para cada<br>evento auditable:<br>•Identificación del usuario.<br>•Tipo de evento.<br>•Fecha y hora.<br>•Indicación de Exitoso o Fallido.<br>•Origen del evento.<br>•Identidad o nombre de los datos, componentes del sistema, recursos o<br>servicios afectados (por ejemplo, nombre y protocolo).||||4|||
|**10.3**Los registros de auditoría están protegidos contra la destrucción y las<br>modificaciones no autorizadas.|||||||
|**10.3.1**El acceso de lectura a los archivos de registros de auditoría está<br>limitado a aquellos con una necesidad relacionada con sus funciones.||||4|||
|**10.3.2**Los archivos de registros de auditoría están protegidos para evitar<br>modificaciones por parte de terceros.||||4|||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

37 

**==> picture [522 x 600] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>10.3.3  Los archivos de registros de auditoría, incluidos los de tecnologías  4<br>externas, se respaldan con prontitud en un servidor de registro interno<br>seguro, central o sobre otro medio que sea difícil de modificar.<br>10.3.4  Los mecanismos de detección de cambios o supervisión de la  4<br>integridad de los archivos se utilizan en registros de auditoría para<br>garantizar que los datos de registros existentes no se puedan modificar sin<br>generar alertas.<br>10.4  Los registros de auditoría se revisan para identificar anomalías o<br>actividades sospechosas.<br>10.4.1  Los siguientes registros de auditoría se revisan al menos una vez al  4<br>día:<br>• Todos los eventos de seguridad.<br>• Registros de todos los componentes del sistema que almacenan,<br>procesan o transmiten CHD y/o SAD.<br>• Registros de todos los componentes críticos del sistema.<br>• Registros de todos los servidores y componentes del sistema que<br>realizan funciones de seguridad (por ejemplo, controles de seguridad de<br>red, sistemas de detección de intrusiones/sistemas de prevención de<br>intrusiones (IDS / IPS), servidores de autenticación).<br>10.4.1.1  Se utilizan mecanismos automatizados para realizar  4<br>revisiones de los registros de auditoría.<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo<br>de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener<br>más detalles.<br>10.4.2  Los registros de todos los demás componentes del sistema (aquellos  4<br>no especificados en el Requisito 10.4.1) se revisan periódicamente.<br>10.4.2.1  La frecuencia de las evaluaciones periódicas de los  4<br>componentes del sistema identificados (No definidos en el Requisito<br>10.4.1) se define en el análisis de riesgo específico de la entidad, el<br>cual se realiza de acuerdo con todos los elementos especificados en el<br>Requisito 12.3.1.<br>Este requisito es la mejor práctica recomendada hasta el 31 de marzo<br>de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener<br>más detalles.<br>10.4.3  Se abordan las excepciones y anomalías identificadas durante el  4<br>proceso de revisión.<br>**----- End of picture text -----**<br>


©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

38 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**10.5**Se conserva el historial del registro de auditoría y está disponible para su<br>análisis.|||||||
|**10.5.1**Conserve el historial de los registros de auditoría durante 12 meses<br>como mínimo, teniendo al menos los tres últimos meses inmediatamente<br>disponibles para su análisis.||||4|||
|**10.6**Los mecanismos de sincronización de la hora apoyan una configuración de<br>hora coherente en todos los sistemas.|||||||
|**10.6.1**Los relojes del sistema y la hora están sincronizados usando<br>tecnología de sincronización de tiempo.||||4|||
|**10.6.2**Los sistemas están configurados con la hora correcta y consistente<br>como sigue:<br>•Uno o más servidores de tiempo designados están en uso.<br>•Solo los servidores de hora central designados reciben la hora de<br>fuentes externas.<br>•La hora recibida de fuentes externas se basa en la Hora Atómica<br>Internacional u Hora Universal Coordinada (UTC).<br>•Los servidores de tiempo designados aceptan actualizaciones de tiempo<br>solo de fuentes externas específicas aceptadas por la industria.<br>•Cuando hay más de un servidor de tiempo designado, los servidores de<br>tiempo se emparejan entre sí para mantener la hora exacta.<br>•Los sistemas internos reciben información de la hora solo de los<br>servidores de hora central designados.||||4|||
|**10.6.3**La configuración de sincronización de la hora y los datos están<br>protegidos de la siguiente manera:<br>•El acceso a los datos de tiempo está restringido solo al personal con una<br>necesidad de negocio.<br>•Cualquier cambio en la configuración de tiempo en sistemas críticos se<br>registra, monitorea y verifica.||||4|||



- El acceso a los datos de tiempo está restringido solo al personal con una necesidad de negocio. 

- Cualquier cambio en la configuración de tiempo en sistemas críticos se registra, monitorea y verifica. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

39 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



**10.7** Las fallas de los sistemas de control de seguridad críticos se detectan, informan y atienden con prontitud. 

**10.7.1** _**Requisito adicional sólo para proveedores de servicios:**_ Las 4 fallas de los sistemas de control de seguridad críticos se detectan, alertan y abordan con prontitud, incluyendo entre otras, las fallas de los siguientes sistemas de control de seguridad críticos: • Controles de seguridad de la red.  Controles de seguridad de la red. • IDS/IPS.  IDS/IPS. • FIM.  FIM. • Soluciones antimalware.  Soluciones antimalware. • Controles de acceso físico.  Controles de acceso físico. • Controles de Ingreso lógico.  Controles de Ingreso lógico. • Mecanismos de registro de auditoría.  Mecanismos de registro de auditoría. • Controles de segmentación (si se utilizan).  Controles de segmentación (si se utilizan). **10.7.2** 4 

- Controles de seguridad de la red.  Controles de seguridad de la red. 

- IDS/IPS.  IDS/IPS. 

- FIM.  FIM. 

- Soluciones antimalware.  Soluciones antimalware. 

- Controles de acceso físico.  Controles de acceso físico. 

- Controles de Ingreso lógico.  Controles de Ingreso lógico. 

- Mecanismos de registro de auditoría.  Mecanismos de registro de auditoría. 

- Controles de segmentación (si se utilizan).  Controles de segmentación (si se utilizan). 

**10.7.2** Las fallas de los sistemas de control de seguridad críticos se detectan, alertan y abordan con prontitud, incluidas, entre otras, las fallas de los siguientes sistemas de control de seguridad críticos: 

- Controles de seguridad de la red. 

- IDS/IPS. 

- Cambiar los mecanismos de detección. 

- Soluciones antimalware. 

- Controles de acceso físico. 

- Controles de Ingreso lógico. 

- Mecanismos de registro de auditoría. 

- Controles de segmentación (si se utilizan). 

- Mecanismos de revisión del registro de auditoría. 

- Herramientas de prueba de seguridad automatizadas (si se utilizan). 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

40 

|||||**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**||||||||
||**1**|**2**|**3**|**3**|**4**|**5**|**6**|
|**10.7.3**Las fallas de cualquier sistema de control de seguridad crítico se|||||4|||
|responden con prontitud, incluidas, entre otras, las siguientes:||||||||



- Restaurando las funciones de seguridad. 

- Identificando y documentando la duración (fecha y hora de principio a fin) de la falla de seguridad. 

- Identificando y documentando las causas de la falla y documentando el remedio requerido. 

- Identificando y abordando cualquier problema de seguridad que surgió durante la falla. 

- Determinar si se requieren más acciones como resultado de la falla de seguridad. 

- Implementar controles para evitar que se repita la causa de la falla. 

- Reanudación del monitoreo de los controles de seguridad. 

_Este es un requisito PCI DSS v3.2.1que aplica solo a los proveedores de servicios. Este Requisito es la mejor práctica para todas las demás entidades hasta el 31 de marzo de 2025; consulte las Notas de Aplicabilidad en PCI DSS para más detalles._ 

## **Requisito 11: Poner a Prueba Regularmente la Seguridad de los Sistemas y de las Redes** 

**11.1** Se definen y comprenden los procesos y mecanismos para probar periódicamente la seguridad de los sistemas y redes. 

**11.1.1** Todas las políticas de seguridad y procedimientos operativos que se 6 identifican en el Requisito 11 son: • Documentados.  Documentados. • Actualizados.   Actualizados. • En uso.  En uso. • Conocidos por todas las partes involucradas.  Conocidos por todas las partes involucradas. **11.1.2** Los roles y responsabilidades para realizar las actividades del 6 Requisito 11 son documentados, asignados y comprendidos. 

- Documentados.  Documentados. 

- Actualizados.   Actualizados. 

- En uso.  En uso. 

- Conocidos por todas las partes involucradas.  Conocidos por todas las partes involucradas. 

**11.2** Se identifican y controlan los puntos de acceso inalámbricos y se abordan los puntos de acceso inalámbricos no autorizados. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

41 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**11.2.1**Los puntos de acceso inalámbricos autorizados y no autorizados se<br>gestionan de la siguiente manera:<br>•Se comprueba la existencia de puntos de acceso inalámbricos_(Wi-Fi)_<br>para,<br>•Detectar e identificar todos los puntos de acceso inalámbricos<br>autorizados y no autorizados,<br>•Que la verificación, detección e identificación ocurre al menos cada tres<br>meses.<br>•Si se utiliza la supervisión automatizada, se notifica al personal mediante<br>la generación de alertas.||||4|||
|**11.2.2**Se mantiene un inventario de los puntos de acceso inalámbricos<br>autorizados, incluyendo una justificación de negocio documentada.||||4|||
|**11.3**Las vulnerabilidades externas e internas se identifican, se priorizan y se<br>abordan periódicamente.|||||||
|**11.3.1**Los escaneos de vulnerabilidad interna se realizan de la siguiente<br>manera:<br>•Al menos una vez cada tres meses.<br>•Se resuelven las vulnerabilidades de alto riesgo o críticas (según las<br>clasificaciones de riesgo de vulnerabilidad de la entidad definidas en el<br>Requisito 6.3.1).<br>•Se realizan re-escaneos que confirman que se han resuelto todas las<br>vulnerabilidades críticas y de alto riesgo (como se indicó anteriormente).<br>•La herramienta de escaneo se mantiene actualizada con la información<br>más reciente sobre vulnerabilidades.<br>•Los escaneos son realizados por personal calificado con la<br>independencia organizacional del probador.||2|||||
|**11.3.1.1**Todas las demás vulnerabilidades aplicables (aquellas que<br>no se clasifican como vulnerabilidades de alto riesgo o<br>vulnerabilidades críticas según las clasificaciones de riesgo de<br>vulnerabilidad de la entidad definidas en el Requisito 6.3.1) se<br>gestionan de la siguiente manera:<br>•Abordado en función del riesgo definido en el análisis de riesgo<br>específico de la entidad, que se realiza de acuerdo con todos los<br>elementos especificados en el Requisito 12.3.1.<br>•Los re-escaneos se realizan según sea necesario.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||2|||||



- Abordado en función del riesgo definido en el análisis de riesgo específico de la entidad, que se realiza de acuerdo con todos los elementos especificados en el Requisito 12.3.1. 

- Los re-escaneos se realizan según sea necesario. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

42 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**11.3.1.2**Los escaneos de vulnerabilidad interna se realizan mediante<br>escaneos autenticados como sigue:<br>•Los sistemas que no pueden aceptar credenciales para los<br>escaneos autentificados están documentados.<br>•Se utilizan suficientes privilegios para aquellos sistemas que<br>aceptan credenciales para escanear.<br>•Si las cuentas utilizadas para el escaneo autenticado se pueden<br>utilizar para el inicio de sesión interactivo, estas se gestionan de<br>acuerdo con el Requisito 8.2.2.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||2|||||
|**11.3.1.3**Los escaneos de vulnerabilidad interna se realizan después<br>de cualquier cambio significativo como sigue:<br>•Se resuelven las vulnerabilidades de alto riesgo o críticas (según<br>las clasificaciones de riesgo de vulnerabilidad de la entidad<br>definidas en el Requisito 6.3.1).<br>•Los re-escaneos se realizan según sea necesario.<br>•Los escaneos son realizados por personal cualificado con la<br>independencia organizacional del probador (no se requiere que<br>sea un QSA o ASV).||2|||||
|**11.3.2**Los escaneos de vulnerabilidad externa se realizan de la siguiente<br>manera:<br>•Al menos una vez cada tres meses.<br>•Por parte de un Proveedor de Escaneo Aprobado por PCI SSC (ASV).<br>•Las vulnerabilidades se resuelven y se cumple con los requisitos de la<br>_Guía del Programa ASV._<br>•Se realizan nuevos escaneos según sea necesario para confirmar que<br>las vulnerabilidades se han resuelto de acuerdo con los requisitos de la<br>_Guía del Programa ASV_de escaneos aprobados.||2|||||
|**11.3.2.1**Los escaneos de vulnerabilidad externa se realizan después<br>de cualquier cambio significativo de la siguiente manera:<br>•Se resuelven las vulnerabilidades calificadas con 4.0 o más por<br>CVSS.<br>•Los re-escaneos se realizan según sea necesario.<br>•Los escaneos son realizados por personal cualificado con la<br>independencia organizacional del probador (no se requiere que sea<br>un QSA o ASV).||2|||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

43 

**Requisitos de PCI DSS v4.0.1** 

**==> picture [144 x 31] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|1|2|3|4|5|6|

**----- End of picture text -----**<br>


**11.4** Las pruebas de penetración externas e internas se realizan con regularidad y se corrigen las vulnerabilidades explotables y las debilidades de seguridad. 

- **11.4.1** La entidad define, documenta e implementa una metodología de prueba de penetración, que incluye: 

2 

- Enfoques de pruebas de penetración aceptados por la industria. 

- Cobertura para todo el perímetro de CDE y sus sistemas críticos. 

- Pruebas tanto dentro como fuera de la red. 

- Pruebas para validar cualquier control de segmentación y reducción del alcance. 

- Pruebas de penetración a nivel de la aplicación para identificar, como mínimo, las vulnerabilidades enumeradas en el Requisito 6.2.4. 

- Las pruebas de penetración a nivel de red que abarcan todos los componentes que apoyan las funciones de red y los sistemas operativos. 

- Revisión y consideración de amenazas y vulnerabilidades experimentadas en los últimos 12 meses. 

- Enfoque documentado para evaluar y abordar el riesgo que plantean las vulnerabilidades explotables y las debilidades de seguridad encontradas durante las pruebas de penetración. 

- Retención de los resultados de las pruebas de penetración y los resultados de las actividades de remediación durante al menos 12 meses. 

- **11.4.2** Se realizan pruebas de penetración interna: 2 • Según la metodología definida por la entidad. • Al menos una vez cada 12 meses. • Después de cualquier actualización o cambio significativo de infraestructura o aplicación. 

- • Por un recurso interno calificado o un tercero externo calificado. • El asesor cuenta con independencia organizacional (no se requiere que sea un QSA o ASV). 

- **11.4.3** 2 

- **11.4.3** Se realizan pruebas de penetración externa: • Según la metodología definida por la entidad. • Al menos una vez cada 12 meses. 

- Después de cualquier actualización o cambio significativo de infraestructura o aplicación. 

- Por un recurso interno calificado o un tercero externo calificado. 

- El asesor cuenta con independencia organizacional (no se requiere que sea un QSA o ASV). 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

44 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**11.4.4**Las vulnerabilidades explotables y las debilidades de seguridad<br>encontradas durante las pruebas de penetración se corrigen de la siguiente<br>manera:<br>•De acuerdo con la evaluación de la entidad, del riesgo que representa el<br>problema de seguridad según se define en el Requisito 6.3.1.<br>•La prueba de penetración se repite para verificar las correcciones.||2|||||
|**11.4.5**Si la segmentación se utiliza para aislar el CDE de otras redes, las<br>pruebas de penetración se realizan en los controles de segmentación de la<br>siguiente manera:<br>•Al menos una vez cada 12 meses y después de cualquier cambio en los<br>controles/métodos de segmentación.<br>•Cubriendo todos los controles/métodos de segmentación en uso.<br>•De acuerdo con la metodología de prueba de penetración definida por la<br>entidad.<br>•Confirmar que los controles/métodos de segmentación son operativos y<br>eficientes, y aislar al CDE de todos los sistemas fuera del ámbito.<br>•Confirmar la efectividad de cualquier uso de aislamiento para separar<br>sistemas con diferentes niveles de seguridad (ver Requisito 2.2.3).<br>•Realizado por un recurso interno calificado o un tercero externo<br>calificado.<br>•El asesor cuenta con independencia organizacional (no se requiere que<br>sea un QSA o ASV).||2|||||
|**11.4.6****_Requisito adicional sólo para proveedores de servicios:_**Si la<br>segmentación se utiliza para aislar el CDE de otras redes, las pruebas de<br>penetración se realizan en los controles de segmentación de la siguiente<br>manera:<br>•Al menos una vez cada seis meses y después de cualquier cambio en<br>los controles/métodos de segmentación.<br>•Cubriendo todos los controles/métodos de segmentación en uso.<br>•De acuerdo con la metodología de prueba de penetración definida por la<br>entidad.<br>•Confirmar que los controles/métodos de segmentación son operativos y<br>eficientes, y aislar al CDE de todos los sistemas fuera del ámbito.<br>•Confirmar la efectividad de cualquier uso de aislamiento para separar<br>sistemas con diferentes niveles de seguridad (ver Requisito 2.2.3).<br>•Realizado por un recurso interno calificado o un tercero externo<br>calificado.<br>•El asesor cuenta con independencia organizacional (no se requiere que<br>sea un QSA o ASV).||2|||||



|•Al menos una vez cada seis meses y después de cualquier cambio en<br>•Cubriendo todos los controles/métodos de segmentación en uso.|Al menos una vez cada seis meses y después de cualquier cambio en<br>los controles/métodos de segmentación.<br>Cubriendo todos los controles/métodos de segmentación en uso.|
|---|---|
|•De acuerdo con la metodología de prueba de penetración definida por la|De acuerdo con la metodología de prueba de penetración definida por la|
||entidad.|
|•Confirmar que los controles/métodos de segmentación son operativos y|Confirmar que los controles/métodos de segmentación son operativos y|
||eficientes, y aislar al CDE de todos los sistemas fuera del ámbito.|
|•Confirmar la efectividad de cualquier uso de aislamiento para separar|Confirmar la efectividad de cualquier uso de aislamiento para separar|
||sistemas con diferentes niveles de seguridad (ver Requisito 2.2.3).|
|•Realizado por un recurso interno calificado o un tercero externo|Realizado por un recurso interno calificado o un tercero externo|
||calificado.|
|•El asesor cuenta con independencia organizacional (no se requiere que|El asesor cuenta con independencia organizacional (no se requiere que|
||sea un QSA o ASV).|



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

45 

**==> picture [404 x 55] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|
|2|

**----- End of picture text -----**<br>


**==> picture [320 x 46] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||
|---|---|
|11.4.7|Requisito adicional sólo para proveedores de servicios|
|multiusuario:|Los proveedores de servicios multiusuario apoyan a sus|
|clientes para las pruebas de penetración externas según los Requisitos|
|11.4.3 y 11.4.4.|

**----- End of picture text -----**<br>


_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**11.5** Las intrusiones de red y los cambios inesperados de archivos se detectan y se responden. 

**11.5.1** Las técnicas de detección y/o prevención de intrusiones se utilizan para detectar y/o impedir intrusiones en la red de la siguiente manera: 

- Todo el tráfico se supervisa en el perímetro del CDE. 

- Todo el tráfico se supervisa en los puntos críticos del CDE. 

- Se envía una alerta al personal indicando las sospechas de situaciones comprometidas. 

- Todos los motores de detección y prevención de intrusiones, las líneas de base y las firmas se mantienen actualizadas. 

**11.5.1.1** _**Requisito adicional sólo para proveedores de servicios:**_ Las técnicas de detección-intrusión y/o intrusión-prevención detectan, alertan/impiden y abordan los canales de comunicación de malware encubierto. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**11.5.2** Un mecanismo de detección de cambios (por ejemplo, herramientas de monitoreo de integridad de archivos) se despliega como sigue: 

2 2 4 

- Para alertar al personal sobre modificaciones no autorizadas (incluyendo cambios, adiciones y eliminaciones) de archivos críticos. 

- Para realizar comparaciones de archivos críticos al menos una vez por semana. 

**11.6** Se detectan los cambios no autorizados en las páginas de pago se detectan y se responden. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

46 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**11.6.1**El mecanismo de detección de cambios y manipulaciones se||2|||||||
|despliega de la siguiente manera:|||||||||
|•Para enviar alertas al personal sobre modificaciones no autorizadas|||||||||
|(incluyendo indicadores de situaciones comprometidas, cambios,|||||||||
|adiciones y supresiones) en los encabezados HTTP que afectan la|||||||||
|seguridad y en el contenido de_script_de las páginas de pago tal y como|||||||||
|las recibe el navegador del consumidor.|||||||||
|•El mecanismo está configurado para evaluar el encabezamiento HTTP y|||||||||
|la página de pago recibidas.|||||||||



- Las funciones del mecanismo se realizan de la siguiente manera: 

   - Al menos semanalmente **O** 

   - – Periódicamente, (a una frecuencia definida en el análisis de riesgos específico de la entidad, el cual se desarrolla de acuerdo a todos los elementos especificados en el Requisito 12.3.1). 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

## **Requisito 12: Respaldar la Seguridad de la Informácion con Políticas y Programas Organizacionales** 

**12.1** Una política integral de seguridad de la información que rija y proporcione orientación para la protección de los activos de información de la entidad es actualizada y bien conocida. 

|**12.1.1**Una política general de seguridad informática es:||||||6|
|---|---|---|---|---|---|---|
|•Establecida.|||||||
|•Publicada.|||||||
|•Mantenida.|||||||
|•Difundida a todo el personal relevante, así como a los proveedores y|||||||
|socios comerciales relevantes.|||||||
|**12.1.2**La política de seguridad de la información es:||||||6|
|•Revisada al menos una vez cada 12 meses.|||||||
|•Actualizada según sea necesario para reflejar los cambios en los|||||||
|objetivos de negocios o en los riesgos para el entorno.|||||||
|**12.1.3**La política de seguridad define claramente los roles y||||||6|
|responsabilidades de seguridad de la información para todo el personal, y|||||||
|todo el personal conoce y reconoce sus responsabilidades en materia de|||||||
|seguridad de la información.|||||||



- Establecida. 

- Revisada al menos una vez cada 12 meses. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

47 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**12.1.4**La responsabilidad de la seguridad de la información se asigna||||||||6|
|formalmente a un director de seguridad de la información o a otro miembro|||||||||
|de la dirección ejecutiva con conocimientos de seguridad de la información.|||||||||
|**12.2**Se definen e implementan políticas de uso aceptable para tecnologías de|||||||||
|usuario final.|||||||||
|**12.2.1**Se documentan e implementan políticas de uso aceptable para||||||||6|
|tecnologías orientadas al usuario final, que incluyen:|||||||||
|•Aprobación explícita por las partes autorizadas.|||||||||
|•Usos aceptables de la tecnología.|||||||||
|•Lista de productos aprobados por el comerciante para uso de los|||||||||
|empleados, incluidos hardware y software.|||||||||
|**12.3**Los riesgos para el entorno de datos de tarjetahabiente se identifican,|||||||||
|evalúan y gestionan formalmente.|||||||||
|**12.3.1**Para cada requisito de PCI DSS que especifique completar un||2|||||||
|análisis de riesgo específico, el análisis se documenta e incluye:|||||||||



- Identificación de los activos a proteger. 

- Identificación de las amenazas contra las que protege el requisito. 

- Identificación de factores que contribuyen a la probabilidad y/o impacto de que se materialice una amenaza. 

- Análisis resultante que determine e incluya la justificación de, cómo la frecuencia o los procesos definidos por la entidad para cumplir el requisito minimizan la probabilidad y/o el impacto de que se materialice la amenaza. 

- Revisión de cada análisis de riesgo específico al menos una vez cada 12 meses para determinar si los resultados siguen siendo válidos o si se necesita un análisis de riesgo actualizado. 

- Realización de análisis de riesgos actualizados cuando sea necesario, según lo determinado por la revisión anual. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

48 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**12.3.2**Se realiza un análisis de riesgos específico para cada Requisito PCI<br>DSS que la entidad reúne con el enfoque personalizado, que incluye:<br>•Evidencia documentada que detalla cada elemento se especifica en el<br>Anexo D: Enfoque Personalizado (incluyendo, como mínimo, una matriz<br>de controles y un análisis de riesgos).<br>•Aprobación de las evidencias documentadas por parte de la alta<br>dirección.<br>•La realización del análisis de riesgos específico al menos una vez cada<br>12 meses.||2|||||
|**12.3.3**Los conjuntos de cifrado criptográfico y los protocolos en uso se<br>documentan y revisan al menos una vez cada 12 meses, incluyendo al<br>menos lo siguiente:<br>•Un inventario actualizado de todos los protocolos y conjuntos de cifrado<br>criptográfico en uso, incluyendo su propósito y dónde se utilizan.<br>•Monitoreo activo de las tendencias de la industria con respecto a la<br>viabilidad continua de todos los protocolos y conjuntos de cifrado<br>criptográfico en uso.<br>•Documentación de un plan para responder a los cambios anticipados en<br>las vulnerabilidades criptográficas.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._||||||6|
|**12.3.4**Las tecnologías de hardware y software en uso se revisan al menos<br>una vez cada 12 meses, incluyendo al menos lo siguiente:<br>•Análisis de que las tecnologías continúan recibiendo correcciones de<br>seguridad por parte de los proveedores con prontitud.<br>•Análisis de que las tecnologías continúan apoyando (y no imposibilitan)<br>la conformidad PCI DSS de la entidad.<br>•Documentación de cualquier anuncio o tendencia de la industria<br>relacionada con una tecnología, como cuando un proveedor ha<br>anunciado planes para el "fin de la vida útil" de una tecnología.<br>•Documentación de un plan, aprobado por la alta gerencia, para remediar<br>tecnologías obsoletas, incluidas aquellas para las que los proveedores<br>han anunciado planes de "fin de vida útil".<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._||||||6|



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

49 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**12.4**Gestión del cumplimiento con PCI DSS.|||||||
|**12.4.1****_Requisito adicional solo para proveedores de servicios:_**La<br>responsabilidad es establecida por la gerencia ejecutiva para la protección<br>de datos de tarjetahabiente y un programa de conformidad PCI DSS que<br>incluye:<br>•Responsabilidad general para mantener la conformidad PCI DSS.<br>•Definición de un estatuto para un programa de conformidad PCI DSS y<br>un reporte a la dirección ejecutiva.||||||6|
|**12.4.2****_Requisito adicional solo para proveedores de servicios:_**Las<br>revisiones se realizan al menos una vez cada tres meses para confirmar<br>que el personal está realizando sus tareas de acuerdo con todas las<br>políticas de seguridad y los procedimientos operativos. Las revisiones son<br>realizadas por personal distinto al responsable de realizar la tarea en<br>cuestión e incluyen, entre otras, las siguientes tareas:<br>•Revisiones de registros diarios.<br>•Revisiones de configuración para controles de seguridad de la red.<br>•Aplicación de estándares de configuración a nuevos sistemas.<br>•Respuesta a las alertas de seguridad.<br>•Procesos de gestión del cambio.||||||6|
|**12.4.2.1****_Requisito adicional solo para proveedores de servicios:_**<br>Las revisiones realizadas de acuerdo con el Requisito 12.4.2 se<br>documentan para incluir:<br>•Resultados de las revisiones.<br>•Acciones de remediación documentadas tomadas para cualquier<br>tarea que no se haya realizado en el Requisito 12.4.2.<br>•Revisión y aprobación de los resultados por parte del personal al<br>que se le haya asignado la responsabilidad del programa de<br>conformidad PCI DSS.||||||6|
|**12.5**Documentación y validación del alcance PCI DSS.|||||||
|**12.5.1**Se mantiene y actualiza un inventario de los componentes del<br>sistema que están dentro del alcance PCI DSS, incluyendo una descripción<br>de su función/uso.||2|||||



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

50 

**==> picture [404 x 55] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|
|1|

**----- End of picture text -----**<br>


- **12.5.2** El alcance PCI DSS es documentado y confirmado por la entidad al menos una vez cada 12 meses y ante cambios significativos en el entorno dentro del alcance. Como mínimo, la validación del alcance incluye: 

- Identificar todos los flujos de datos para las diversas etapas de pago (por ejemplo, autorización, captura de la liquidación, devoluciones y reembolsos) y canales de aceptación (por ejemplo, tarjeta física, tarjeta virtual y comercio electrónico). 

- Actualizar todos los diagramas de flujo de datos según el Requisito 1.2.4. 

- Identificar todas las ubicaciones donde se almacenan, procesan y transmiten datos del titular de la tarjeta, incluidos, entre otros: 1) cualquier ubicación fuera del CDE definida actualmente, 2) aplicaciones que procesan CHD, 3) transmisiones entre sistemas y redes, y 4) copias de seguridad de archivos. 

- Identificar todos los componentes del sistema en el CDE, conectados al CDE o que podrían afectar la seguridad del CDE. 

- Identificar todos los controles de segmentación en uso y los entornos desde los que se segmenta el CDE, incluida la justificación de los entornos que están fuera del alcance. 

- Identificar todas las conexiones de entidades de terceros con acceso al CDE. 

- Confirmar que todos los flujos de datos identificados, datos del titular de la tarjeta, componentes del sistema, controles de segmentación y conexiones de terceros con acceso al CDE están incluidos en el alcance. 

**12.5.2.1** _**Requisito adicional solo para proveedores de servicios:**_ El alcance PCI DSS es documentado y confirmado por la entidad al menos una vez cada seis meses y ante cambios significativos en el entorno dentro del alcance. Como mínimo, la validación del alcance incluye todos los elementos especificados en el Requisito 12.5.2. 

1 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**12.5.3** _**Requisito adicional solo para proveedores de servicios:**_ Los cambios significativos en la estructura organizativa dan como resultado una revisión documentada (interna) del impacto en el alcance PCI DSS y la aplicabilidad de los controles; los resultados se comunican a la dirección ejecutiva. 

6 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

51 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**12.6**La educación en concienciación sobre la seguridad es una actividad<br>continua.|||||||
|**12.6.1**Se implementa un programa formal de concientización sobre<br>seguridad para que todo el personal conozca la política y los<br>procedimientos de seguridad de la información a de la entidad, y el rol del<br>personal en la protección de los datos de tarjetahabiente.||||||6|
|**12.6.2**El programa de concientización sobre seguridad es:<br>•Revisado al menos una vez cada 12 meses, y<br>•Actualizado según sea necesario para abordar cualquier nueva<br>amenaza y vulnerabilidad que pueda afectar la seguridad de datos de<br>tarjetahabiente y/o datos de autenticación sensibles de la entidad, o la<br>información proporcionada al personal sobre sus funciones en lo<br>concerniente a la protección de los datos de tarjetahabiente.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de_<br>_2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más_<br>_detalles._||||||6|
|**12.6.3**El personal recibe capacitación sobre seguridad de la siguiente<br>manera:<br>•Al momento de la contratación y al menos una vez cada 12 meses.<br>•Se utilizan múltiples métodos de comunicación.<br>•El personal reconoce al menos una vez cada 12 meses que ha leído y<br>comprendido las políticas y los procedimientos de seguridad de la<br>información.||||||6|
|**12.6.3.1**El entrenamiento de concientización de seguridad incluye la<br>concientización ante amenazas y vulnerabilidades que podrían<br>impactar la seguridad de datos de tarjetahabiente y/o datos de<br>autenticación sensibles, incluyendo, pero no limitado a:<br>•Phishing y ataques relacionados.<br>•Ingeniería social.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||||||6|
|**12.6.3.2**La capacitación en concientización sobre seguridad incluye la<br>concientización sobre el uso aceptable de las tecnologías de usuario<br>final de acuerdo con el requisito 12.2.1.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||||||6|



©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

52 

**==> picture [522 x 541] intentionally omitted <==**

**----- Start of picture text -----**<br>
Hito<br>Requisitos de PCI DSS v4.0.1<br>1  2  3  4  5  6<br>12.7  El personal es evaluado para reducir los riesgos de amenazas internas.<br>12.7.1  El personal potencial que tendrá acceso al CDE es investigado, en el  6<br>marco de las limitaciones que establecen las leyes locales, antes de su<br>contratación, a fin de minimizar el riesgo de ataques provenientes de<br>fuentes internas.<br>12.8  Gestión del riesgo de los activos de información asociados a las relaciones<br>con proveedores de servicios externos (TPSP).<br>12.8.1  Se mantiene una lista de todos los proveedores de servicios de  2<br>terceros (TPSP) con los que se comparten datos del titular de la tarjeta o<br>que podrían afectar a la seguridad de los datos del titular de la tarjeta,<br>incluyendo una descripción para cada uno de los servicios prestados.<br>12.8.2  Se mantienen acuerdos escritos con los TPSP de la siguiente  2<br>manera:<br>• Se mantienen acuerdos escritos con todos los TPSP con los que se<br>comparten datos del titular de la tarjeta o que podrían afectar la<br>seguridad del CDE.<br>• Los acuerdos escritos incluyen el reconocimiento por parte de los TPSP<br>de que los TPSP son responsables por la seguridad de los datos del<br>titular de la tarjeta que los TPSP poseen o almacenan, procesan o<br>transmiten en nombre de la entidad, o en la medida en que puedan<br>afectar a la seguridad de los datos tarjetahabiente o datos de<br>autenticación sensibles de la entidad.<br>12.8.3  Se implementa un proceso establecido para contratar a los TPSP,  2<br>incluyendo la debida diligencia antes de la contratación.<br>12.8.4  Se implementa un programa para monitorear el estado de  2<br>conformidad PCI DSS de los TPSP al menos una vez cada 12 meses.<br>12.8.5  Se mantiene información sobre qué requisitos PCI DSS gestiona  2<br>cada TPSP, cuáles gestiona la entidad y cualquiera que se comparta entre<br>el TPSP y la entidad.<br>12.9  Los proveedores de servicios externos (TPSP) apoyan la conformidad PCI<br>DSS de sus clientes.<br>**----- End of picture text -----**<br>


©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

53 

**==> picture [404 x 154] intentionally omitted <==**

**----- Start of picture text -----**<br>
|||||||
|---|---|---|---|---|---|
|Hito|
|Requisitos de PCI DSS v4.0.1|
|1|2|3|4|5|6|
|Los|2|
|Los|2|

**----- End of picture text -----**<br>


**12.9.1** _**Requisito adicional solo para proveedores de servicios:**_ Los TPSP proporcionan acuerdos por escrito a los clientes que incluyen el reconocimiento de que los TPSP son responsables de la seguridad de los datos de las cuentas que el TPSP posee o que almacena, procesa o transmite en nombre del cliente, o en la medida en que el TPSP pueda afectar a la seguridad de los datos tarjetahabiente y/o datos de autenticación sensibles del cliente. **12.9.2** _**Requisito adicional solo para proveedores de servicios:**_ Los TPSP apoyan las solicitudes de información de sus clientes para cumplir con los Requisitos 12.8.4 y 12.8.5 proporcionando lo siguiente a pedido del cliente: 

- Información del estado de cumplimiento PCI DSS (Requisito 12.8.4). 

- Información sobre qué requisitos de PCI DSS son responsabilidad del TPSP y cuáles son responsabilidad del cliente, incluyendo las responsabilidades compartidas (Requisito 12.8.5), para cualquier servicio que preste el TPSP que cumpla uno o varios requisitos de la PCI DSS en nombre de los clientes o que pueda afectar a la seguridad de los datos tarjetahabiente y/o datos de autenticación sensibles del cliente. 

**12.10** Respuesta inmediata a incidentes de seguridad sospechosos y confirmados que podrían afectar al CDE. 

**12.10.1** Existe un plan de respuesta a incidentes y está listo para activarse en caso de sospecha o confirmación de un incidente de seguridad. El plan incluye, pero no se limita a: 

2 

- Funciones, responsabilidades y estrategias de comunicación y contacto en caso de sospecha o confirmación de un incidente de seguridad, incluyendo la notificación de marcas de pago y adquirentes, como mínimo. 

- Procedimientos de respuesta a incidentes con actividades específicas de contención y mitigación para diferentes tipos de incidentes. 

- Procedimientos de recuperación y continuidad del negocio. 

- Procesos de apoyo de datos. 

- Análisis de requisitos legales para reportar situaciones comprometidas. 

- Cobertura y respuestas de todos los componentes críticos del sistema. 

- Referencia o inclusión de procedimientos de respuesta a incidentes de las marcas de pago. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

54 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**12.10.2**Al menos una vez cada 12 meses, el plan de respuesta a<br>incidentes de seguridad es:<br>•Revisado y el contenido se actualiza según sea necesario.<br>•Probado, incluyendo todos los elementos enumerados en el Requisito<br>12.10.1.||2|||||
|**12.10.3**Se designa personal específico para estar disponible las 24 horas<br>del día, los 7 días de la semana a fin de responder a incidentes de<br>seguridad sospechosos o confirmados.||2|||||
|**12.10.4**El personal responsable de responder a incidentes de seguridad<br>sospechados y confirmados recibe capacitación adecuada y periódica<br>sobre sus responsabilidades en cuanto a la respuesta a incidentes.||2|||||
|**12.10.4.1**La frecuencia de la capacitación periódica del personal de<br>respuesta a incidentes es definida según el análisis de riesgos<br>específico de la entidad, que se realiza de acuerdo con todos los<br>elementos especificados en el requisito 12.3.1.<br>_Este requisito es la mejor práctica recomendada hasta el 31 de marzo_<br>_de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener_<br>_más detalles._||2|||||
|**12.10.5**El plan de respuesta a incidentes de seguridad incluye el monitoreo<br>y la respuesta a las alertas de los sistemas de monitoreo de seguridad,<br>incluyendo, pero no limitado a:<br>•Sistemas de detección y prevención de intrusiones.<br>•Controles de seguridad de la red.<br>•Mecanismos de detección de cambios en archivos críticos.<br>•El mecanismo de detección de cambios y manipulaciones en las páginas<br>de pago._Este punto es la mejor práctica recomendada hasta el 31 de_<br>_marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para_<br>_obtener más detalles._<br>•Detección de puntos de acceso inalámbricos no autorizados.||2|||||
|**12.10.6**El plan de respuesta a incidentes de seguridad se modifica y<br>evoluciona de acuerdo con las lecciones aprendidas y para incorporar los<br>desarrollos de la industria.||2|||||



- Revisado y el contenido se actualiza según sea necesario. 

- Probado, incluyendo todos los elementos enumerados en el Requisito 12.10.1. 

- Sistemas de detección y prevención de intrusiones. 

- Controles de seguridad de la red. 

- Mecanismos de detección de cambios en archivos críticos. 

- El mecanismo de detección de cambios y manipulaciones en las páginas de pago. _Este punto es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

- Detección de puntos de acceso inalámbricos no autorizados. 

**12.10.6** El plan de respuesta a incidentes de seguridad se modifica y evoluciona de acuerdo con las lecciones aprendidas y para incorporar los desarrollos de la industria. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

55 

|||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|||||||||
||**1**|**2**|**3**|**3**||**4**|**5**|**6**|
|**12.10.7**Existen procedimientos de respuesta a incidentes que se iniciarán||2|||||||
|cuando se detecten datos de PAN almacenados en un lugar inesperado, e|||||||||
|incluyen:|||||||||
|•Determinar qué hacer si se descubren datos de PAN fuera del CDE,|||||||||
|incluyendo su recuperación, eliminación segura y/o migración al CDE|||||||||
|actualmente definido, según corresponda.|||||||||



- Identificar si los datos de autenticación sensibles se almacenan con datos de PAN. 

- Determinar de dónde proceden los datos del titular de la tarjeta y cómo han llegaron donde no se esperaba. 

- Remediar fugas de datos o brechas en el proceso que llevaron a que los datos del titular de la tarjeta llegaran a una ubicación inesperada. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

## **Anexo A1: Requisitos Adicionales de PCI DSS para Proveedores de Servicios Multiusuario** 

**A1.1** Los proveedores de servicios multiusuario protegen y separan todos los entornos y datos de los clientes. 

**A1.1.1** La separación lógica se implementa de la siguiente manera: 

**A1.1.1** La separación lógica se implementa de la siguiente manera: 4 • El proveedor no puede ingresar a los entornos de sus clientes sin  El proveedor no puede ingresar a los entornos de sus clientes sin autorización. • Los clientes no pueden ingresar al entorno del proveedor sin  Los clientes no pueden ingresar al entorno del proveedor sin autorización. _Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ **A1.1.2** Los controles se implementan de modo que cada cliente solo tenga 4 permiso para ingresar a sus propios datos de tarjetahabiente y CDE. **A1.1.3** Los controles se implementan de modo que cada cliente solo pueda 4 ingresar a los recursos que se le han asignados. **A1.1.4** 2 

- El proveedor no puede ingresar a los entornos de sus clientes sin  El proveedor no puede ingresar a los entornos de sus clientes sin autorización. 

- Los clientes no pueden ingresar al entorno del proveedor sin  Los clientes no pueden ingresar al entorno del proveedor sin autorización. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**A1.1.4** La eficiencia de los controles de separación lógica utilizados para separar los entornos de los clientes se confirma al menos una vez cada seis meses mediante pruebas de penetración. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

56 

|||||||||**Hito**|**Hito**|**Hito**|||
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|**Requisitos de PCI DSS v4.0.1**|||||||||
||||||**1**|**2**|**3**|**3**||**4**|**5**|**6**|



**A1.2** Los proveedores de servicios multiusuario facilitan el registro y la respuesta a incidentes para todos los clientes. 

**A1.2.1** La función de registro de auditoría está habilitada para el entorno de 4 cada cliente de conformidad con el Requisito 10 PCI DSS, que incluye lo siguiente: • Los registros están habilitados para aplicaciones comunes de terceros.  Los registros están habilitados para aplicaciones comunes de terceros. • Los registros están activos de forma predeterminada.  Los registros están activos de forma predeterminada. • Los registros están disponibles para revisión solo por parte del cliente  Los registros están disponibles para revisión solo por parte del cliente propietario. • Las ubicaciones de los registros se comunican claramente al cliente  Las ubicaciones de los registros se comunican claramente al cliente propietario. • Los datos de registro y la disponibilidad son consistentes con el  Los datos de registro y la disponibilidad son consistentes con el Requisito 10 de los PCI DSS. **A1.2.2** Se implementan procesos o mecanismos para apoyar y/o facilitar 2 investigaciones forenses rápidas en caso de un incidente de seguridad sospechado o confirmado para cualquier cliente. **A1.2.3** 2 

- Los registros están habilitados para aplicaciones comunes de terceros.  Los registros están habilitados para aplicaciones comunes de terceros. 

- Los registros están activos de forma predeterminada.  Los registros están activos de forma predeterminada. 

- Los registros están disponibles para revisión solo por parte del cliente  Los registros están disponibles para revisión solo por parte del cliente propietario. 

- Las ubicaciones de los registros se comunican claramente al cliente  Las ubicaciones de los registros se comunican claramente al cliente propietario. 

- Los datos de registro y la disponibilidad son consistentes con el  Los datos de registro y la disponibilidad son consistentes con el Requisito 10 de los PCI DSS. 

**A1.2.3** Se implementan procesos o mecanismos para reportar y abordar vulnerabilidades e incidentes de seguridad presuntos o confirmados, incluyendo lo siguiente: 

- Los clientes pueden informar de forma segura los incidentes de seguridad y las vulnerabilidades al proveedor. 

- El proveedor aborda y repara los incidentes de seguridad y las vulnerabilidades sospechadas o confirmadas de acuerdo con el Requisito 6.3.1. 

_Este requisito es la mejor práctica recomendada hasta el 31 de marzo de 2025, consulte las Notas de Aplicabilidad de PCI DSS para obtener más detalles._ 

**Anexo A2: Requisitos Adicionales de PCI DSS Para Entidades que Utilizan SSL/ Primeras Versiones de TLS para Conexiones de Terminal POS POI Presencial con Tarjetas** 

**A2.1** Está confirmado que Los terminales POI que utilizan SSL y/o versiones iniciales de TLS no son susceptibles a explotaciones conocidas de SSL/TLS. 

**A2.1.1** Cuando los terminales POS POI en el comercio o en la ubicación de 2 aceptación de pagos usan SSL y/o primeras versiones de, la entidad confirma que los dispositivos no son susceptibles a ninguna vulnerabilidad conocida para esos protocolos. 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

57 

|**Requisitos de PCI DSS v4.0.1**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|**Hito**|
|---|---|---|---|---|---|---|
||**1**|**2**|**3**|**4**|**5**|**6**|
|**A2.1.2****_Requisito adicional sólo para proveedores de servicios:_**Todos<br>los proveedores de servicios con puntos de conexión existentes POS POI<br>que utilizan SSL y/o primeras versiones de TLS como se define en A2.1<br>cuentan con un Plan de Migración y Mitigación de Riesgos que incluye:<br>•Descripción del uso, incluidos los datos que se transmiten, los tipos y la<br>cantidad de sistemas que usan y/o apoyan SSL/primeras versiones de<br>TLS y el tipo de entorno.<br>•Resultados de la evaluación de riesgos y controles de reducción de<br>riesgos implementados.<br>•Descripción de procesos para monitorear nuevas vulnerabilidades<br>relacionadas con SSL/primeras versiones de TLS.<br>•Descripción de los procesos de control de cambios que se implementan<br>para garantizar que los SSL/primeras versiones de TLS no se<br>implementen en nuevos entornos.<br>•Descripción general del plan del proyecto de migración para reemplazar<br>los SSL/primeras versiones de TLS en una fecha futura.||2|||||
|**A2.1.3****_Requisito Solo Para Proveedores de Servicios:_**Todos los<br>proveedores de servicios brindan una oferta de servicios segura.||2|||||



- Descripción del uso, incluidos los datos que se transmiten, los tipos y la cantidad de sistemas que usan y/o apoyan SSL/primeras versiones de TLS y el tipo de entorno. 

- Resultados de la evaluación de riesgos y controles de reducción de riesgos implementados. 

- Descripción de procesos para monitorear nuevas vulnerabilidades relacionadas con SSL/primeras versiones de TLS. 

- Descripción de los procesos de control de cambios que se implementan para garantizar que los SSL/primeras versiones de TLS no se implementen en nuevos entornos. 

- Descripción general del plan del proyecto de migración para reemplazar los SSL/primeras versiones de TLS en una fecha futura. 

**A2.1.3** _**Requisito Solo Para Proveedores de Servicios:**_ Todos los proveedores de servicios brindan una oferta de servicios segura. 

_DECLARACIONES: La versión en inglés del texto en este documento tal y como se encuentra en el sitio web de PCI SSC deberá considerar se, para todos los efectos, como la versión oficial de estos documentos y, si existe cualquier ambigüedad o inconsistencia entre este texto y el texto en inglés, el texto en inglés en dicha ubicación es el que prevalecerá._ 

©2016 – 2025 PCI Security Standards Council LLC. La intención de este documento es proporcionar información complementaria, la cual no sustituye ni reemplaza los requisitos de ningún Estándar PCI SSC. Enero de 2025 

58 

