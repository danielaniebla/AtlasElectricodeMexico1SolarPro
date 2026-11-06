# SolarPro · Atlas Eléctrico de México

Aplicación web estática (HTML + CSS + JavaScript, sin dependencias ni compilación) para explorar el sistema eléctrico mexicano: recursos energéticos, generación, transmisión, distribución y «¿Sabías que?». Proyecto académico TE1020 · v12.2.

## Publicar en GitHub Pages
1. Crea un repositorio y sube **el contenido de esta carpeta** (`index.html` debe quedar en la raíz).
2. En *Settings → Pages* elige *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Tu sitio quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Probar en local
```bash
python3 -m http.server 8000   # y abre http://localhost:8000
```
(Abrir `index.html` con doble clic también funciona, pero algunos navegadores limitan el video en `file://`.)

## Estructura
- `index.html`, `styles.css`, `script.js`, `sabias.js`, `offline-map.js`
- `datos/` — datos y mapas locales · `assets/` — logotipos y video de portada · `fuentes/` — PDF de respaldo
- `docs/historial/` — auditorías y notas de versiones anteriores

## Notas
- Las tipografías (DM Sans, Manrope) se cargan desde Google Fonts; sin internet se usa Arial.
- Los datos cuentan con fuente y año indicados en la propia página (sección «Fuentes y metodología»).
