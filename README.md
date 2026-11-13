# Fifth Heir Studio

Aplicación de diseño de interiores para iPad (horizontal) y ordenador: plano 2D y vista 3D sincronizados, mobiliario con medidas reales, comprobación de espacio, materiales e iluminación.

- **App publicada:** https://elpanaedgar.github.io/fifth-heir-studio/
- **Instalar en iPad:** abrir en Safari → Compartir → «Añadir a pantalla de inicio».
- **Actualizaciones:** cada cambio subido a `main` se publica solo. La app compara su versión con `version.json` y muestra «Actualizar».

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La aplicación completa (HTML + CSS + JS en un solo archivo). Three.js se carga desde cdn.jsdelivr.net |
| `version.json` | Versión publicada. **Debe coincidir con `APP_VERSION` de `index.html`** en cada actualización |
| `manifest.webmanifest`, `icon-*.png` | Instalación en pantalla de inicio |
| `.nojekyll` | Evita que GitHub Pages procese los archivos |

## Datos

Los proyectos se guardan en el dispositivo (almacenamiento del navegador). Copia de seguridad: Exportar → «Proyecto editable (.json)» (formato `fifthheir.project` v1). Importar: Proyectos → Importar.

## Publicar una versión nueva

1. Cambiar `APP_VERSION` en `index.html`.
2. Poner el mismo número en `version.json`.
3. Commit y push a `main`.
