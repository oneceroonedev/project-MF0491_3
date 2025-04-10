# IFCD0210__MF0491_3 - MÓDULO 1__PROGRAMACIÓN WEB EN EL ENTORNO CLIENTE
Este repositorio contiene el proyecto final del Módulo 1 del Certificado de Profesionalidad "IFCD0210 - Desarrollo de aplicaciones con tecnologías web", centrado en la programación web en el entorno cliente. Partiendo de un diseño en Figma, el objetivo ha sido desarrollar una página web completamente funcional utilizando código puro.

## Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript

## Herramientas utilizadas
- Git
- Netlify

No se ha utilizado ningún framework, pero tanto el CSS como el JavaScript siguen una estructura basada en componentes. La maquetación se ha realizado con un enfoque mobile first y es completamente responsive, adaptándose a dispositivos móviles, tabletas y ordenadores de escritorio.

## Home (index.html)
En las versiones móviles y de tabletas, se han ocultado ciertos elementos decorativos, como las imágenes que acompañan al personaje principal en la versión de escritorio y los memojis de la sección de reseñas. Se ha implementado un menú tipo hamburguesa, que ocupa el 100% del ancho y alto del dispositivo.

## Projects (project.html)
Esta página es totalmente dinámica: la información se carga mediante JavaScript desde un archivo JSON proporcionado.

## Contact (contact.html + received.html)
Incluye un formulario de contacto con validación personalizada implementada en JavaScript, desactivando la validación nativa del navegador, para su correcta ejecución. Una vez enviado correctamente el formulario, el usuario es redirigido a una página de confirmación donde se muestran los datos introducidos a través de la URL.

## 404 (404.html)
Se ha diseñado una página de error 404, enlazada desde las tarjetas de servicios en la Home y desde distintos elementos del footer. Esta decisión se ha tomado al no contar con diseños específicos para dichas páginas.

## Destacados
- Se han añadido efectos hover a todas las tarjetas de la web.
- La imagen de la página 404, al no tener diseño, se ha utilizado la de la página principal, y con la ayuda de inteligencia artifical se ha creado una imagen nueva siguiendo la linea del contenido para una página de error.
- Se ha añadido un favicon a la web.
- Se ha implementado una navegación fluida entre las distintas secciones del sitio mediante los elementos del menú principal (header). Dado que no se contaba con una página específica para proyectos o servicios, los enlaces se anclan a secciones correspondientes dentro de la Home.       
- Se ha incorporado un botón de "scroll up" para facilitar el regreso a la parte superior de la página.

## Deploy
El proyecto ha sido desplegado en la plataforma Netlify, lo que permite acceder a la versión en línea directamente desde cualquier dispositivo. A continuación, se incluye el enlace para acceder al sitio web:

https://ifcd0210-m1-ironhack.netlify.app/