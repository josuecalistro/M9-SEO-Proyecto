# Productos Innovadores

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un sitio web utilizando HTML5 y CSS3, aplicando buenas prácticas de estructura, accesibilidad, diseño responsive y optimización SEO.

El objetivo principal es crear un sitio preparado para ser interpretado correctamente por los motores de búsqueda, ofreciendo una mejor experiencia para los usuarios en diferentes dispositivos.

---

# Tecnologías utilizadas

- HTML5
- CSS3
- Diseño Responsive
- SEO Técnico
- Optimización de imágenes
- Git y GitHub

---

# Estructura del proyecto


Proyecto-SEO/

│
├── index.html
├── productos.html
├── contacto.html
│
├── css/
│ └── styles.css
│
├── img/
│ ├── producto1.webp
│ ├── producto2.webp
│ └── producto3.webp
│
├── robots.txt
├── sitemap.xml
├── .htaccess
└── README.md


---

# Implementaciones SEO

## Archivo robots.txt

Se creó el archivo `robots.txt` para controlar el comportamiento de los motores de búsqueda.

Funciones implementadas:

- Permitir el rastreo general del sitio.
- Bloquear carpetas privadas o administrativas.
- Declarar la ubicación del sitemap.xml.

Esto ayuda a mejorar la gestión del rastreo por parte de los crawlers.

---

## Sitemap.xml

Se implementó el archivo `sitemap.xml` con las principales URLs del sitio.

Incluye:

- URL de cada página.
- Fecha de última modificación.
- Prioridad de cada sección.

Su objetivo es facilitar que los buscadores encuentren e indexen correctamente el contenido.

---

## Canonicalización

Se agregaron etiquetas canonical en las páginas HTML:

```html
<link rel="canonical" href="URL-preferida">

Esto permite indicar a los motores de búsqueda cuál es la versión principal de una página y evitar problemas de contenido duplicado.

Redirecciones 301

Se configuraron redirecciones permanentes mediante .htaccess.

Su función es mantener la autoridad SEO cuando una URL cambia, evitando:

Errores 404.
Pérdida de posicionamiento.
Mala experiencia del usuario.
Mejoras HTML5 y Semántica Web

Se corrigió la estructura del HTML utilizando etiquetas semánticas:

<header>
<nav>
<main>
<section>
<footer>

Esto permite que los motores de búsqueda y tecnologías asistivas interpreten mejor el contenido.

Se evitó el uso incorrecto de etiquetas, como colocar un <main> dentro de un <footer>, ya que puede afectar la comprensión del documento por parte de los crawlers.

Sistema de navegación

Se implementó una navegación uniforme en todas las páginas del sitio.

Todas las secciones incluyen:

Inicio.
Productos.
Contacto.

Esto mejora la experiencia del usuario y facilita el rastreo interno del sitio.

Optimización de imágenes

Las imágenes fueron optimizadas utilizando formato WebP para mejorar la velocidad de carga.

Además, se implementaron atributos importantes:

<img 
src="imagen.webp"
alt="Descripción de la imagen"
loading="lazy">

Beneficios:

Mejor rendimiento.
Mejor accesibilidad.
Mejor posicionamiento SEO.
Diseño Responsive

El diseño fue adaptado para diferentes tamaños de pantalla mediante Media Queries.

Se aplicaron mejoras como:

img{
max-width:100%;
height:auto;
}

Esto permite que las imágenes sean adaptativas y evita problemas de visualización en dispositivos pequeños.

También se agregaron estilos responsive para:

Navegación móvil.
Ajuste de tamaños de texto.
Adaptación del contenido.
Accesibilidad

Se mejoraron los formularios asociando correctamente etiquetas e inputs.

Ejemplo:

<label for="nombre">
Nombre:
</label>

<input 
id="nombre"
type="text">

Esto permite que los lectores de pantalla interpreten correctamente cada campo.

Buenas prácticas aplicadas

✅ HTML5 semántico
✅ CSS organizado
✅ Diseño adaptable
✅ Imágenes optimizadas
✅ Atributos ALT personalizados
✅ Navegación consistente
✅ SEO técnico implementado
✅ Formularios accesibles
✅ Código preparado para buscadores

Objetivo del proyecto

Crear un sitio web optimizado para usuarios y motores de búsqueda, aplicando técnicas de SEO técnico que mejoren la indexabilidad, accesibilidad y experiencia de navegación.

Reflexión SEO

La implementación de configuraciones como robots.txt, sitemap.xml, canonicalización y redirecciones 301 mejora la manera en que los motores de búsqueda descubren, interpretan e indexan un sitio web.

El archivo robots.txt permite controlar qué contenido debe ser rastreado, mientras que el sitemap.xml facilita la identificación de las páginas importantes del proyecto.

Las etiquetas canonical ayudan a evitar problemas de contenido duplicado indicando cuál es la versión principal de una URL. Por otro lado, las redirecciones 301 permiten conservar la autoridad SEO cuando se modifican direcciones antiguas.

Además, aplicar HTML semántico, imágenes optimizadas y diseño responsive mejora tanto la experiencia del usuario como la comprensión del sitio por parte de los buscadores.