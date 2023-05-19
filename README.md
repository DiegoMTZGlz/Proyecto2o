# Proyecto DBP #2

Proyecto basado en un script programado en una imagen de docker para ejecutar un servidor desde JS para poder visualizar un sitio web.

## Empezando

Éstas instrucciones son para la ejecución correcta del servidor o imagen de docker

### Prerequsítos

Terminal

Deberemos descargar la imagen desde docker
```
docker pull diegomtzglz/proyectodbpdos:latest
```
Luego crearemos un contenedor con la imágen
```
docker run -d --name >nombre_contenedor> -t -p 8888:8888 diegomtzglz/proyectodbpdos:latest
```
## Ejecución
Para acceder al servidor podemos seguir la siguiente liga: http://localhost:8888

## Hecho con:

* [JavaScript](https://www.javascript.com/) - Lenguaje utilizado.
* [Node-js](https://nodejs.org/es) - Entorno de ejecución .
* [HTTP](https://httpwg.org/specs/) - Protocolo de Servidor.
* [HTML](https://www.w3docs.com/learn-html.html) - Leanguaje para construir el sitio web.
* [CSS](https://www.w3docs.com/learn-css.html) - Lenguaje para estilizar el sitio web.
* [docker](https://www.docker.com/) - Usado para crear la imagen ejecutable.

## Integrantes

* **Diego Martínez - 353198** - [DiegoMTZGlz](https://github.com/DiegoMTZGlz)

## Repositorios

* **GitHub** - (https://github.com/DiegoMTZGlz/Proyecto2o)
* **DockerHub** (https://hub.docker.com/r/diegomtzglz/proyectodbpdos)
