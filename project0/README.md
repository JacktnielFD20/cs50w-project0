# Project 0

Web Programming with Python and JavaScript
# cs50w-project0
mi project0 en si se basa en una pagina que muestra todos mis gustos personales, ya sea en peliculas, deporte, series etc
HTML:
Empecé creando un archivo HTML para mi sitio web. Definí la estructura básica utilizando la etiqueta <!DOCTYPE html>. Luego, en la sección head, agregué algunas metaetiquetas para el juego de caracteres y la vista en dispositivos móviles. Enlazé las hojas de estilo necesarias para mi sitio, incluyendo la hoja de estilo de Bootstrap y mi propia hoja de estilo CSS. También agregué el enlace a los iconos de Font Awesome.

Dentro del cuerpo (<body>), comencé con una etiqueta de título (<title>) para darle un nombre a mi sitio web. Usé la clase container de Bootstrap para crear un contenedor centralizado para mi contenido. Dentro de este contenedor, coloqué un encabezado grande llamado jumbotron con un título y una descripción. Debajo del jumbotron, organicé cuatro tarjetas utilizando el sistema de grillas de Bootstrap (row y col-md-3). Cada tarjeta contiene una imagen y un título relacionado con mis intereses. Para las tarjetas, usé la clase card de Bootstrap y agregué botones que enlazan a diferentes páginas de mi sitio.

Al final de la página, añadí un pie de página (footer) con enlaces a mis redes sociales. Utilicé las clases de Bootstrap para organizar los elementos de manera ordenada.

SASS (CSS):
Para los estilos, comencé definiendo algunos colores personalizados utilizando variables. Estos colores los usé para dar estilo a diferentes partes de mi sitio web. Creé una clase base llamada .base-style que establece propiedades generales como fondo, color de texto y tipo de fuente.

Dentro de la hoja de estilo, también definí estilos específicos para el encabezado (header), jumbotron, tarjetas de contenido (card), botones (btn-primary) y el pie de página (footer). Utilicé pseudo-selectores como :hover para aplicar cambios de estilo cuando el usuario interactúa con los elementos.

Además, apliqué estilos responsivos usando @media queries para adaptar el diseño en pantallas más pequeñas. Esto asegura que mi sitio se vea bien en diferentes dispositivos, como teléfonos móviles y tabletas.

En cuanto a la estructura del código, agrupé elementos relacionados en bloques con clases y utilicé anidamiento para mantener mi hoja de estilo organizada. También aproveché la herencia de estilos para aplicar propiedades similares a varios elementos.