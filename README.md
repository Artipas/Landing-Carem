# CAREM · Landing informativa

Web estática de CAREM, la marca de coberturas de chocolate belga de ARTIPAS.
Las compras se hacen en https://www.artipas.com/carem

## Publicar con GitHub Pages
1. Subir todo el contenido de esta carpeta a la raíz del repositorio.
2. Settings → Pages → Deploy from a branch → rama `main`, carpeta `/ (root)`.
3. Dominio propio: Settings → Pages → Custom domain, y marcar «Enforce HTTPS».
   En el proveedor DNS, crear un registro CNAME que apunte el subdominio a `<usuario>.github.io`.

## Pendiente al conectar el dominio
En `index.html`, sustituir `img/og-carem.jpg` por la dirección completa
(p. ej. `https://carem.artipas.com/img/og-carem.jpg`) en `og:image` y `twitter:image`,
para que la vista previa funcione al compartir el enlace.

## Estructura
- `index.html` — la página
- `img/` — imágenes
- `fichas/` — fichas técnicas en PDF
- `favicon.svg`, `favicon.ico`, `favicon-32.png`, `apple-touch-icon.png` — iconos
- `.nojekyll` — indica a GitHub Pages que sirva los archivos tal cual
