# premileal-docker - Pasos para correr la apliación usando Docker.

En primer lugar, se deben descargar las imagenes que se mencionan a continuación para poder correr la aplicación.

docker pull rafa98/premileal-front:front-v1

docker pull rafa98/premileal-back:back-v1

docker pull rafa98/premileal-database:database-v1

Luego, escoger alguna carpeta de su computador que sea conveniente y clonar este repositorio: 

git clone https://github.com/RafaelMendezUCAB/premileal-docker.git

Abrir la consola de comando y situarse en dicha carpeta para así ejecutar el siguiente comando:

docker-compose up

Los contenedores serán inicializados y una vez estén todos activos, abrir el navegador e ir a: localhost:8080 y hacer uso de la aplicación.