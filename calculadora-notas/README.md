# Calculadora de notas · 1er semestre

Calculadora para saber cuánto llevo corregido en cada asignatura, mi media y qué necesito en lo que queda para aprobar.

## Cómo se guardan los datos

- Todo lo que marcas o escribes se guarda **al momento** en el navegador (`localStorage`). Al volver a abrir la página, sigue ahí.
- Los datos se guardan **por navegador y por dirección web**: la versión de GitHub Pages no ve lo que guardaste en el archivo del Escritorio, ni en otro móvil u ordenador.
- Para pasar los datos de un sitio a otro: **Exportar copia** (descarga un `.json`) y luego **Importar copia** en el otro sitio.

## Publicarla con GitHub Pages

1. Crea un repositorio nuevo en GitHub y sube `index.html` y este `README.md` (botón *Add file → Upload files*).
2. Ve a *Settings → Pages*.
3. En *Source* elige *Deploy from a branch*, rama `main`, carpeta `/ (root)` y pulsa *Save*.
4. En un par de minutos estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
