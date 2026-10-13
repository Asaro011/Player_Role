# PlayerRole

Planilla de personaje de rol para el teléfono. Funciona sin internet y guarda los datos de cada persona en su propio dispositivo.

## Subirla a GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `playerrole`).
2. Sube **todo el contenido de esta carpeta** a la raíz del repositorio (`index.html` debe quedar en la raíz).
3. Ve a **Settings → Pages**. En *Build and deployment* elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
4. Espera uno o dos minutos. La página quedará en `https://TU-USUARIO.github.io/playerrole/`.

## Instalarla en el teléfono

- **Android (Chrome):** menú ⋮ → *Instalar app* o *Añadir a pantalla de inicio*.
- **iPhone/iPad (Safari):** Compartir → *Añadir a pantalla de inicio*.

## Datos

Los cambios se guardan en el navegador de cada persona (localStorage e IndexedDB), no en GitHub. Para no perderlos, usar **💾 Guardar copia** de vez en cuando y **📂 Cargar copia** para restaurar o pasar la planilla a otro dispositivo.

## Actualizar la página

Si cambias `index.html`, sube también el cambio y, para forzar que los teléfonos descarguen la versión nueva, cambia el número de `CACHE` en `sw.js` (por ejemplo `playerrole-v2`).

## Contenido

- `index.html`: la aplicación completa
- `manifest.webmanifest`: datos de instalación como app
- `sw.js`: funcionamiento sin internet
- `icons/`: iconos
- `.nojekyll`: evita el procesamiento de Jekyll de GitHub Pages
