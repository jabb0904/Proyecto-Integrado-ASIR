# Infraestructura Informática Global
## Creación de toda la infraestructura informática para una autoescuela.

### INTRODUCCIÓN.

Se trata de una empresa (Autoescuela Lechuga) que pretende “modernizarse” dejando a un lado la formación tradicional en papel, pasando a desarrollarla de forma totalmente digital y online. 

### FINALIDAD
El proyecto va a consistir con diseñar, desarrollar e implementar toda la Red Informática (clientes, servidores, routers, webs, etc.) para el correcto funcionamiento de la empresa.

### OBJETIVOS
Se pretende montar la estructura informática para la siguiente organización:
La empresa cuenta con 2 sedes, una en Jerez (principal) y otra en Dos Hermanas.
Ambas sedes tienen la misma estructura de formación:
•	Aula para alumnos que acceden a los diferentes tipos de carnet por primera vez, equipada con 10 ordenadores
•	Aula para alumnos de reciclaje, bien por falta de uso, bien por obligaciones con la DGT por pérdida de puntos, etc., equipada con 5 ordenadores
La sede principal cuenta, además, con un departamento de administración que se encarga de la gestión y control de ambas sedes. En este departamento trabajan, alternando trabajo presencial y teletrabajo, un total de 4 personas: una gerente, que es, además, jefa de administración, un instructor jefe y 1 administrativa y 1 recepcionista/administrativo.

### MEDIOS HARDWARE Y SOFTWARE A UTILIZAR
Como describo más adelante, en el apartado Planificación, usaré las siguientes herramientas:
•	Packet Tracer
•	VMware WorkStation Pro
•	WordPress instalado en un hosting
•	Moodle instalado en un hosting
•	Máquina virtual con Windows Server
•	Máquina virtual con Synology para emular un NAS.
•	OpenVPN para la creación de la VPN.

### PLANIFICACIÓN
Se propone:
•	Diseño e implantación de toda la red informática necesaria (equipos, routers, switches, cableado, redes, subredes, Vlans, ruteo, etc.) para la empresa (se realizará en la aplicación de simulación Packet Tracer). Para el proyecto, se simularán varias máquinas virtuales que harán las veces de host en cada una de las aulas y sedes, así como algún host del departamento de administración. (PAR / FH)
•	Instalación de un servidor Windows (simulado en una máquina virtual) en el departamento de administración, con las funciones de:
o	Active Directory (ISO / ASO)
o	Servidor de correos electrónicos (ISO / ASO)
o	Servidor de impresión (ISO / ASO)
•	Alojamiento en un hosting gratuito de las web de la empresa (autoescuelalechu.ga). (ISO / ASO /SIR).
•	Diseño e implantación de una página web corporativa, mediante el uso de WordPress. (IAW / SRI)
•	Diseño e implantación de una web para el funcionamiento de autoescuela, usando el CMS Moodle, que usarán profesores y alumnos en la que se podrán realizar test de cada tipo de carnet, descarga de documentos de ayuda, etc. (IAW / SRI)
•	Creación de una estructura de red multisede (Routing). (PAR)
•	Creación de VNP para que profesores y administración tengan acceso seguro desde cualquier lugar (Se simulará en un servidor Linux y una máquina virtual cliente, que hará las veces de un portátil particular de uno de los profesores). (SAD)
•	Creación de copias de seguridad en NAS privado. (Se simulará con una máquina virtual usando Synology). (SAD / ASO)
•	SI NO SE ME HACE DEMASIADO GRANDE EL PROYECTO: Creación, dentro de la web corporativa, de un área privada (para profesores y administración), donde administración controlará las altas y bajas de alumnos, así como los recibos y los pagos que los mismos realicen y los profesores podrán crear, modificar y consultar los horarios de prácticas que tienen con sus alumnos. (GBD / ASGBD / LM / IAW)
