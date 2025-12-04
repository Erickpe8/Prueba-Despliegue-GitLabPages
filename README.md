# WebApp – Suma con Emojis (GitLab Pages)

Este proyecto es una prueba donde se despliega una aplicación web mediante GitLab Pages.  
La aplicación permite sumar dos números y mostrar el resultado usando una conversión a caracteres tipo emoji.  
Toda la lógica se ejecuta en el navegador utilizando HTML, Bootstrap y JavaScript.

## Estructura del proyecto

- `public/index.html`: Página principal del sitio.
- `public/lab1.html`: Aplicación monolítica donde se realiza la suma.
- `public/diagrama.png`: Diagrama de arquitectura del proyecto.
- `.gitlab-ci.yml`: Pipeline encargado del despliegue automático en GitLab Pages.

## Diagrama de arquitectura

A continuación se incluye el diagrama almacenado en la carpeta `public`:

![Diagrama de Arquitectura](public/diagramaa.png)

## Despliegue

El pipeline de GitLab Pages toma los archivos ubicados en la carpeta `public` y los publica automáticamente cada vez que se realiza un commit en la rama principal.  
El resultado es un sitio estático accesible desde la URL generada por GitLab Pages.

