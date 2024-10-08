# La Hisoria de la Ciberseguridad 
---



## Dos Ataques tempranos de *Malware* : Virus Brain y Gusano Morris

Fueron creados por desarrolladores de **malware** para tareas específicas. Sin embargo, ellos subestimaron el impacto que su malware tendría y la cantidad de computadoras que este iba a infectar.

### Virus Brain 

En **1986**, los hermanos Alvi crearon el **Virus Brain**. La función principal era rastrear copias ilegales de software médico y evitar las licencias piratas, pero los resultados no fueron los esperados.  
Una vez que una persona usaba una copia barata del software, **el virus infectaba esa computadora**. Luego cualquier disco que se insertaba en la computadora tambien se infectaba. **El virus se propagaba a una computadora nueva cada vez que alguien usaba uno de los discos infectados**. EL virus se propagó por todo el mundo en un par de meses.  
El virus Brain alteró radicalmente la industria informática y **destacó la necesidad de un plan para mantener la seguridad y productividad.**

### Gusanos Morris

En **1988**, Robert Morris desarrollo un programa para **calcular el tamaño de internet**. El programa rastreó la web y se instaló en otras computadoras para calcular el número de equipos conectados a internet.  
El programa no logró hacer un seguimiento de las computadoras que ya habia puesto en riesgo, y seguia reinstalándose hasa que las computadoras se quedaron sin memoria y colapsaron. Cerca de 6000 computadoras se vieron afectadas **(10% de internet en ese momento)**  
**Despues del Gusano Morris** se establecieron equipos de respuesta ante emergencias informáticas conocidos como **CERT®**, para responder a incidentes de seguridad informática.


## Dos Ataques notables que *dependieron de internet* : Ataque LoveLetter y Fuga de información de Equifax

### Ataque LoveLetter
En el año **2000**, Onel De Guzmán creó el malware **LoveLetter** para robar credenciales de inicio de sesión de internet. El ataque se extendió rapidamente y se aprovechó de personas que no habian aprendido a sospechar de los emails no deseados.  
Los usuarios recibieron un email con un "Te amo" en el asunto. Cada email contenía un archivo adjunto titulado "Carta de amor para ti". Al abrir el archivo, el malware escaneaba la libreta de direcciones de un usuario. Luego se **enviaba** automáticamente a cada persona de la lista e **instalaba un programa** para recopilar **información de usuario** y **contraseñas**.  
LoveLetter afectó 45 millones de computadoras y fue el primer ejemplo de **Ingeniería Social.**

### Fuga de información de Equifax
En **2017**, atacantes se infiltraron con éxito en la **agencia de informes de crédito de Equifax**. Esto dio lugar a una de las fugas de información más grandes de las que se tenga registro.  
Se robaron más de **143 millones de registros de clientes** y la fuga afectó a casi el **40%** de los estadounidenses. Los registros contenían **información personal identificable** como números de seguridad social, fechas de nacimiento, licencias de conducir, domicilios y números de tarjetas de crédito.  
Desde el punto de vista de la seguridad, la fuga se produjo debido a múltiples fallas por parte de Equifax. **La empresa no tomó las medidas necesarias** para reparar múltiples vulnerabilidades conocidas en los meses previos a la fuga.
Al final, **Equifax llegó a un acuerdo con el gobierno de los EE.UU. y pagó mas de 575 millones de dólares** para resolver reclamos de los clientes y cubrir las multas requeridas.

___

## Ataques comunes y su eficacia
Anteriormete, aprendiste acerca de los ataques pasados y actuales que ayudaron a moldear el campo de la ciberseguridad. Uno de sus resultados fue el desarrollo de los **equipos de respuesta ante inicidentes de seguridad informática (CSIRT, por sus siglas en inglés)**. En esta lectura conocerás más detalles sobre los métodos de ataque mas comunes.

### Phishing
Es el uso de comunicaciones digitales en las que se **suplanta la identidad de una persona o empresa** con el objetivo de engañar a otras personas para que **revelen datos confidenciales o implementen un software malicioso**.

Algunos de los tipos más comunes de ataques de *phishing* actuales son:

- #### Compromiso del email empresarial (BEC) : 
Tipo de ataque de suplantación de identidad,en el que un agente de amenaza **envia un email y se hace pasar por una persona conocida** por la víctima e **intenta que realice una acción**, como enviar dinero u otorgar datos confidenciales de la compañía.  

- #### Phishing localizado (spear phishing) : 
Ataque por **email malicioso** dirigido a una persona o grupo de personas específico que **parece** provenir de una **fuente confiable**.

- #### Ataque "Caza de ballenas" (Whaling) :
Es un tipo de **phishing localizado** en el que el agente de amenaza busca acceder a los datos confidenciales de **ejecutivos de una empresa**. 

- #### Vishing : 
Un tipo de estafa por suplantación de identidad en la que se busca obtener información sensible a través de una **llamada telefónica**.

- #### Smishing :
Ataque de **phishing por SMS** para engañar a los usuarios, con el fin de obtener información confidencial o hacerse pasar por una fuente conocida. 

### Software Malicioso (Malware)
Software diseñado para **dañar dispositivos o redes**. EL propósito principal del ataque es obtener **dinero** o en algunos casos, **información** para usar en contra de una persona organización o territorio.

Algunos de los tipos más comunes de ataques de *software malicioso* actuales son:

- #### Virus informático (computer virus) :
Es un código malicioso creado para **interferir con las operaciones de la computadora y dañar datos, software y hardware**. El virus se instala en programas o documentos de una computadora y luego, **se propaga e infecta una o más computadoras en una red**.

- #### Gusano (worm) :
Es un *software malicioso* que puede duplicarse y propagarse **por si mismo**.

- #### Rasomware (secuestro de datos) :
Es un ataque malicioso en el que los agentes de amenaza **cifran los datos** de una organización y **exigen un pago** para **restablecer el acceso** a ellos. 

- #### spyware : 
Es un tipo de *software malicioso* que se usa para **obtener y vender información sin consentimiento**. Se puede usar para acceder a dispositivos, lo cual permite a los agentes de amenaza recopilar datos personales.

 ### Ingeniería social
Es una **técnica de manipulación** que aprovecha errores humanos para **obtener** información privada, acceso a sistemas o bienes de valor. La misión de un agente de amenaza que actúa como ingeniero social es **crear un entorno de confianza falso y mentir para aprovecharse**.

Algunos de los tipos más comunes de *ingeniería social* actuales son:

- #### Ataque de suplantación de identidad en redes sociales (phishing en redes sociales) :
Es un tipo de ataque en el que el agente de amenaza contacta a la víctima en alguna red social para **robar información** o **quedarse con la cuenta**.

- #### Ataque de "agujero de agua" (Watering hole) : 
Un agente de amenaza ataca un **sitio web** visitado con frecuencia por un **grupo específico de usuarios**.

- #### Cebo USB :
Un agente de amenaza deja estratégicamente una **unidad de USB que contiene software malicioso** para que un empleado lo encuentre y lo instale, con el fin de causar la **infección involuntaria de una red**.

- #### Ingeniería social física :
Un agente de amenaza **se hace pasar** por una persona ligada a la empresa para obtener **acceso no autorizado a una ubicación física**.

### Principios de la ingeniería social 
La **ingeniería social** es eficaz porque las personas suelen ser confiadas y tienen firmemente establecido el respeto a la autoridad. La cantidad de ataques de ineniería social **aumenta** a medida que crece la cantidad de aplicaciones de redes sociales que **permiten el acceso público a los datos de las personas**.

Los motivos por los cuales los ataques de *ingeniería social* son eficaces son:

- #### Autoridad :
Los agentes de amenaza se hacen pasar por **personas con autoridad** porque los individuos suelen respetarlas.

- #### Intimidación :
Los agentes de amenaza utilizan **tácticas de hostigamiento**, como asustar las víctimas para que sigan sus órdenes.

- #### Consenso / Prueba social :
Como las personas a veces hacen cosas convencidas de que otras tambien las hacen, los agentes de amenaza **utilizan esta confianza** en los demas para dar una **impresión de legitimidad**.

##### Ejemplo: 
Para obtener acceso a datos privados, un agente de amenaza puede decir a un empleado que **otros miembros de la empresa ya le han otorgado el acceso** en otras ocaciones.

- #### Escasez : 
El agente de amenaza le da a entender a la persona que existe **disponibilidad limitada** a ciertos bienes o servicios, para **convencerla de hacer algo**.

- #### Familiaridad : 
Los agentes de amenaza establecen **falsos lazos emocionales** con los usuarios de quienes desean aprovecharse, para lograr su objetivo.

- #### Confianza : 
Los agentes de amenaza establecen una relación afectiva con los usuarios, que les permite aprovecharse de ellos con el *paso del tiempo* y acceder a su información personal.

- #### Urgencia :
Un agente de amenaza **persuade** a las personas para que **respondan con rapidez** sin hacer preguntas.


