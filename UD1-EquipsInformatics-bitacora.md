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
2. Con perfect-backup
3. En Linux Lite

- Teoría Arquitectura

- Software: 
  - Utilidades Windows: 7zip, ccleaner, notepad++, acrobat
  - Multimedia: VLC, XnView
- Configuració Windows: 
  - Icones escriptori
  - Extensió fitxers (-> Magic Numbers)

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
  