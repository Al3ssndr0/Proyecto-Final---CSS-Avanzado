# Proyecto-Final CSS-Avanzado
Solución tecnológica Web mediante FRONTEND para la definición, análisis, diseño, implementación y pruebas de los procesos de una entidad que brinda servicio de Belleza y Relajación: Afeitado y Depilación, Aromaterapia, Cosméticos, Cuidado de la piel, Equipo de Spa y Salón.

Componentes CSS exclusivos:

1. Preprocesadores LESS.
2. Preprocesadores SASS.
3. Framework Bulma CSS.


# 🌿 Lumina Atelier — Sitio Web Corporativo y Catálogo Digital

Sitio web responsivo desarrollado para **Lumina Atelier**, un centro de spa, estética integral y cosmética botánica en Arequipa, Perú.  
Proyecto final del curso **Hojas de Estilo en Cascada Avanzado** (UTP, 2026).

🌐 **Demo en vivo (GitHub Pages):** https://al3ssndr0.github.io/Proyecto-Final---CSS-Avanzado/index.html

---

## 📁 Estructura del Proyecto

El repositorio está organizado por separación de responsabilidades para facilitar el mantenimiento y el trabajo en equipo:

```text
Proyecto-Final---CSS-Avanzado/
├── index.html                  # Portada principal (Hero, servicios, experiencias, Club VIP y últimas entradas)
├── pages/                      # Vistas internas del sitio web (11 páginas)
│   ├── nosotros.html           # Identidad corporativa, misión, visión, equipo y sidebar (Grid 70/30)
│   ├── servicios.html          # Catálogo general de tratamientos y tabla comparativa de tarifas
│   ├── cosmeticos.html         # Catálogo de productos botánicos (Grid automático .grid-catalogo)
│   ├── blog.html               # Diario de bienestar con listado de artículos, buscador y categorías
│   ├── contacto.html           # Formulario de reservas estilizado, datos de atención y mapa embebido
│   ├── clientes.html           # Página de beneficios y formulario de inscripción al Club VIP
│   ├── equipo-spa.html         # Galería de cabinas, instalaciones y aparatología estética
│   ├── promociones.html        # Paquetes de temporada, combos y descuentos vigentes
│   ├── afeitado-depilacion.html# Detalle de servicios de depilación orgánica
│   ├── aromaterapia.html       # Detalle de masajes y rituales con aceites esenciales
│   ├── cuidado-piel.html       # Detalle de tratamientos faciales e hidratación
│   └── blog/                   # Artículos editoriales individuales (3 páginas)
│       ├── rutina-calma-nocturna.html
│       ├── acido-hialuronico-mito-verdad.html
│       └── beneficios-cosmetica-botanica.html
├── css/                        # Hojas de estilo enlazadas en los HTML (no editar compilados manualmente)
│   ├── bulma.min.css           # Framework Bulma CSS en versión local
│   ├── style.css               # Estilos base tradicionales y configuración tipográfica
│   ├── main-scss.css           # CSS compilado automáticamente desde scss/main.scss
│   └── main-less.css           # CSS compilado automáticamente desde less/main.less
├── scss/                       # Código fuente SASS
│   └── main.scss               # Variables de paleta, header fijo, banners, grids y tablas
├── less/                       # Código fuente LESS
│   ├── _mixins.less            # Mixins reutilizables (transiciones, sombras y transformaciones)
│   └── main.less               # Botones (.btn-lumina), tarjetas (.servicio-card) y animaciones
└── assets/
    └── img/                    # Banners, fotografías editoriales, productos e iconografía (.jpg / .png)
