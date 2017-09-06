# orionv2
Stack Docker Lamp para Orion.

En el servicio httpd está habilitado el volumen:
  volumes:
    - ./public_html:/var/www/html

Esto implica que en el lugar en el que ejecutes el stack vas a tener la aplicación (orion)
dentro de una carpeta llamada public_html.
