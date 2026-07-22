# Proyecto Final - 
# Proyecto SEO - Productos Innovadores

## Descripción

Este proyecto consiste en el desarrollo de un sitio web utilizando HTML5 y CSS3, aplicando buenas prácticas de desarrollo web, accesibilidad, diseño responsive y optimización SEO.

El objetivo es ofrecer una experiencia de usuario de calidad y mejorar la visibilidad del sitio en los motores de búsqueda mediante técnicas de SEO On-Page y SEO Técnico.

---

# Tecnologías utilizadas

- HTML5
- CSS3
- Diseño Responsive
- SEO On-Page
- SEO Técnico
- Git
- GitHub

---

# Estructura del proyecto

```
Proyecto-SEO/

│
├── index.html
├── productos.html
├── contacto.html
│
├── css/
│   └── styles.css
│
├── img/
│   ├── producto1.webp
│   ├── producto2.webp
│   └── producto3.webp
│
├── robots.txt
├── sitemap.xml
├── .htaccess
└── README.md
```

---

# SEO Técnico

Se implementaron diferentes técnicas para mejorar la indexación del sitio web.

## robots.txt

Se creó el archivo `robots.txt` para indicar a los motores de búsqueda qué contenido puede ser rastreado.

Configuración aplicada:

- Permitir el rastreo general del sitio.
- Bloquear carpetas privadas.
- Declarar la ubicación del sitemap.

---

## sitemap.xml

Se creó un archivo `sitemap.xml` con las páginas principales del sitio.

Incluye:

- URL de cada página.
- Fecha de última modificación.
- Prioridad de indexación.

Esto facilita que Google encuentre e indexe el contenido.

---

## Canonical

Todas las páginas incluyen la etiqueta:

```html
<link rel="canonical" href="URL-preferida">
```

Su finalidad es evitar contenido duplicado y definir la versión principal de cada página.

---

## Redirecciones 301

Se implementó un archivo `.htaccess` con redirecciones permanentes para conservar la autoridad SEO cuando una URL cambia.

---

# SEO On-Page

## Title

Cada página posee un título único y descriptivo.

Ejemplo:

```
Productos Innovadores | Tecnología y Soluciones Modernas
```

---

## Meta Description

Se agregaron meta descripciones optimizadas para cada página.

Ejemplo:

```
Descubre productos innovadores y tecnológicos con diseños modernos y soluciones para tu día a día.
```

---

## Headings

Se organizó correctamente la jerarquía de encabezados utilizando:

- H1 para el título principal.
- H2 para las secciones.
- H3 para los subtítulos.

Esto mejora la comprensión del contenido por parte de Google.

---

## Investigación de Palabras Clave

Se seleccionaron palabras clave relacionadas con el contenido del sitio:

- Productos innovadores.
- Productos tecnológicos.
- Comprar productos online.

Estas palabras fueron utilizadas de manera natural en:

- Títulos.
- Encabezados.
- Meta descripciones.
- Contenido.
- Textos alternativos.

---

## Imágenes

Las imágenes fueron optimizadas mediante:

- Formato WebP.
- Atributos ALT personalizados.
- Carga diferida mediante `loading="lazy"`.

Ejemplo:

```html
<img
src="producto.webp"
alt="Producto tecnológico innovador"
loading="lazy">
```

---

# Accesibilidad

Se implementaron diversas mejoras para facilitar la navegación.

## Focus

Todos los elementos interactivos cuentan con estilos `:focus-visible`.

Esto permite identificar fácilmente el elemento seleccionado al navegar con teclado.

---

## Skip Link

Se agregó un enlace "Saltar al contenido principal" para mejorar la accesibilidad.

---

## Formularios

Todos los formularios utilizan correctamente:

- label
- for
- id

Ejemplo:

```html
<label for="nombre">Nombre</label>

<input
id="nombre"
type="text">
```

Esto mejora la compatibilidad con lectores de pantalla.

---

# Diseño Responsive

Se agregaron Media Queries para adaptar el sitio a distintos dispositivos.

### Tablet

```
@media (max-width: 992px)
```

### Celulares

```
@media (max-width: 576px)
```

Además:

- Imágenes adaptativas.
- Navegación responsive.
- Formularios adaptables.
- Ajuste de tipografía.

---

# Buenas prácticas implementadas

- HTML5 semántico.
- Navegación uniforme en todas las páginas.
- Código organizado.
- Etiquetas ALT descriptivas.
- Meta etiquetas optimizadas.
- Canonical.
- robots.txt.
- sitemap.xml.
- Redirecciones 301.
- Diseño responsive.
- Accesibilidad WCAG.
- Optimización SEO.

---

# Reflexión

Durante el desarrollo del proyecto se aplicaron diferentes técnicas de SEO para mejorar la indexabilidad y la experiencia del usuario.

El archivo robots.txt permite controlar el rastreo de los motores de búsqueda, mientras que el sitemap.xml facilita la indexación de las páginas principales.

Las etiquetas canonical ayudan a evitar problemas de contenido duplicado y las redirecciones 301 permiten conservar la autoridad SEO cuando una URL cambia.

También se optimizó el contenido mediante el uso de palabras clave, meta etiquetas, encabezados correctamente estructurados e imágenes optimizadas.

Finalmente, se incorporaron mejoras de accesibilidad y diseño responsive para garantizar una mejor experiencia de navegación en diferentes dispositivos y para usuarios que utilizan tecnologías asistivas.

---

# Mejoras futuras

- Integración con Google Search Console.
- Monitoreo del rendimiento SEO.
- Optimización continua del contenido.
- Incorporación de nuevas palabras clave.
- Análisis del posicionamiento mediante herramientas como Google Keyword Planner y SurferSEO.



Desarrollo Web

## Descripción

Este proyecto consiste en un sitio web desarrollado con HTML5, CSS3 y Bootstrap, aplicando buenas prácticas de SEO, accesibilidad y diseño responsive.

## Tecnologías

- HTML5
- CSS3
- Bootstrap 5
- Git
- GitHub

## Características

- Diseño Responsive
- Optimización SEO
- Imágenes optimizadas
- Accesibilidad
- Formularios
- Bootstrap 5

## Instalación

1. Clonar el repositorio

(https://github.com/josuecalistro/M9-SEO-Proyecto.git)

2. Abrir index.html en el navegador.

## Proyecto desplegado

https://app.netlify.com/projects/vermillion-basbousa-79b735/deploys/6a6142f81e9fc5784595f059

## Autor

Josue Calistro