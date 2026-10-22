# marcoantl. — Landing personal

Sitio estático preparado para publicar en Vercel o GitHub Pages.

## Archivos

- `index.html`: landing completa; CSS, JavaScript e ilustración principal están integrados en el HTML.
- `vercel.json`: configuración mínima para publicación estática en Vercel.

No requiere Node.js, compilación ni instalación de dependencias.

## Publicar en Vercel

1. Entra a https://vercel.com/ e inicia sesión.
2. Selecciona **Add New → Project**.
3. Importa el repositorio de GitHub que contenga estos archivos, o usa la opción de despliegue por CLI.
4. Si Vercel pregunta por el framework, elige **Other**.
5. Deja **Build Command** vacío y **Output Directory** como `.` (raíz del proyecto).
6. Pulsa **Deploy**.

Si publicas desde GitHub, cada `git push` a la rama conectada puede generar un nuevo despliegue.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `marcoantl-portfolio`.
2. Sube `index.html`, `README.md` y `vercel.json` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages termine el despliegue y abre la URL que te muestre.

## Antes de publicarla

- Revisa la página en móvil real y en escritorio, especialmente el menú flotante y el Hero.
- Comprueba los enlaces a redes sociales, correo y proyectos.
- Si se añade un dominio propio, configúralo en Vercel o GitHub Pages.
- Los datos de métricas ilustrativas, si aparecen en la versión publicada, deben sustituirse por datos reales o identificarse claramente como demostrativos.

## Responsive

La página incluye ajustes para móviles estrechos (320 px), móviles habituales, tablet y escritorio. El movimiento del Hero respeta la preferencia de movimiento reducido del sistema.
