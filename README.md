# Publicar El Tiempo en GitHub Pages

Estos pasos publican la app como sitio estático y permiten instalarla como PWA.

1. Inicia sesión en GitHub y crea un repositorio nuevo (por ejemplo, `el-tiempo`).
2. Sube a la raíz del repositorio los cinco archivos de la app: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.svg` e `icon-512.svg`.
3. Abre **Settings > Pages** del repositorio.
4. En **Build and deployment**, selecciona **Deploy from a branch**; elige la rama **main** y la carpeta **/ (root)**, y pulsa **Save**.
5. Espera a que GitHub Pages termine de publicar. La dirección será:

   `https://USUARIO.github.io/REPO/`

   Sustituye `USUARIO` por tu nombre de usuario de GitHub y `REPO` por el nombre del repositorio.

La instalación de PWA y el service worker requieren HTTPS; GitHub Pages proporciona HTTPS. Para que el navegador ofrezca «Instalar app», la app debe cumplir sus criterios de instalación y no estar ya instalada.
