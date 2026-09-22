# VIH · Atención integral

Aplicación docente en español para recorrer resúmenes propios de siete perfiles de atención al VIH y abrir las páginas de la fuente original.

## Alcance

- La fuente es *Recomendaciones de atención para un paciente con infección por VIH según perfil*, National Policy / SI-Health, edición 2022, material NP-ES-HVU-MONO-230003 (v1), enero de 2023.
- Esta app no diagnostica, clasifica pacientes, puntúa, prescribe ni reemplaza guías actualizadas o valoración clínica.
- No contiene el PDF, datos de pacientes, marcas de tratamiento, servicios de analítica ni fuentes externas de tipografía.
- Búsqueda, filtro y favoritos funcionan en el dispositivo; el service worker guarda los archivos propios. La guía enlazada requiere Internet.

## Desarrollo y despliegue

Sitio estático. `index.html`, `manifest.webmanifest`, `sw.js` e iconos no requieren dependencias. Puede servirse desde GitHub Pages manteniendo la ruta base del repositorio; el registro de service worker es relativo al alcance desplegado.
