# TrackNutri — iPhone PWA

## Cómo ponerlo en el iPhone

TrackNutri está preparado como una PWA. Para instalarlo como una app en iPhone, el contenido debe estar servido desde una URL web segura (HTTPS).

1. Sube esta carpeta a un alojamiento estático, por ejemplo GitHub Pages.
2. Abre la URL en **Safari** en el iPhone.
3. Pulsa **Compartir** → **Añadir a Inicio**.
4. Activa **Abrir como app web** si aparece.
5. Pulsa **Añadir**.

La app conserva los datos localmente en el navegador. El análisis con IA necesita Internet y una clave de API configurada dentro de TrackNutri.

## Archivos

- `index.html` — aplicación
- `manifest.webmanifest` — configuración PWA
- `sw.js` — caché/offline de la aplicación
- `icon-180.png`, `icon-192.png`, `icon-512.png` — iconos

Nota: abrir `index.html` directamente desde Archivos funciona para probar la aplicación, pero no permite instalar correctamente el Service Worker/PWA. Para la instalación como app en iPhone, usa HTTPS.
