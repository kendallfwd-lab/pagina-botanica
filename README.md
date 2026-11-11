# VapeKing CR — Frontend

Frontend estático de catálogo para una tienda ficticia. Está construido con HTML5, CSS3 y JavaScript vanilla, sin framework ni backend requerido para desplegarlo.

## Ejecutar localmente

Desde la raíz del repositorio:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Luego abre `http://127.0.0.1:4173/`.

## Desplegar en Vercel

Este repositorio está preparado para Vercel: `index.html` está en la raíz y no necesita comando de build.

1. Importa `kendallfwd-lab/pagina-botanica` en Vercel.
2. Deja **Framework Preset** como `Other`.
3. Deja **Build Command** vacío.
4. Deja **Output Directory** vacío o usa `.`.
5. Pulsa **Deploy**.

## Incluye

- Catálogo de 44 productos de demostración.
- Colecciones Wax y Botánica con filtros propios.
- Búsqueda, filtros, ordenamiento y carrusel de productos.
- Carrito y favoritos persistidos en `localStorage`.
- Diseño responsive, navegación móvil, modal de búsqueda y cierre con `Escape`.
- Validación nativa del formulario de newsletter.
- Age gate informativo para mayores de 18 años.
- Soporte para `prefers-reduced-motion` y foco visible.

## Estructura

```text
index.html
css/
  styles.css
  local-assets.css
js/
  data.js
  cart.js
  favorites.js
  filters.js
  ui.js
  app.js
assets/
  productos/
  catalogo/productos/
    wax-vaporizers/
    botanica/
```

Las imágenes botánicas son maquetas visuales y no representan contenido, potencia, seguridad ni certificaciones reales. Antes de vender productos, reemplaza las imágenes y datos por información verificada.
