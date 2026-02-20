# Un Rincón para Desconectar — Estructura del proyecto

Proyecto: pequeño blog / página de viajes con login demo.

Estructura del proyecto:

- `index.html` — landing que redirige a `login.html`.
- `login.html` — página de inicio de sesión (cliente).
- `dashboard.html` — contenido protegido (dashboard) con los destinos.
- `assets/css/style.css` — estilos.
- `js/login.js` — lógica del formulario de login (cliente).
- `js/app.js` — lógica del dashboard (verifica sesión, logout).
- `assets/images/` — carpeta con las imágenes de los destinos.

Notas importantes:

- La contraseña compartida de demo es `Sasia2026` y la autenticación es totalmente cliente-side (no segura). Para pruebas local está bien, pero no uses este enfoque en producción.
- Las imágenes están en `assets/images/` y `dashboard.html` apunta a esa carpeta.

Siguientes pasos recomendados:

- (Opcional) Convertir las imágenes a `.jpg` si lo prefieres.
- (Recomendado) Implementar autenticación en servidor (Node/Express, Firebase, o similar) y almacenar contraseñas de forma segura. para futura referencia

Cómo probar localmente: solo para mi y con quien lo comparta.

1. Abre `index.html` en tu navegador (redirige a `login.html`).
2. Inicia sesión con cualquier `Nombre` y la contraseña `Sasia2026`.
3. Serás redirigido a `dashboard.html`.