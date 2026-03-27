# 🚀 Portfolio Personal — Alex Rivera

Este es un proyecto de una **Landing Page** moderna y minimalista con estética **Dark Neón**, desarrollada como práctica de fundamentos de desarrollo web. El objetivo fue transformar una estructura HTML simple en una interfaz de alto impacto visual utilizando CSS avanzado.

## 🛠️ Conceptos Aplicados

En este proyecto se pusieron en práctica los pilares fundamentales del desarrollo Front-End:

### 1. Estructura Semántica (HTML5)
Se utilizaron etiquetas semánticas como `<header>`, `<main>`, `<section>` y `<footer>`. Esto no solo ayuda a la organización del código, sino que mejora la **accesibilidad** y el **SEO** (optimización para buscadores).

### 2. Box Model (Modelo de Caja)
Es el corazón del diseño web. Cada elemento se trabajó entendiendo la relación entre:
* **Content**: El texto o imagen.
* **Padding**: El espacio interno.
* **Border**: La línea que delimita la caja.
* **Margin**: El espacio exterior entre elementos.

### 3. CSS Custom Properties (Variables)
Utilizamos `:root` para definir una paleta de colores y tipografías globales. Esto permite que el diseño sea **mantenible**: si quiero cambiar el color neón, solo cambio una línea de código y se actualiza en todo el sitio.

### 4. Flexbox & Grid
* **Flexbox**: Utilizado para la alineación del Header y la sección Hero (alineación en una dimensión).
* **CSS Grid**: Utilizado en la sección de Habilidades para crear una cuadrícula responsiva que se adapta automáticamente al ancho de la pantalla.

### 5. Glassmorphism & Efectos Visuales
* **Backdrop-filter**: Para crear el efecto de "cristal esmerilado" en la barra de navegación.
* **Keyframes**: Para las animaciones de entrada (`fadeInUp`) y el efecto de levitación de la imagen.
* **Transitions**: Para que los cambios de color y escala al pasar el mouse (hover) sean suaves.

### 6. Responsive Design
El sitio es totalmente adaptable. Se utilizaron **Media Queries** y la función `clamp()` para que los textos y contenedores se reajusten perfectamente en dispositivos móviles.
