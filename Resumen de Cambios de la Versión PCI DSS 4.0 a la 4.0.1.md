# **Payment Card Industry Estándar de Seguridad de Datos** 

**Resumen de Cambios de la Versión PCI DSS 4.0 a la 4.0.1** Agosto de 2024 

## **Cambios en el Documento** 

|**Fecha**|**Revisión**|**Descripción**|
|---|---|---|
|Junio de||Versión inicial del Estándar PCI DSS v4.0 a v4.0.1 Resumen de los|
|2024||cambios.|
|Agosto de|1|Actualización de erratas para incluir 'Aclaración u Orientación' al Tipos de|
|2024||Cambio para el Requisito 6.5.5.|



_DECLARACIONES: La versión en inglés del texto en este documento tal y como se encuentra en el sitio web de PCI SSC deberá considerarse, para todos los efectos, como la versión oficial de estos documentos y, si existe cualquier ambigüedad o inconsistencia entre este texto y el texto en inglés, el texto en inglés en dicha ubicación es el que prevalecerá._ 

_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados._ 

_Agosto de 2024 Página i_ 

## **Tabla de Contenido** 

|**Tabla de Contenido**|**Tabla de Contenido**|
|---|---|
|**Cambios en el Documento .......................................................................................................................... i**||
|**1**|**Introducción .......................................................................................................................................... 1**|
|**2**|**Tipos de Cambio ................................................................................................................................... 2**|
|**3**|**Resumen de los Cambios Generales ................................................................................................. 2**|
|**4**|**Resumen de los Cambios Generales de las Secciones Introductorias de PCI DSS ..................... 2**|
|**5**|**Resumen de los Cambios de los Requisitos de PCI DSS ................................................................ 4**|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página ii_ 

_Página ii_ 

## **1  Introducción** 

Este documento proporciona el resumen y la descripción de los cambios de PCI DSS v4.0 a PCI DSS v4.0.1, pero no detalla todas las revisiones del documento. 

Las tablas incluidas de este documento resumen de los cambios de PCI DSS v4.0.1 con respecto a PCI DSS v4.0. El resumen está organizado de la siguiente forma: 

- _Tipos de Cambio_ - ofrece una visión general de los tipos de cambio. 

- _Resumen de cambios generales_ - incluye las descripciones de los cambios generales realizados a lo largo del mismo. 

- _Resumen de los Cambios Generales de las Secciones Introductorias de PCI DSS_ - incluye las descripciones de los cambios realizados en cada sección afectada. 

- _Resumen de Cambios en los Requisitos de PCI DSS_ - incluye las descripciones de los cambios realizados en los requisitos, los procedimientos de prueba y las directrices. 

_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 1_ 

_Página 1_ 

## **2 Tipos de Cambio** 

|**Tipos de Cambio**|**Definición**|
|---|---|
|Requisito en evolución|Cambios para garantizar que el estándar esté al día frente a las nuevas amenazas<br>y acerca de las tecnologías, y de los cambios en el sector de los pagos. Algunos<br>ejemplos son los requisitos o procedimientos de ensayo nuevos o modificados, o la<br>supresión de un requisito.<br>_Tenga en cuenta que en esta versión de PCI DSS no se produjeron cambios_<br>_clasificados como "Requisito en evolución"._|
|Guía de pruebas de<br>penetración|Actualizaciones de la redacción, explicación, definición, orientación adicional y/o<br>instrucción para aumentar la comprensión o proporcionar mayor información u<br>orientación acerca de un tema concreto.|
|Estructura o formato|Reorganización del contenido, incluyendo la combinación, separación y<br>renumeración de los requisitos para alinear el contenido.|



## **3 Resumen de los Cambios Generales** 

## **Descripción de los Cambios de PCI DSS v4.0 a v4.0.1** 

Corrija los errores tipográficos y otros errores menores (incluyendo los errores de formato, falta de encabezados, etc.). 

Actualizar y aclarar las orientaciones, incluyendo los cambios para alinearlas con publicaciones posteriores (por ejemplo, la guía de consulta rápida de la versión 4.0 y las preguntas frecuentes publicadas recientemente). 

Suprimir las Definiciones de la guía si también se incluyen en el glosario y remitirlas en su lugar al glosario (Anexo G). 

Agregar referencias al glosario en referencia los términos del glosario definidos recientemente y a los términos del glosario existentes que no tenían referencias anteriormente. 

Cambiar "afectar a la seguridad del CDE" por "afectar la seguridad de los datos de tarjetahabiente y/o datos de autenticación sensibles ", en todos los estándares donde proceda. 

Actualizar los procedimientos de la prueba para alinearlos con la redacción actualizada de los requisitos, según sea necesario. 

## **4 Resumen de los Cambios Generales de las Secciones Introductorias de PCI DSS** 

|**Sección PCI DSS**|**Cambio de PCI DSS v4.0 a PCI DSS v4.0.1**|
|---|---|
|Sección 3, Relación entre PCI DSS y los<br>Estándares de Software PCI SCC|Reformular la nota para reflejar el retiro de PA-DSS.<br>Actualizar "Proveedores de software validados" a "Proveedores de<br>software calificados".|
|Sección 4, Alcance de los requisitos de<br>PCI DSS|Añadir la subsección, Cuando se Reciben Accidentalmente Datos de<br>Tarjetahabiente y/o Datos de Autenticación Sensibles a través de un<br>Canal No Previsto, para incorporar el contenido incluido previamente en<br>el requisito 4.2.1 Nota de aplicabilidad.|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024_ 

_© 2024 PCI Security Standards Council, LLC. Todos los derechos reservados._ 

_Página 2_ 

|**Sección PCI DSS**|**Cambio de PCI DSS v4.0 a PCI DSS v4.0.1**|
|---|---|
|Sección 4, Alcance de los requisitos de<br>PCI DSS<br>Subsección, La Importancia de<br>Comprender las Responsabilidades Entre<br>los Clientes de TPSP y los TPSP|Aclarar que esta subsección se aplica si el TPSP presta un servicio que<br>cumplecon los requisitos PCI DSS de los clientes o si dicho servicio<br>puede afectar a la seguridad de los datos de tarjetahabiente y/o datos<br>de autenticación sensibles de los clientes.<br>Actualizar la referencia de Consejos y herramientas para comprender<br>PCI DSS v4.0 a Suplemento informativo: Garantía de seguridad de<br>terceros<br>Aclarar que los TPSP deben proporcionarles a los clientes<br>documentación acerca de las responsabilidades sólo si el TPSP presta un<br>servicio que cumple con los requisitos PCI DSS de los clientes o si dicho<br>servicio puede afectar a la seguridad de los datos de tarjetahabiente y/o<br>los datos de autenticación sensibles de los clientes.|
|Sección 7, Descripción de los Plazos<br>Utilizados en los Requisitos de PCI DSS|Aclarar la descripción de cambio significativo.<br>Por ejemplo, las poblaciones podrían dividirse en subpoblaciones según<br>las características que puedan afectar la coherencia de los requisitos<br>evaluados, tal como el uso de diferentes procesos o herramientas.|
|Sección 8, Enfoques para la i<br>Implementar y Validar de PCI DSS|Actualizar las referencias del enfoque personalizado para incluir las<br>Plantillas de muestra para Apoyar el enfoque personalizado en el sitio<br>web del PCI SSC.<br>Actualizar los colores y la fuente en la Imagen 4 y actualizar de<br>"Plantilla de informes ROC" a "Plantilla ROC".|
|Sección 13, Referencias Adicionales|Eliminar los enlaces URL.|
|Sección 14, Versiones PCI DSS|Eliminar la referencia de PCI DSS v3.2.1, ya que está retirada, y aclarar<br>que PCI DSS v4.0.1 es la versión actual.<br>Aclarar que las preguntas acerca del uso de las versiones anteriores de<br>PCI DSS deben dirigirse a las organizaciones que gestionan los<br>programas de cumplimiento.<br>Actualizar la tabla 6 para incluir la fecha de publicación de la v4.0.1, la<br>fecha de retiro de la v4.0 y la información de la v3.2.|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 3_ 

_Página 3_ 

## **5 Resumen de los Cambios de los Requisitos de PCI DSS** 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|**Requisito 1**|||
|1.2.2|Añadir_Propósito_, faltaba por error.|Aclaración u<br>Orientación|
|**Requisito 3**|||
|3.3.1|Actualización de la nota de aplicabilidad para emisores y empresas que prestan servicios de<br>emisión que cualquier almacenamiento de DUA se basa en "una necesidad empresarial<br>legítima y documentada". Añada una descripción de la necesidad empresarial legítima.<br>Añadir_Buenas Prácticas_para abordar cuándo pueda ser aceptable almacenar DUA en la<br>memoria no persistente.|Aclaración u<br>Orientación|
|3.3.1<br>3.3.1.1<br>3.3.1.2<br>3.3.1.3|Actualizar el requisito de "Los SAD no se retienen después de la autorización" a "Los SAD<br>no se alamacenan después de la autorización" para alinearlo con el uso de "almacenado" en<br>otra parte de la sección 3.3 de este requisito.|Aclaración u<br>Orientación|
|3.3.2|Aclarar la nota de aplicabilidad para emisores y empresas que apoyan los servicios de<br>emisión que cualquier almacenamiento de DUA se basa en "una necesidad empresarial<br>legítima y documentada". Agregar una descripción de la necesidad empresarial legítima.<br>Actualizar_Definiciones_para alinearlo con la descripción de "proceso de autorización" con la<br>definición de "autorización" del glosario.|Aclaración u<br>Orientación|
|3.3.3|Agregar una nota de aplicabilidad para describir la "necesidad comercial legítima del emisor"<br>que coincide con la descripción usada en las notas de aplicabilidad de los requisitos 3.3.1 y<br>3.3.2. Eliminar la definición que se encontraba anteriormente en la guía.<br>Eliminar el párrafo que describe las entidades a las cuales van dirigidos los requisitos PCI<br>DSS.<br>Eliminar_Información adicional_ya que hacía referencia a un estándar ISO que está obsoleta.|Aclaración u<br>Orientación|
|3.4.2|Aclarar las_Definiciones_que las tecnologías de acceso remoto a menudo incluyen<br>herramientas para desactivar la funcionalidad de la copia y/o reubicación.|Aclaración u<br>Orientación|
|3.5.1|Aplicabilidad del movimiento Tenga en cuenta que es relativamente trivial el reconstruir los<br>datos de PAN que tienen acceso a las versiones truncadas y con hash a_Buenas prácticas_.<br>Actualizar_Propósito_de "La eliminación de PAN en texto claro" a "PAN ilegible" y eliminar el<br>segundo párrafo, que fue redactado de forma confusa.<br>Añadir a las_Buenas Prácticas_que la implementación de hashes criptográficos con clave de<br>los procesos y procedimientos de gestión de las claves asociados es un control adicional<br>válido para evitar la correlación.|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 4_ 

_Página 4_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|3.5.1.1|Añadir Propósito de enfoque personalizado para ofrecer flexibilidad a la hora de cumplir con<br>este requisito.<br>Eliminar las notas de aplicabilidad duplicadas del requisito 3.5.1 y añadir que "Todas las<br>notas de aplicabilidad del requisito 3.5.1 se aplican también este requisito".<br>Añadir una nota de aplicabilidad que indique que el requisito sustituirá al punto del Requisito<br>3.5.1 para hashes unidireccionales una vez alcanzada su fecha de entrada en vigor.<br>Añadir una nota de aplicabilidad para los componentes del sistema que generan hashes<br>individuales con la clave de un PAN para compararlo con otro sistema.<br>Actualizar_Propósito_de "La eliminación de PAN en texto claro" a "PAN ilegible."<br>Eliminar_Buenas prácticas_y trasladar la información a_Finalidad_.<br>Añadir_ejemplos_relacionados con la nueva nota de aplicabilidad para los componentes del<br>sistema que generan hashes individuales con clave de un PAN para compararlo con otro<br>sistema.|Aclaración u<br>Orientación|
|3.5.1.2|Añadir Propósito de enfoque personalizado para ofrecer flexibilidad a la hora de cumplir este<br>requisito.<br>Añadir una nota de aplicabilidad acerca de los tipos de métodos de cifrado a los cuales se le<br>aplica este requisito.<br>Añadir una nota de aplicabilidad acerca de cómo se aplica este requisito a los emisores y a<br>quienes prestan servicios de emisión.|Aclaración u<br>Orientación|
|**Requisito 4**|||
|4.2.1|Trasladar la nota de aplicabilidad acerca de la recepción de datos de tarjetahabiente a través<br>de un canal no solicitado a una nueva subsección de la Sección 4,_Ámbito de aplicación de_<br>_los requisitos de PCI DSS._<br>Eliminar la frase de la nota de aplicabilidad que cubría los certificados autofirmados.|Aclaración u<br>Orientación|
|4.2.2|Añadir_Buenas Prácticas_acerca del uso de Políticas de uso aceptable para gestionar las<br>tecnologías del usuario final.|Aclaración u<br>Orientación|
|**Requisito 5**|||
|5.4.1|Eliminar la nota de aplicabilidad acerca del mecanismo automatizado para aclarar que el<br>requisito sí se aplica a los sistemas que proporcionan el mecanismo (PCI DSS en general se<br>aplica a los sistemas que proporcionan servicios de seguridad).|Aclaración u<br>Orientación|
|**Requisito 6**|||
|6.3.1|Aclarar la nota de aplicabilidad teniendo en cuenta que este requisito es adicional a la<br>realización de escaneos de vulnerabilidad de acuerdo con los requisitos 11.3.1 y 11.3.2.<br>Añadir el texto de PCI DSS v3.2.1 a_Buenas prácticas_que las clasificaciones de riesgo<br>deben identificar las vulnerabilidades consideradas de "alto riesgo" o "críticas" para el<br>entorno. Actualización de las_Buenas Prácticas_acerca de la inclusión de múltiples fuentes<br>de información acerca de las vulnerabilidades en el proceso de gestión de vulnerabilidades<br>de la entidad.|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 5_ 

_Página 5_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|6.3.3|Actualizar el requisito de volver a la versión 3.2.1 para que se aplique a los parches y<br>actualizaciones de vulnerabilidades críticas. Eliminar el texto añadido para la v4.0 de que el<br>requisito se aplica a los "parches y actualizaciones de alta seguridad".<br>Eliminar el ejemplo de "en los tres meses siguientes a la puesta en servicio" del requisito y<br>añadirlo a los_Ejemplos_.<br>Aclarar que todos los demás parches y actualizaciones de seguridad aplicables se instalan<br>según lo determinado por la "evaluación de la criticidad del riesgo para el entorno" de la<br>entidad que el parche aborda.<br>Añadir a las_Buenas Prácticas_el recomendarles a las entidades que cumplan con un análisis<br>de riesgos específico para determinar la frecuencia de instalación de todos los demás<br>parches y actualizaciones de seguridad aplicables.|Aclaración u<br>Orientación|
|6.4.3|Aclarar la viñeta del requisito de que "Se mantiene un inventario de guiones con una<br>justificación_empresarial o técnica_por escrito del por qué cada uno es necesario".<br>Añadir tres notas de aplicabilidad para aclarar cómo se aplica el requisito a las páginas web<br>de una entidad y a las páginas o formularios de pago integrados de un TPSP o procesador<br>de pagos.<br>Bajo el_Propósito,_añadir orientaciones para abordar situaciones en las cuales no es práctico<br>que los scripts se autoricen antes de que se modifique o añada un script a la página.<br>En las_Buenas prácticas,_añadir una orientación en el sentido de que la entidad debe<br>esperar que el TPSP o procesador de pagos proporcione pruebas de que cumple con este<br>requisito, cuando la entidad incluya en su página web una página o formulario de pago<br>incrustado de un TPSP o procesador de pagos.<br>Eliminar las_Definiciones_que explican qué significa "necesario" para este requisito<br>("necesario para que la funcionalidad de la página de pago acepte una operación de pago").|Aclaración u<br>Orientación|
|6.5.5|Eliminar las_Buenas Prácticas_que explican cómo las entidades pueden minimizar el<br>almacenamiento de PAN en vivo en preproducción.<br>Aclarar, en las_Definiciones_, que los PAN vivos son los emitidos por, o en nombre de, una<br>marca de pago. Eliminar el texto que indica que los PAN en vivo puedan usarse para<br>efectuar pagos.|Aclaración u<br>Orientación|
|**Requisito 8**|||
|Requisito 8<br>– General|Actualizar la siguiente declaración en la visión general y en las notas de aplicabilidad para<br>varios requisitos: "_Ciertos requisitos no están destinados a aplicarse a las cuentas de_<br>_usuario en terminales de punto de venta que tienen acceso a un solo número de tarjeta a la_<br>_vez para facilitar una sola transacción_" para agregar la redacción en cursiva y eliminar el<br>ejemplo incluido entre paréntesis.|Aclaración u<br>Orientación|
|8.2.2|Actualizar "cuenta" por "ID" en el requisito y la orientación para alinearlo con el Propósito de<br>enfoque personalizado.<br>Actualizar el Propósito del enfoque personalizado a "Identificación de grupo, compartidos o<br>genéricos" para alinearlo con el requisito.|Aclaración u<br>Orientación|
|8.3.9|Aclarar la aplicabilidad obsérvasión que el requisito no se aplica a los componentes del<br>sistema incluidos en el ámbito de aplicación en los que se usa la AMF.|Aclaración u<br>Orientación|
|8.4.1|Pasar de nota de aplicabilidad a la_Buena Práctica ya_que la AMF es una buena práctica<br>para el acceso administrativo no consular a los componentes del sistema incluidos en el<br>ámbito de aplicación que no forman parte del CDE.|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 6_ 

_Página 6_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|8.4.2|Aclarar que el requisito es para todos los accesos "sin consola" al CDE.<br>Añadir la aplicabilidad que tenga en cuenta que este requisito no se aplica a las cuentas de<br>usuario que sólo se autentican con factores de autenticación resistentes al phishing.|Aclaración u<br>Orientación|
|8.4.3|Aclarar que este requisito se aplica al "acceso remoto" en lugar del término confuso "acceso<br>remoto a la red" y traslade las viñetas sobre qué tipos de acceso remoto se incluyen a una<br>nota de aplicabilidad.<br>Añadir "terceros" al procedimiento de prueba.|Aclaración u<br>Orientación|
|8.5.1|Añadir una definición de ataque repetido en las_Definiciones_.<br>Añadir ejemplos de los métodos para ayudar a proteger contra los ataques repetidos en los<br>_Ejemplos_.|Aclaración u<br>Orientación|
|**Requisito 9**|||
|Requisito 9<br>– General|Añadir una declaración a la descripción general que indique que cada entidad debe<br>identificar las zonas sensibles de su entorno para garantizar que se aplican los controles de<br>seguridad física adecuados.|Aclaración u<br>Orientación|
|9.2.1|Añadir aplicabilidad y tenga en cuenta que este requisito no se aplica a los lugares a los<br>cuales los consumidores (titulares de tarjetas) pueden acceder públicamente.|Aclaración u<br>Orientación|
|9.3.4|Aclarar que el requisito es para los "registros de visitantes" en lugar de "un registro de<br>visitantes" y a "la actividad de los visitantes_tanto_con la instalación como dentro de las<br>zonas sensibles."|Aclaración u<br>Orientación|
|9.5.1|Consolidar las notas de aplicabilidad en dos viñetas para aclarar los tipos de dispositivos a<br>los cuales no se aplican los requisitos del punto 9.5.<br>Trasladar la recomendación de la nota de aplicabilidad a_Buenas prácticas_.|Aclaración u<br>Orientación|
|**Requisito 10**|||
|10.4.1.1|Añadir información acerca del establecimiento de una base de referencia de la actividad<br>normal de auditoría a las_Buenas prácticas_.<br>Añadir una referencia al_Suplemento de Información: Monitoreo Diario Efectivo_en<br>_Información Adicional_.|Aclaración u<br>Orientación|
|10.5.1|Actualizar el epígrafe_Buenas prácticas_por el epígrafe_Propósito_para reflejar exactamente el<br>contenido de esa sección.|Estructura o<br>formato|
|**Requisito 11**|||
|11.2.1|Eliminar la nota de aplicabilidad y moverla bajo el_Propósito_que el uso no autorizado de<br>tecnologías inalámbricas sigue siendo posible incluso si la empresa tiene una política que lo<br>prohiba.|Aclaración u<br>Orientación|
|11.3.1|Aclarar que el requisito se aplica a las vulnerabilidades que son "críticas o de alto riesgo".<br>Añadir a las_Buenas Prácticas_que las vulnerabilidades identificadas durante los escaneos<br>internos de vulnerabilidades deben formar parte del proceso de gestión de vulnerabilidades<br>de la entidad e incluir múltiples fuentes de vulnerabilidades.|Aclaración u<br>Orientación|
|11.3.1.1|Aclarar que el requisito se aplica a todas las demás vulnerabilidades no clasificadas como<br>"vulnerabilidades de alto riesgo o vulnerabilidades críticas".|Aclaración u<br>Orientación|
|11.3.1.3|Aclarar que el requisito se aplica a las vulnerabilidades que son "críticas o de alto riesgo".|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 7_ 

_Página 7_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|11.3.2|Añadir a las_Buenas prácticas_que las vulnerabilidades identificadas durante los escaneos<br>externos de vulnerabilidades deben formar parte del proceso de gestión de vulnerabilidades<br>de la entidad e incluir múltiples fuentes de vulnerabilidades.<br>Añadir una referencia a la_Guía del programa PCI SSC (ASV)_en la_Información adicional_.|Aclaración u<br>Orientación|
|11.6.1|Aclarar que el requisito se aplica a los "_encabezados HTTP que afectan la seguridad y en el_<br>_contenido de script de las páginas_ _de pago_...".<br>Actualizar el requisito de "una vez cada siete días" a "semanalmente" para alinearlo con la<br>Tabla 4.<br>Añadir tres notas de aplicabilidad para aclarar cómo se aplica el requisito a las páginas web<br>de una entidad y a las páginas o formularios de pago integrados de un TPSP o procesador<br>de pagos.<br>Ampliar el_Propósito_para incluir más detalles sobre lo que se puede detectar al comparar los<br>encabezamientos HTTP y el contenido de las páginas de pago recibidas por el navegador<br>del consumidor.<br>En las_Buenas prácticas,_añadir una orientación en el sentido de que la entidad debe<br>esperar que el TPSP o procesador de pagos proporcione pruebas de que cumple con este<br>requisito, cuando la entidad incluya en su página web una página o formulario de pago<br>incrustado de un TPSP o procesador de pagos.<br>Aclararen los_Ejemplos_que los mecanismos que detectan e informan sobre cambios en los<br>encabezamientos y el contenido de las páginas de pago "_podrían_incluir, pero no se limitan<br>a,_una combinación de las siguientes técnicas"._Añadir que la lista de mecanismos que se<br>encuentra en los_Ejemplos_no es exhaustiva.|Aclaración u<br>Orientación|
|**Requisito 12**|||
|12.1.4|Eliminar ejemplos de títulos de dirección ejecutiva comunes para esta función del_Propósito_.<br>Cambiar la descripción de que estos puestos suelen estar en el nivel más alto de gestión a<br>_Buenas prácticas._<br>Añadir orientación acerca de cómo se pueden indicar los conocimientos de seguridad de la<br>información para esta función de la dirección ejecutiva en las_Buenas prácticas_.|Aclaración u<br>Orientación|
|12.3.1|Aclarar que el requisito sólo se aplica a los requisitos de PCI DSS que especifican la<br>realización de un análisis de riesgos específico.<br>Aclarar que el análisis resultante determina y justifica cómo la frecuencia o los procesos<br>definidos por la entidad minimizan la probabilidad y/o el impacto de la amenaza.<br>Añadir una sección de_Información adicional_para hacer referencia al documento de<br>orientación sobre el análisis de riesgos específicos del PCI SSC y a las plantillas de<br>muestra.|Aclaración u<br>Orientación|
|12.3.3|Actualizar el tercer punto del requisito a "Documentación de un plan" (en lugar de "Una<br>estrategia documentada") para alinearlo con la redacción del requisito 12.3.4.<br>Añadir a la nota de aplicabilidad para proporcionar ejemplos de los requisitos de PCI DSS<br>que requieren el uso de criptografía.|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 8_ 

_Página 8_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
|12.8.2|Aclarar el segundo punto del requisito de que los acuses de recibo de los TPSP aborden la<br>responsabilidad de los TPSP cambiando "esos" por "los TPSP".<br>Actualizar las notas de aplicabilidad como se determina a continuación:<br>•<br>Aclarar la diferencia entre "acuerdo" y "reconocimiento".<br>•<br>Añadir que el reconocimiento por escrito del TPSP es la confirmación de que el TPSP<br>es responsable.<br>•<br>Cambiar los ejemplos de pruebas que demuestren que un TPSP cumple los requisitos<br>de PCI DSS a una frase aparte y agregue más ejemplos.|Aclaración u<br>Orientación|
|12.9.1|Actualizar el segundo punto del requisito para reflejar el mismo lenguaje incluido en el<br>requisito 12.8.2 sobre lo que los clientes obtienen de parte de sus proveedores de servicios<br>de pago por parte de terceros, para aclarar lo que los proveedores de servicios de pago por<br>terceros deben proporcionarles a los clientes en relación con los acuerdos y reconocimientos<br>por escrito.<br>Aclarar que los acuses de recibo de los TPSP abordan la responsabilidad de los TPSP<br>cambiando "esos" por "los TPSP".<br>Actualizar las notas de aplicabilidad como se determina a continuación:<br>•<br>Aclarar la diferencia entre "acuerdo" y "reconocimiento".<br>•<br>Añadir que el reconocimiento por escrito del TPSP es la confirmación de que el TPSP<br>es responsable.<br>•<br>Añadir la misma nota de aplicabilidad incluida en el requisito 12.8.2 en el sentido de<br>que la prueba de que un TPSP cumple un requisito del PCI DSS no es igaula a un<br>acuerdo por escrito.<br>Actualizar_Propósito_para que incluya la redacción de PCI DSS v3.2.1 sobre las plantillas de<br>los TPSP incluyendo la provisión de acuses de recibo apropiados.|Aclaración u<br>Orientación|
|12.9.2|Aclarar que el primer punto del requisito se aplica a todos los TPSP eliminando "para<br>cualquier servicio que el TPSP realice en nombre de los clientes".<br>Aclarar que el segundo punto del requisito se aplica a los TPSP que prestan servicios que<br>cumplen con los requisitos PCI DSS del cliente o que pueden afectar la seguridad de los<br>datos del titular de la tarjeta de los clientes.|Aclaración u<br>Orientación|
|**Anexo**|||
|Anexo A1:|Actualizar la cláusula en la Visión general de las "conexiones a pasarelas y procesadores de<br>pago" a "servicios de pasarela y procesador de pagos ofrecidos en un entorno compartido."|Aclaración u<br>Orientación|
|Anexo A3|Actualizar la sección de la descripción general que cubre los plazos definidos para reflejar la<br>redacción de la Sección 7 y remitirlos a la Sección 7 para obtener orientación acerca de las<br>evaluaciones iniciales.|Aclaración u<br>Orientación|
|Anexo D|Actualizar para hacer referencia a PCI DSS v4.x: Plantillas de muestra para apoyar el<br>enfoque personalizado en el sitio web del PCI SSC en lugar del Anexo E.<br>Actualizar de "El uso del enfoque personalizado debe ser completado por un QSA o ISA y<br>debe ser documentado de acuerdo..." a "El uso del enfoque personalizado debe ser<br>documentado por un QSA o ISA de acuerdo...".|Aclaración u<br>Orientación|
|Anexo D|Eliminar las plantillas de muestra del Enfoque personalizado y use el Anexo E para indicar<br>que las plantillas están disponibles en el sitio web del PCI SSC.|Estructura o<br>formato|
|Anexo G|Añadir las definiciones de "Excepción Legal", "Autenticación Resistente al Phishing" y<br>"Visitante".|Aclaración u<br>Orientación|



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 9_ 

_Página 9_ 

|**Requisito**<br>**PCI DSS**|**Descripción del Cambio**|**Tipos de**<br>**Cambio**|
|---|---|---|
||Aclarar las definiciones de "Entidad", "Inicio de sesión interactivo" y "Página de pago" y<br>"QSA".||



_PCI DSS v4.0 a la v.4.0.1 Resumen de Cambios r1                                                                                Agosto de 2024 © 2024 PCI Security Standards Council, LLC. Todos los derechos reservados. Página 10_ 

_Página 10_ 

