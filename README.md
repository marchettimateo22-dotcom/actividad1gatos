# README - Proyecto Web: "Mis Gatos"

**Autor:** Mateo Marchetti  
**Materia / Proyecto:** Diseño y Desarrollo Web

## Descripción del Proyecto

**Mis Gatos** es una galería visual dedicada a Pomelo, Donato y Duque.

El objetivo del sitio es presentar a cada uno de mis gatos a través de imágenes e información sobre sus características, personalidad y gustos.

La página busca mostrar las diferencias entre los tres gatos y compartir algunas fotografías de su día a día.

El sitio está compuesto por 4 páginas interconectadas:

1. **Inicio (`index.html`):** Presentación general de la galería y de Pomelo, Donato y Duque.
2. **Pomelo (`pomelo.html`):** Página dedicada a Pomelo, con sus datos básicos, personalidad, gustos y fotografías.
3. **Donato (`donato.html`):** Página dedicada a Donato, con información sobre sus características, personalidad, gustos e imágenes.
4. **Duque (`duque.html`):** Página dedicada a Duque, donde se presentan sus datos básicos, personalidad, gustos y fotografías.

Todas las páginas cuentan con una barra de navegación que permite acceder a la página principal y a cada uno de los gatos.


## Objetivo de la Galería

El objetivo de la galería es presentar de una manera visual, simple y organizada a mis tres gatos.

Cada uno tiene características, gustos y personalidades diferentes, por lo que cada página permite conocerlos individualmente mediante fotografías y textos descriptivos.


## Contenidos Incluidos

El sitio incluye:

- Página principal de presentación.
- Página individual de Pomelo.
- Página individual de Donato.
- Página individual de Duque.
- Fotografías de cada gato.
- Datos básicos.
- Descripción de sus personalidades.
- Información sobre sus gustos.
- Barra de navegación.
- Enlaces internos dentro de las páginas.
- Enlace externo relacionado con el tema de los gatos.


# Decisiones de Diseño

## 1. Paleta de Colores Elegida

Para el sitio se eligió una paleta de colores cálidos formada principalmente por tonos crema, beige y marrón.

- **Crema claro (`rgb(253, 252, 233)`):**
  utilizado como fondo general del `body`.

- **Beige (`rgb(247, 242, 238)`):**
  utilizado como fondo del contenido principal (`main`).

- **Rosa beige (`rgb(214, 196, 190)`):**
  utilizado como fondo del encabezado (`header`).

- **Beige rosado (`rgb(220, 205, 196)`):**
  utilizado como fondo de la barra de navegación (`.barramenu`) y de la caja de información (`.caja-info`).

- **Marrón (`rgb(132, 88, 77)`):**
  utilizado en enlaces, botones de navegación y botones de regreso.

- **Terracota (`rgb(184, 124, 103)`):**
  utilizado en los estados `hover` de enlaces y botones.

- **Marrón oscuro (`rgb(87, 60, 32)`):**
  utilizado como color principal del texto.

- **Marrón grisáceo (`rgb(116, 101, 96)`):**
  utilizado como fondo del pie de página.

- **Blanco (`rgb(255, 255, 255)`):**
  utilizado principalmente para los textos de botones y del pie de página.

## 2. Tipografía y Estilos de Texto

- **Familia tipográfica:** Gill Sans, Gill Sans MT, Calibri, Trebuchet MS y sans-serif.

- **Texto general (`body`):**
  tamaño de `22px` y color marrón oscuro.

- **Elementos de lista (`li`):**
  tamaño de `35px` y peso en negrita.

- **Menú de secciones (`.menu-secciones li`):**
  tamaño de `24px`.

- **Botones de navegación (`.botonmenu`):**
  tamaño de `18px`, texto blanco y sin subrayado.

- **Botón para volver (`.botonvolver`):**
  tamaño de `18px`, texto blanco y fondo marrón.

- **Pie de página (`footer`):**
  tamaño de `25px`, texto blanco y alineación centrada.


## 3. Imágenes

Las imágenes principales utilizan la clase `.foto`.

Se definió:

- Ancho de `45%`.
- Ancho máximo de `450px`.
- Altura automática para mantener las proporciones.
- Bordes redondeados de `10px`.
- Centrado horizontal mediante `display: block` y `margin: 0 auto`.

En la página principal también se utilizan imágenes con la clase `.foto-index`, con un ancho de `30%` y un máximo de `450px`.


## 4. Organización Visual con Flexbox

En la página principal se utiliza **Flexbox** mediante la clase `.fotos-index`.

Se aplicaron las siguientes propiedades:

- `display: flex`
- `justify-content: center`
- `gap: 20px`

Esto permite mostrar las imágenes una al lado de la otra, centradas y con separación entre ellas.


## 5. Diseño Responsive

El sitio incorpora una **media query para pantallas de hasta 768px**.
