# Registro Holter

Web móvil y estática para anotar síntomas durante un estudio Holter.

Opciones rápidas: **Agitada**, **Siento el corazón latir**, **Tos** y
**Latidos irregulares**. Cada registro se conserva al cerrar y volver a abrir
la web en el mismo navegador y dispositivo.

Cada evento también registra obligatoriamente si la persona estaba **moviéndose**
o **quieta** en ese momento.

## Publicar en GitHub Pages

1. Creá un repositorio nuevo en GitHub.
2. Subí `index.html` a la raíz del repositorio.
3. Entrá en **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná `main`, carpeta `/ (root)`, y guardá.

Los registros se guardan únicamente en el navegador del dispositivo mediante `localStorage`.
