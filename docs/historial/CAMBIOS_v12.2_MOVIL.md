# v12.2 · Corrección móvil y preparación para GitHub

- **Corregido:** en pantallas pequeñas (≤ 760 px) la sección «¿Sabías que?» se ensanchaba ~570 px más que la pantalla y el botón ☰ quedaba fuera de vista. Causa: la línea de tiempo de la reforma (`min-width:900px`) ensanchaba la cuadrícula `.sabias-page`. Ahora la cuadrícula usa `minmax(0,1fr)` y la línea de tiempo se desliza dentro de su marco. (Última regla de `styles.css`.)
- Archivos de historial (README/AUDITORIA/CAMBIOS/Dictamen) movidos a `docs/historial/`.
- Añadidos `.nojekyll`, `.gitignore` y un `README.md` raíz.
