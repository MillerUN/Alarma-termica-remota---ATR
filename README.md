# Alarma térmica remota (ATR)
## Equipo de trabajo
G.A. Angulo S, M.A. Cubillos H, J.M. Marín M, J.S. Monje M, J.S. Quecan H, W.A. Quiroga H, M.F. Triviño C.

## Identificación de problemas

| | **Es**	| **Hizo** |	**Puede** |	**Hará** |	**Haría** |	**Podría** |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| Quién | Empresas, familias y agricultores. | Enrique Hernández. | Propietario de unidad de refrigeración con conocimiento acerca del proceso a monitorear. | Estudiantes de sistemas embebidos. | Interesados en monitoreo de temperatura y humedad en espacio con alto valor económico o investigativo desde cualquier lugar. | Personas  con  capacidad de programar, entender el  hardware   y el software del  sistema. |
| Qué | Cambios de temperatura y humedad. | Sistema de monitoreo y control vía inalámbrica de humedad y temperatura para invernaderos. | Ocasiona pérdidas de materiales y alimentos sensibles a cambios de temperatura. | Detectar cambios de temperatura o humedad relativa. | Revisar alarma, verificar y corregir fallos. | Notificar a usuarios sobre cambios de temperatura y/o humedad relativa. |
| Dónde | Lugares que cuentan con unidades de refrigeración. | UPTC | Refrigeradores o invernaderos. | El laboratorio de electrónica digital y microprocesadores. | En lugares que requieran  de un monitoreo  de temperatura y humedad. | Recintos que requieran de un monitoreo  de temperatura  y humedad. |
| Cuándo | En cualquier momento. | 2018 | Al presentarse fallos en el sistema de refrigeración, fallas eléctricas o fugas térmicas. | En el transcurso del semestre 2019-3. | Una de ventajas del sistema es que el censado es contante es decir el sistema estará midiendo variables los horarios de operación, por ende es un sistema en tiempo real, desde luego habrá momentos de alarma definidos por los limites operativos de la aplicación. | Cuando existen  cambios de temperatura abruptos. Teniendo en  cuenta conocimientos de diseño. |
| Por qué | Fallos en sistema de refrigeración o posibles fugas térmicas. | Mejorar eficiencia en cultivos de flores para mejorar exportaciones del país. | La temperatura puede variar conforme a diferentes factores al interior de la unidad, fugas u obstrucciones. | En vista de una problemática existente en la cual puede existir pérdidas economicas a causa de variaciones abruptas en la temperatura y humedad en almientos u otro tipo de elementos. | El control eficiente de temperatura y humedad es un imperativo, escalable desde necesidades de confort hasta procesos industriales y el estar en retroalimentación con el usuario, genera una sensación de confiablidad y eficacia en el hogar o empresa. | Por fallas relacionadas por el sistema de control o  los dispositivos de refrigeración. |
| Cómo | Ante cualquier falencia evitar abrir las puertas de la unidad de refrigeración. | Desarrollo de tesis. | Dejando las puertas abiertas, falta de mantenimiento, exceso de almacenamiento. | Empleando conocimientos en herramientas informáticas y trabajando en equipo. | Por medio de sensores, microcontroladores, microprocesadores, Fpga, aplicativos y bases de datos. | Beneficiar a empresas del sector agroindustrial, por medio de determinar de cómo influye la temperatura, en el correcto crecimiento de los cultivos. |

## Diagrama de causa y efecto
### Diagrama general
 ![alt text](https://github.com/Fernanda-Trivino/Alarma-termica-remota---ATR/blob/master/Diagrama0.PNG)
### Diagramas específicos
 ![alt text](https://github.com/Fernanda-Trivino/Alarma-termica-remota---ATR/blob/master/Diagrama1.PNG)
 ![alt text](https://github.com/Fernanda-Trivino/Alarma-termica-remota---ATR/blob/master/Diagrama2.PNG)
 ![alt text](https://github.com/Fernanda-Trivino/Alarma-termica-remota---ATR/blob/master/Diagrama3.PNG)

## Descripción del problema

|**¿Cuál es el problema clave?¿por qué?**|**¿Para quién es un problema?**|**Factores técnicos**|**Evidencias de que vale la pena realizarlo**|**¿Existen enfoques diferentes?**|
| ---- | ---- | ---- | ---- | ---- |
|Ausencia de plantas en los hogares. Es importante tener plantas cerca para mejorar la calidad del aire que se respira y con esto el bienestar de las personas.|Personas amantes de las plantas que no tengan una completa diponibilidad de tiempo.|Temperatura, humedad, CO2.|La mala calidad del aire en las ciudades, la calidad de vida de los usuarios y la necesidad de actividades de ocio.|Sí, control industrial.| 

### Roles

![alt text](https://github.com/Fernanda-Trivino/Alarma-termica-remota---ATR/blob/master/Embebidos.png)

|**Montar red de sensores con FreeRTOS**|**Enviar datos WI-Fi**|**Enviar datos UART**|**Gestionar base de datos**|**Display FPGA**|**Desarrollo aplicación**|**GUI (HTML)**|**Prototipado 3D**|
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
|J.M. Marín M., M.A. Cubillos H.|J.M. Marín M., M.A. Cubillos H.|J.M. Marín M., M.A. Cubillos H.|J.S. Monje M., W.A. Quiroga H.|G.A. Angulo S., M.F. Triviño C.|J.S. Quecán H.|J.S. Monje M., W.A. Quiroga H.|M.A. Cubillos H.|

|**Fortalezas**|**Debilidades**|
| ---- | ---- |
| iPlantTwo es una iniciativa que vincula lo mejor de tres tecnologías (microcontrolador, microprocesador y FPGA), para brindar a sus usuarios un sistea de alerta en tiempo real.|No se tiene el suficiente conocimiento de plantas y sus necesidades.|
|Se cuenta con una aplicación móvil, la cual informa al usuario el estado de su planta y recomienda  |Se debe aumentar el conocimiento en la programación de hardware.|
|**Oportunidades**|**Amenazas**|
|Los usuarios necesitan respirar un aire de mejor calidad, dadas las múltiples alertas por contaminación. iPlantTwo ofrece la oportunidad al incentivar la tenencia de plantas en el hogar.|Las empresas que trabajan este tema tienen ms años de experiencia.|
|El aprovechamiento de las tecnologías y aplicaciones digitales, implementado al monitoreo de plantas, dándole al usuario facilidad y comodidad a larga distancia para cuidar de sus plantas.|El mercado ya está establecido con ciertas compañías.|
|La población no cuenta con el tiempo y/o conocimiento necesarios para el cuidado de sus plantas. Con este sistema, se les proporcionará un apoyo en estos dos aspectos.|En el tiempo previsto, integrar todas las partes del proyecto plantea un reto al grupo.|
||Limitación económica en el desarrollo del prototipo.|

### Diseños
## Diseño Hardware 
## Diseño prototipo 1.0 

###  Codigos fuente
