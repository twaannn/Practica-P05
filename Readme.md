# P05 - Despliegue de aplicaciones web con docker compose

# Autores

Daniel Pérez y Antoine Román 

# Requisitos

Necesitamos Docker y un IDE donde podamos trabajar.
La jerarquía que vamos a seguir es cada servicio en una carpeta y dentro el .yml con el que vamos a crear los servicios.

# Referencias

La información la he sacado de las páginas
https://hub.docker.com

# Adminer

Creamos el archivo .yml con el servicio de la aplicación adminer y una base de datos.
Ejecutamos el comando docker-compose up -d.
Vemos que nos ha creado la imagen de adminer y nos ejecuta el contenedor.
Ejecutamos el contenedor en un navegador y vemos que se ejecuta correctamente.

Versión: 3.1

# Apache

Creamos el archivo .yml con el servicio de la aplicación httpd.
Ejecutamos el comando docker-compose up -d.
Vemos que nos ha creado la imagen y nos ejecuta el contenedor.
Ejecutamos el contenedor en un navegador y vemos que se ejecuta correctamente.

Versión: 3.9

# Guestbook

Creamos el archivo .yml con el servicio de la aplicación guestbook y la base de datos.
Ejecutamos el comando docker-compose up -d.
Vemos que nos ha creado la imagen y nos ejecuta el contenedor.
Ejecutamos el contenedor en un navegador y vemos que se ejecuta correctamente.

Versión: 3.1

# MediaWiki

Creamos el archivo .yml con el servicio de la aplicación MediaWiki y la base de datos.
Ejecutamos el comando docker-compose up -d.
Vemos que nos ha creado la imagen y nos ejecuta el contenedor.
Ejecutamos el contenedor en un navegador y descargamos el LocalSettings.php y lo copiamos en /var/www/html


Versión: 3

# WordPress

Creamos el archivo .yml con el servicio de la aplicación WordPress y la base de datos.
Ejecutamos el comando docker-compose up -d.
Vemos que nos ha creado la imagen y nos ejecuta el contenedor.
Ejecutamos el contenedor en un navegador y vemos que se ejecuta correctamente.

Versión: 3.1