# Descripción

Mi nombre es Anibal Rodrigo Corini Apaza, actualmente soy Técnico Superior en Sistemas Informáticos. El presente proyecto se contempla como un esquema de landing page para la empresa Manaco como primer examen de la materia "Tecnologías de Internet" en la carrera de Ingeniería de Sistemas de la Universidad Adventista de Bolivia.

## Accesibilidad (a11y)

Se implementaron varias mejoras para que el sitio sea accesible a todos los usuarios, incluyendo aquellos que usan teclado o lectores de pantalla:

- **Navegación por teclado:** todos los enlaces `<a>` y botones `<button>` son focoables, permitiendo recorrer la página sin mouse.
- **Foco visible:** se agregaron estilos CSS claros para que el usuario siempre vea cuál elemento tiene el foco (`outline`).
- **Imágenes con `alt` descriptivo:** cada producto tiene texto alternativo claro para que los lectores de pantalla describan correctamente el contenido visual.
- **Uso de roles y ARIA:** se añadieron `aria-label` en `<nav>`, `<section>` y `<footer>` solo donde es necesario para describir regiones.
- **Semántica correcta:** se usaron `<header>`, `<main>`, `<section>`, `<article>` y `<footer>` para estructurar la página de forma comprensible para todos los dispositivos de asistencia.

## SEO

Se aplicaron algunas buenas prácticas de SEO para mejorar la visibilidad del sitio:

- **Meta description:** breve y concisa para atraer clics en buscadores.
- **Open Graph mínimo:** permite compartir correctamente en redes sociales.
- **Jerarquía de títulos:** `<h1>` para la marca y `<h2>/<h3>` para secciones y productos.
- **Alt en imágenes:** describe cada producto para SEO y accesibilidad.
