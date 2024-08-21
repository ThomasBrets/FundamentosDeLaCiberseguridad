# Herramientas importantes de ciberseguridad
---

## La caja de herramientas de un analista de nivel inicial
Cada organización puede proporcionar una **caja de herramientas** diferente, dependiendo de sus necesidades de seguridad. Como futuro analista, es importante que te familiarices con las herramientas estándar de la industria y que puedas demostrar tu capacidad para aprender a usar otras similares, en un lugar de trabajo diferente

### Log (registro)
És un historial de eventos que ocurren dentro de los sistemas de una organización.

#### Ejemplo
Registros de inicio de sesión de empleados en sus computadoras o accesos a servicios en la red.

### Herramientas de información de seguridad y gestión de eventos (Herramientas SIEM)
Una herramienta **SIEM** una aplicación que **recopila y analiza datos de registro** para monitorear actividades críticas en una organización.  
Dependiendo de la cantidad de datos con los que estés trabajando, podría tomarte horas o días filtrar los datos del registro. Las herramientas SIEM **proporcionan alertas para tipos específicos de amenazas, riesgos y vulnerabilidades**, lo que reduce la cantidad de datos que un/a analista debe revisar.  

Las herramientas SIEM ofrecen **paneles (dashboards) que organizan visualmente los datos en categorías** para facilitar su análisis. Además, pueden ser alojadas **localmente (on-premise)** o en **la nube**, permitiendo a las organizaciones elegir según la experiencia de su equipo de seguridad. Las versiones en la nube suelen ser más fáciles de configurar, usar y mantener, lo que puede ser preferido por equipos con menos experiencia.

#### Ejemplos

#### Splunk
Es una plataforma de analisis de datos, y **Splunk Enterprise** proporciona soluciones **SIEM**. Splunk Enterprise es una herramienta autoalojada que se utiliza para retener, analizar y buscar datos de registri de una organización.

#### Chronicle, de Google
Es una **SIEM nativa de la nube**, que **analiza datos de seguridad para búsqueda y análisis**. Al ser nativa de la nube significa que Chronicle permite una entrega rápida de nuevas características. 


### Analizadores de protocolo de red (sniffer de paquetes)
Es una herramienta diseñada para **capturar y analizar el tráfico de datos de una red**. Esto significa que la herramienta **mantiene un registro de todos los datos** que encuentra una computadora dentro de la red de una organización.   

### Manual de estrategias (Playbook)
**Brinda detalles acerca de cualquier acción operativa**, como la forma de responder a un incidente. Estos manuales, que varían de acuerdo a la organización, **orientan a los analistas sobre como manejar un incidente de seguridad antes, durante y después de que ocurrió**.  
Pueden corresponder a revisiones de conformidad o seguridad, gestión del acceso y muchas otras tareas organizacionales que requieren un proceso documentado de inicio a fin.

#### Ejemplo
Como analista de seguridad, tu tarea es investigar una fuga de información en una clínica médica y proporcionar evidencia a una compañía de seguros de ciberseguridad. Según los hallazgos de tu investigación, se decidirá si la clínica recibirá el pago del seguro.  
En este ejemplo, los manuales  describirán las acciones específicas que debes tomar para llevar a cabo la investigación. También ayudan a que te asegures de que estás siguiendo los protocolos y procedimientos adecuados.  

Cuando trabajas en un caso forense, hay dos manuales que puedes seguir:

- **La cadena de custodia:** La cadena de custodia es el proceso de documentar la posesión y el control de la evidencia durante el ciclo de vida del incidente.  
Como analista de seguridad en un análisis forense, debes trabajar con los **datos vulnerados y documentar todos los detalles de la evidencia** recopilada. Es tu responsabilidad **mantener las pruebas seguras y reportar cada vez que se muevan**, asegurando que todas las partes sepan su ubicación en todo momento.

- **Protección y preservación de la evidencia:** La protección y preservación de la evidencia es el proceso de trabajar adecuadamente con **evidencia digital frágil y volátil**. Como analista de seguridad, es fundamental comprender qué es la evidencia digital frágil y volátil, y por qué existe un procedimiento.  
Al seguir el manual, debes consultar el **"orden de volatilidad"**, que prioriza la conservación de los datos más volátiles, aquellos que se pierden si el dispositivo se apaga. Una **gestión inadecuada** de la evidencia digital puede **comprometerla**, haciéndola inutilizable en la investigación. Por eso, la prioridad es preservar correctamente los datos, lo que incluye hacer copias para su análisis.

## Conclusión
En esta lectura, aprendiste sobre algunas herramientas que un analista de seguridad puede tener en su **caja de herramientas**, dependiendo de dónde trabajen. También exploraste **dos tipos importantes de manuales de estrategias: la cadena de custodia y la protección y preservación de la evidencia.** Estos son solo dos procedimientos que ocurren al comienzo de una investigación forense.
