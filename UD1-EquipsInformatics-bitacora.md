### Sesión 7J

Perfiles de usuario:
- Administrativo
- La gestora de RRHH

Opciones:

1- Que cada usuario tenga la documentación en su propio ordenador.
Ventajas: que se garantiza el acceso correcto.
Desventaja: no estan conectados y no pueden compartir información que pueden necesitar AMBOS perfiles. Solución sería tener información DUPLICADA.

2- Que la información este en un ordenador y se comparta a través de la RED LOCAL (LAN = Local Area Network).

3- Disponer (en la propia RED LOCAL de la empresa) de un SERVIDOR --> ES UN ORDENADOR "especial" QUE:

- Está encendido de forma contínua (24h / 7 d / 365 d).
- "Sirve" las peticiones que le mandan el resto de ordenadores conectados en la misma RED (LOCAL).

4- Hacer una "ABSTRACCIÓN" del concepto de SERVIDOR y poner los servicios (servidor de ficheros, etc.) en LA NUBE (en INTERNET) 

¿Qué es la NUBE?  LA NUBE no es nada más que un CONJUNTO DE SERVIDORES en Internet.

Los servidor de la NUBE pueden darte servicios como:

- Servidor de ficheros
- Servidor de aplicaciones WEB
- Servidor de Bases de Datos
- Servidor de CORREO ELECTRÓnico
- etc.......


MEDIDAS DE SEGURIDAD: (preventivas, mitigadoras)
---------------------

- FÍSICAS --> preventivo:  
	* Sala del servidor tiene que cumplir:
		Bien ventilada -> temperatura -> Refrigeradas
		No haya humedades 
		Protección contra incendios
- SAI (UPS): Sistema de Alimentación Ininterrumpida.

- Medidas de protección de la INFORMACIÓN --> Documentos, archivos, ficheros ...
	Medidas de seguridad específica para discos duros:
		RAID 1 (espejo)
		RAID 5 (combinación 0 + 1)
- BACKUPS -> COPIAS DE SEGURIDAD --> DISCOS EXTERNOS:
	* Conectado el mínimo tiempo imprescindible para hacer
	el backup
	* El disco externo con el backup SIEMPRE se va a guardar
	en una SALA (EDIFICIO) DISTINTA de donde esta el Servidor

Copias automatizadas de todos los ficheros.
1. Hacer la copia de Seguridad --> un programa especializado
2. Guardar los discos con las copias en una ubicación distinta que el servidor.
3. (Recuperar) Hacer un RESTORE.


### Sesión 10J

[tipos de backups](https://blog.mdcloud.es/tipos-de-copias-de-seguridad-como-elegir-el-adecuado/)

Actividad: realización de backups en MV:
1. Con el sistema propio de Windows

  Pasos:  
  a. Añadir un nuevo disco a la Maquina Virtual  
  b. Dentro de Windows (MV) y usando la herramienta de particiones:   
      - Inicializar el disco  
      - Particionar, formatear y asignarle una letra al disco  
  c. Usando la utilidad de Backup settings de Windows:  
      - Añadir el disco de backup  
      - Confgurar el backup (botón more options) para que:  
         - Haga un backup diario  
         - Haga backup de la unidad D: de Datos  
         - Excluya una carpeta llamada "Temporales" que habréis creado antes en la unidad D de datos.  
         - Os descargáis algún fichero de Internet en Downloads.  
         - Miráis el tamaño que tenga la unidad de Backup ANTES de hacer el backup.  
         - Hacéis el backup (botón Backup Ahora)  
         - Mirad el tamaño de la unidad de backup DESPUÉS del backup y comparáis.  



2. Con perfect-backup
3. En Linux Lite

- Teoría Arquitectura

### Sesión 11J

Enlaces vistos en clase:

https://softwarekeep.com/blog/ssd-vs-hdd-difference

https://concepto.de/espectro-electromagnetico/

https://www.notebookcheck.net/PWM-Ranking-Notebooks-Smartphones-and-Tablets-with-PWM.163979.0.html



- Software: 
  - Utilidades Windows: 7zip, cpu-z, notepad++,  acrobat reader, ccleaner
  - Multimedia: VLC, XnView

Actividad 1:

1- Descargar el 7zip en formato exe y msi
2- Activar las extensiones de ficheros en el navegador de ficheros
de Windows
3- Desactivar el UAC
4- Instalar el 7-zip
5- Empaquetar y comprimir, usando 7zip, todos los
ficheros que tengais en Downloads
6- Moveis el fichero 7zip (o zip) creado en el paso
anterior, a la unidad F: de backup
7- (En la unidad de backup) Extaer los
contenidos del fichero 7zip, y comprobáis que
son los mismos contenidos que los originales.

Actividad 2:

1- Descargar e instalar Notepad++
2- Crear un fichero de texto y editarlo con Notepad++
3- Configurar Windows para que, por defecto, use
Notepad++ en lugar del Notepad de Windows.
4- Abrir el documento creado en el paso 2, y con
Notepad++, haced que el documento sea
compatible con sistemas Linux.

Actividad 3:
1. Descargar e instalar el Acrobat Reader (en la MV de Windows)
2. Configurar Windows para que abra los documentos PDF con Acrobat Reader por defecto.

Actividad 4:
1. Descargar e instalar el ccleaner (en MV y en amfitrión). Instalación personalizada: desactivar Scaneo inteligente de cookies.
2. Hacer una limpieza del ordenador (Windows de MV y amfitrión)-
   

- Configuració Windows: 
  - Icones escriptori
  - Extensió fitxers (-> Magic Numbers)
  - Desactivar UAC

- Teoría redes
  - TCP / UDP / IP
  - LAN, WAN, Internet
  - Routers, hubs, switchs
  - Wifi vs rj45 cat 5,6,7,8 (ethernet)
  - ADSL / Fibra òptica / Connexió de backup
  
- Manteniment
  - Registre
  - Documentació d'avaries
  - Reposició de fungibles
  
Si tenemos en cuenta el uso del equipo, se puede confeccionar un cuadro con las siguientes periodicidades:

```
Uso					Periodicidad
---					---
Muy poco uso		Anual	
Uso esporádico		Semestral
Uso intensivo		Trimestral/Bimestral
Uso muy intensivo	Mensual/Bimestral
```

- Seguretat en xarxes: 
  - Tallafoc
  - VPN
  
- Seguretat: contrasenyes segures

[How secure is my password](https://www.security.org/how-secure-is-my-password/)
  
- Compartició de fitxers i protocols:
  - NFS
  - SAMBA
  - FTP
  - ssh

#### Activitat: servidor FTP a Linux Lite i Filezilla a Windows.
  