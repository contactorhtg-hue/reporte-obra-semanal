# Reporte de Obra Semanal v2.2 — Offline

PWA móvil para captura de reportes diarios de construcción y generación de libro Excel `.xlsx` sin depender de Internet después de la instalación.

## Características
- Lunes a domingo.
- Hasta 6 fotografías por día (42 por semana).
- Cámara y galería.
- Resumen individual por fotografía.
- Almacenamiento local con IndexedDB.
- Respaldo/restauración JSON.
- Generación de Excel `.xlsx` local, con 8 hojas y fotografías incrustadas.
- Service Worker para funcionamiento offline.

## Publicación
Publicar la carpeta en un hosting HTTPS. No requiere CDN ni librerías externas.

## Importante
La primera visita/instalación necesita conexión para descargar la aplicación. Una vez cargados los recursos, la captura y generación del Excel funcionan sin Internet.
