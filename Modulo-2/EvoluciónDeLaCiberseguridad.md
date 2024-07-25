# La Hisoria de la Ciberseguridad 
---

## Definiciones

### Computer Virus (Virus informático)
Es un código malicioso escrito para interferir con operaciones informáticas y **causar daños a los datos y el software.** El virus se adhiere a programas o documentos en una computadora. Luego **se propaga e infecta uno o más computadoras en una red.**

### Worm (Gusano)
Es un tipo de *Computer virus* que puede duplicarse y propagarse por su cuenta. 

### Malware (software malicioso)
Es software diseñado para dañar dispositvios o redes.

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


## Ataques comunes y su eficacia
Anteriormete, aprendiste acerca de los ataques pasados y actuales que ayudaron a moldear el campo de la ciberseguridad. Uno de sus resultados fue el desarrollo de los **equipos de respuesta ante inicidentes de seguridad informática (CSIRT, por sus siglas en inglés)**. En esta lectura conocerás más detalles sobre los métodos de ataque mas comunes.

### Phishing
Es el uso de comunicaciones digitales en las que se **suplanta la identidad de una persona o empresa** con el objetivo de engañar a otras personas para que **revelen datos confidenciales o implementen un software malicioso**.

Algunos de los tipos más comunes de ataques de *phishing* actuales son:

