# Configuracion entorno de desarrollo  web

## introduccion

## Indice.

- [Instalacion de Xammp](#instalacion-de-xammp)
- [Configuracion Virtual Host de Apache](#configuracion-virtual-host-de-apache)
- [Instalacion de Eclipse](#instalacion-de-eclipse)
 

## Instalacion de Xammp

La instalacion de Xammp la optenemos de su paguina oficial, www.apachefriends.org.
desde alli comenzaremos la instalacion en el disco local.

![Xammpfoto1](/MEDIA/6_Install_Xampp.PNG))

Al terminar la instalacion , desde el directorio de Xammp, iniciamos el programa desde controlpanel con privilegios de administrador, despues clicxamos el servicio Apache para que quede activo siempre y lo arraque windows, tambien arrancamos el serrcio con START

![Xammpfoto1](/MEDIA/12_Install_Xampp.PNG))

## Configuracion Virtual Host de Apache

 Para implementar  la fase de declarar un virtual host, añadimos codigo en dos archivos, uno de ellos "httpd-xampp.conf" lo encontramos en el directorio de xammp, /apache/conf/extra.
 
 
 
 
 
 El otro fichero que se ha de modificar es "hosts", lo encontramos en la siguiente ruta del disco de sistema, C:/Windows/System32/drivers/etc/. añadimos el codigo y salvamos con privilegios de Administrador.
 
 
 
 
 ## Instalacion de Eclipse
 
 Eclipse sera nuestro editor IDE de cabecera, para su instalacion nos iremos a su paguina oficial y descargaremos el instalador, para el proceso de instalacion, eclipse requiere tenewr instalado previamente JAVA.
 
 
