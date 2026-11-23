# HEXORA — Demo interactiva

Prototipo de demostración con datos ficticios. No se conecta al backend ni solicita credenciales reales.

## Publicación en GitHub Pages

Subir **el contenido** de esta carpeta, manteniendo los archivos `.dc.html`, la carpeta `_runtime/`, el archivo `index.html` y **`.nojekyll`** en la raíz del repositorio público. En Settings → Pages → Deploy from a branch, seleccionar `main` y `/ (root)`.

Importante: `.nojekyll` impide que GitHub Pages omita la carpeta `_runtime`. La página principal redirige a `Login.dc.html` y todas las pantallas navegan mediante rutas relativas.

## Ejecución local

Desde esta carpeta iniciar un servidor HTTP local (p. ej. `python -m http.server 8000`) y abrir `http://localhost:8000`. Abrir los `.dc.html` por doble clic no es fiable porque el navegador puede bloquear las lecturas de componentes.
