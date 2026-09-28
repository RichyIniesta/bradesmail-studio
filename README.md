# BradesMail Studio

Aplicación web para crear correos HTML institucionales de Bradesco México.

## Estructura

- `index.html` — dashboard de la aplicación.
- `correos.html` — editor visual.
- `plantilla.html` — plantilla HTML email-safe base.
- `plantillas.html` — biblioteca inicial de plantillas.
- `assets/css/app.css` — estilos compartidos de la aplicación.
- `assets/js/app.js` — estado ligero del workspace en el navegador.

## Arquitectura actual

La aplicación es estática y funciona sin backend: el editor genera el HTML en el navegador y la plantilla base permanece separada del contenido modular.

La siguiente evolución puede separar el editor en componentes, agregar proyectos persistentes y conectar un backend si se requiere almacenamiento multiusuario.
