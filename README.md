# Portfolio DIWEB · 2.º DAW

Portfolio estático con HTML, CSS y JavaScript, preparado para GitHub Pages.

## Publicar en GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz de un repositorio de GitHub.
2. En el repositorio entra en **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
5. Espera a que aparezca la URL publicada.

## Añadir teoría o actividades

1. Abre `admin.html` desde la URL de GitHub Pages.
2. Escribe un identificador de unidad (por ejemplo `UT01`) y el nombre de la unidad.
3. Elige la categoría, el título y uno o varios archivos.
4. Pulsa **Añadir a la cola** y después **Descargar paquete para GitHub**.
5. Descomprime `portfolio-diweb-actualizacion.zip` en tu copia local del repositorio, combinando carpetas y reemplazando `datos/unidades.json`.
6. Revisa el catálogo, haz commit y push a GitHub. GitHub Pages publicará los cambios.

## Importante

GitHub Pages solo sirve archivos estáticos: no permite que un formulario del navegador escriba directamente en el repositorio ni guarde archivos para todos los visitantes. Por eso, el panel genera un ZIP de actualización que debes subir a GitHub. Los recursos pasan a ser públicos si el repositorio y la web son públicos; no publiques datos personales, entregas privadas ni materiales que no tengas permiso para redistribuir.

El panel usa JSZip desde una CDN para crear el ZIP, por lo que necesita conexión a Internet al exportar.
