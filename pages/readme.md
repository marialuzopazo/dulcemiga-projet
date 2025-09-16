# 📁 Páginas - Dulce Miga Pastelería

Esta carpeta contiene todas las páginas HTML del sitio web de Dulce Miga / todos los que no son el index.
Cada página fue desarrollada con **HTML5 semántico** y **CSS3 puro**

## Estructura de Archivos :)

### 📄 [servicios.html](./servicios.html)
**Descripción**: Catálogo completo de productos y servicios de la pastelería.

**Características técnicas:**
- Estructura semántica con `<article>` para cada categoría de producto
- Sistema de grid CSS para layout que es responsivo
- Precios especificados segun el producto  `.price`
- IDs anclas para navegación interna (`#tortas`, `#panes`, `#facturas`, etc.) 
- el boton para redirigir al formulario de contacto por pedidos personalizados
- Animaciones de aparición con `fade-in`

**Secciones principales:**
- Tortas 
- Pan artesanal
- Facturas y medialunas
- Chocolates finos
- catering
- Productos especiales que estan disponibles segun las festividades u ocaciones especiales

---

### 📄 [equipo.html](./equipo.html)
**Descripción**: Presentación del equipo de trabajo de Dulce Miga.

**Características técnicas:**
- Grid de tarjetas para miembros del equipo
- Estructura semántica con `<article>` para cada miembro
- Imágenes optimizadas con `loading="lazy"`
- Sección de valores corporativos ( tradición calidad innovacion y pasion) 
- Diseño responsive con flexbox

---

### 📄 [contacto.html](./contacto.html)
**Descripción**: Página de contacto con formulario funcional y ubicación.

**Características técnicas:**
- Formulario con validación HTML
- campos: nombre, email, teléfono, asunto, mensaje
- Selector de asunto con opciones específicas (consulta general, pedido especial, catering para eventos, reclamo o sugerencia, otros) 
- Integración de Google Maps
- Información de contacto estructurada simple
- Iconos de redes sociales optimizados que llevan a facebook instagram y whatsapp

---

### 📄 [galeria.html](./galeria.html) 
**Descripción**: Galería visual de productos destacados ( bonus del tp ) 

**Características técnicas:**
- Grid de imágenes
- Efectos hover con overlays con la info 
- Lightbox modal 
- Imágenes con lazy loading
- Filtros activos con clases

---
### HTML5 Semántico
```html
<header>, <nav>, <main>, <section>, <article>, <aside>, <footer>
