# DURMIND Afiliados — sitio informativo

Sitio estático en español con presentación, privacidad y contacto. GitHub Pages publica la raíz de `main`. No requiere paquetes ni compilación y no aloja Flask.

## Archivos públicos
- `index.html`: funciones actuales y estado de la integración futura.
- `privacidad.html`: tratamiento actual de datos y limitaciones.
- `contacto.html`: consultas a través de GitHub Issues, sin publicar datos sensibles.
- `assets/`: CSS e icono propio SVG; sin recursos externos.

La aplicación v1.0 usa plantillas, PNG de Pillow, publicación manual y comisiones manuales. OAuth, publicación por API y métricas de Pinterest están en desarrollo; esta web no afirma que estén disponibles ni aprobadas.

No subir `.env`, bases SQLite, copias de seguridad, contraseñas ni tokens a este repositorio. No utilizar Issues para información sensible. Actualizar la política antes de habilitar nuevas integraciones.

Vista previa local opcional: `python -m http.server 8791 --bind 127.0.0.1` desde esta carpeta.
