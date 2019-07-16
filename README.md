# Configuracion entorno de desarrollo  web

## introduccion

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

La instalacion de Xammp la optenemos de su paguina oficial, www.apachefriends.org.
desde alli comenzaremos la instalacion en el disco local.

![Xammpfoto1](/MEDIA/6_Install_Xampp.PNG))

Al terminar la instalacion , desde el directorio de Xammp, iniciamos el programa desde controlpanel con privilegios de administrador, despues clicxamos el servicio Apache para que quede activo siempre y lo arraque windows, tambien arrancamos el serrcio con START

![Xammpfoto2](/MEDIA/12_Install_Xampp.PNG))

## Configuracion Virtual Host de Apache

 Para implementar  la fase de declarar un virtual host, añadimos codigo en dos archivos, uno de ellos "httpd-xampp.conf" lo encontramos en el directorio de xammp, /apache/conf/extra.
 
 
 
 
 
 El otro fichero que se ha de modificar es "hosts", lo encontramos en la siguiente ruta del disco de sistema, C:/Windows/System32/drivers/etc/. añadimos el codigo y salvamos con privilegios de Administrador.
 
 
 
 
 ## Instalacion de Eclipse
 
 Eclipse sera nuestro editor IDE de cabecera, para su instalacion nos iremos a su paguina oficial y descargaremos el instalador, para el proceso de instalacion, eclipse requiere tenewr instalado previamente JAVA. Durante la instalcion habremos de elegir un entorno de lenguaje para el desarrollo.
 
![Xammpfoto1](/MEDIA/12_Install_Eclipse.PNG)) 

A continuacion nos pedira una ruta donde repositar los trabajos.

![Xammpfoto1](/MEDIA/20_Install_Eclipse.PNG)) 
 
 
## Definicion de WorkSpace
Al final de la instalación de eclipse, nos hace mencion del WorkSpace, sera muy importante declara un directorio al que llamaremos Projectes, y desde el cual partiran este los sucesivos trabajos, a partir de ahora, a este escenario, eclipse lo llama WorkSpace, encontraremos una opcion para senetnciarlo como defecto y olvidarnos de la operacion en sucesivos trabajos.



## Definicion de Projecto

Para definir el nuevo projecto, nos vamos dentro de eclipse, a: archivo --> nuevo--> PHP Project.  alli declaramos el nuevo projecto "pla1.pqtm19.local".

![Xammpfoto1](/MEDIA/foto1.png))

## Definicion del repositorio local

Desde la perspectiva GIT, creamos un nuevo repositorio local que llamaremos como el nuevo projecto "pla1.pqtm19.local".
ahora tendremos creado el repositorio GIT solo desde la vertiente de editor eclipse, nosfalta generarlo en github, que sera el siguiente paso.






## Creacion de repositorio Github

Una vez alojados en nuestra plataforma Github, crearemos un nuevo repositorio llamado "pla1.pqtm19.local"




## Exportacion de la Rama "master" local sobre repositorio Github





