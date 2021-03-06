<img src="../../imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

<img src="../../imagenes/logoApa.jpg" />

# Instalación Apache Directory Studio
[Link a Apache Directory Studio](https://directory.apache.org/studio/download/download-linux.html)
## Como Root
### Creamos Directorio de trabajo

``mkdir /home/fran/apacheDirectoryStudio``

``cd /home/fran/apacheDirectoryStudio``

### Descarga desde un mirror Oficial

``wget https://ftp.cixug.es/apache/directory/studio/2.0.0.v20200411-M15/ApacheDirectoryStudio-2.0.0.v20200411-M15-linux.gtk.x86_64.tar.gz``

### Descomprimimos

``tar -zvxf ApacheDirectoryStudio-2.0.0.v20200411-M15-linux.gtk.x86_64.tar.gz``

Cambiamos permisos y propitarios sobre el directorio de trabajo de Apache Directory Studio

``ls -l``

``chown -R fran:fran /home/fran/apacheDirectoryStudio/``

### Instalamos la OpenJDK (Es necesario para su uso)

``apt install default-jdk``

``apt install default-jre``

**¡Ojo! También podemos intalar una versión específica...**

**apt install openjdk-11-jdk**
**apt install openjdk-11-jre**

## Sin privilegios de root

### Comprobamos que tengamos privilegios necesarios

``cd ~/apacheDirectoryStudio/``

``ls -l``

### Ejecutamos Apache Directory Studio

``./ApacheDirectoryStudio``

**Listo**

## Configuración Apache Directory Studio (Gráfico)

### Creamos la conexión con servidor LDAP

![Conexion](../../imagenes/conexion.png)

![Conexion2](../../imagenes/conexion2.png)

![Conexion3](../../imagenes/conexion3.png)

![Conexion4](../../imagenes/conexion4.png)

![Conexion5](../../imagenes/conexion5.png)

*[Algunas capturas varias de como crear entradas...](../../imagenes/capturas)*
_________________________________________________
*[Volver atrás...](../README.md)*

*[Volver al indice pincipal...](../../README.md)*