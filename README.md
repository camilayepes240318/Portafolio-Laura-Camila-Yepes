# Portafolio · Laura Camila Yepes Gutiérrez

Sitio web estático del portafolio profesional de Laura Camila Yepes Gutiérrez: marketing y comunicaciones, estrategia digital, contenidos, pauta y creación de marca.

## Contenido

- `index.html`: el sitio completo (estilos y código incluidos).
- `hoja-de-vida-laura-camila-yepes.pdf`: hoja de vida descargable desde el sitio.
- `assets/`: fotos, imágenes y videos optimizados para web.
  - `ifcaya/`, `cneutral/`, `nami/`, `riobita/`: material de cada proyecto.
- `.nojekyll`: indica a GitHub Pages que publique los archivos tal cual.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `portafolio`.
2. Sube todo el contenido de esta carpeta a la raíz del repositorio (no la carpeta, sino lo que hay dentro).
3. En el repositorio, ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/portafolio/`.

## Editar

- Los textos se cambian directamente en `index.html`.
- Los datos pendientes están marcados en el código con `data-pendiente`; búscalos para completarlos.
- Para cambiar una imagen, reemplaza el archivo en `assets/` con el mismo nombre.

## Antes de compartir

Cuando tengas la dirección final, agrega en el `<head>` de `index.html`:

```html
<link rel="canonical" href="https://TU-USUARIO.github.io/portafolio/">
<meta property="og:image" content="https://TU-USUARIO.github.io/portafolio/assets/laura-camila-yepes.webp">
```
