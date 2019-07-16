# Configuración entorno de desarrollo  web

## introducción
El ejercicio consiste en crear un escenario de trabajo, con las herramientas Xammp, eclipse y Github.
Este entorno nos situará en un host virtual con un directorio de proyectos, en el cual residirán todos los siguientes proyectos, de esta manera simularemos una web externa donde los trabajos podrán ser desarrollados y testados.
Con Github obtendremos la seguridad de las modificaciones y cambios dentro de la evolución del proyecto, durante los procesos de desarrollo se crearan Ramas (versiones) del proyecto que consolidaran el estado de seguridad de la vida de creación del mismo.

## Indice.

- [Instalacion de Xammp](#instalacion-de-xammp)
- [Configuracion Virtual Host de Apache](#configuracion-virtual-host-de-apache)
- [Instalacion de Eclipse](#instalacion-de-eclipse)
- [Definicion de WorkSpace](#definicion-de-workspace)
- [Definicion de Projecto](#definicion-de-projecto)
- [Definicion del repositorio local](#definicion-del-repositorio-local)
- [Creacion de repositorio Github](#creacion-de-repositorio-github)
- [Exportacion de la Rama master local sobre repositorio Github](#exportacion-de-la-rama-master-local-sobre-repositorio-github)

 

## Instalacion de Xammp

 La instalación de Xammp la obtenemos de su página oficial, www.apachefriends.org.
desde allí comenzaremos la instalación en el disco local.


![Xammpfoto1](/MEDIA/6_Install_Xampp.PNG))

Al terminar la instalación , desde el directorio de Xammp, iniciamos el programa desde “controlpanel” con privilegios de administrador, después clicamos el servicio Apache para que quede activo siempre y lo arranque Windows, también arrancamos el servicio con START

![Xammpfoto2](/MEDIA/12_Install_Xampp.PNG))

## Configuracion Virtual Host de Apache

  Para implementar  la fase de declarar un virtual host, añadimos código en dos archivos, uno de ellos "httpd-xampp.conf" lo encontramos en el directorio de xammp, /apache/conf/extra. 
 
 ![VirtualHfoto1](/MEDIA/virtual1.png))
 
 
 El otro fichero que se ha de modificar es "hosts", lo encontramos en la siguiente ruta del disco de sistema, C:/Windows/System32/drivers/etc/. añadimos el código y salvamos con privilegios de Administrador.
 
  ![VirtualHfoto2](/MEDIA/codigo_host.png))
 
 
 ## Instalacion de Eclipse
 
 Eclipse será nuestro editor IDE de cabecera, para su instalación nos iremos a su página oficial  www.eclipse.org  y descargaremos el instalador, para el proceso de instalación, eclipse requiere tener instalado previamente JAVA. Durante la instalación habremos de elegir un entorno de lenguaje para el desarrollo.
 
![eclipsefoto1](/MEDIA/12_Install_Eclipse.PNG)) 

A continuacion nos pedirá una ruta donde instalar Eclipse.

![eclipsefoto2](/MEDIA/18_Install_Eclipse.PNG)) 
 
 
## Definicion de WorkSpace
Al final de la instalación de eclipse, nos hace mención del WorkSpace, será muy importante declarar un directorio al que llamaremos PROJECTES, y desde el cual partirán este y los sucesivos trabajos, a partir de ahora, a este escenario, eclipse lo llama WorkSpace, encontraremos una opción para sentenciarlo por defecto y olvidarnos de la operación en sucesivos trabajos.

![eclipsefoto3](/MEDIA/20_Install_Eclipse.PNG)) 

## Definicion de Projecto

 Para definir el nuevo proyecto, nos vamos dentro de eclipse, a: archivo --> nuevo--> PHP Project.  allí declaramos el nuevo proyecto "pla1.pqtm19.local
 
![eclipsefoto4](/MEDIA/foto1.png))

## Definicion del repositorio local

Desde la perspectiva GIT, creamos un nuevo repositorio local que llamaremos como el nuevo proyecto "pla1.pqtm19.local".
ahora tendremos creado el repositorio GIT solo desde la vertiente de editor eclipse, nos falta generarlo en github, que será el siguiente paso. ".


![eclipsefoto5](/MEDIA/foto5.png))



## Creacion de repositorio Github

Una vez alojados en nuestra plataforma Github, crearemos un nuevo repositorio llamado "pla1.pqtm19.local"

![Githubfoto1](/MEDIA/foto3.png))


## Exportacion de la Rama "master" local sobre repositorio Github


 En este punto, tenemos creado el repositorio Git en los dos entornos (Eclipse y  GitHub) solo nos falta sincronizarlos , antes crearemos las carpetas del proyecto y colocaremos unas fotos en una de ellas, que nos servirán para implementar el Fichero README.md, muy importante dentro de cualquier repositorio digno de mención.
 
![eclipsebfoto10](/MEDIA/foto10.png))


