# Generador de Firmas — Notaría Pública 39

Generador de firmas de correo (estilizada y reply/móvil) para la Notaría Pública 39 · González & Valdés.

## Archivos
- `generador_firmas.html` — el generador (HTML autónomo). Ábrelo en el navegador o sírvelo con Caddy.
- `Caddyfile` — configuración para servirlo con Caddy.
- `docs/index.html` — copia del generador para publicar en GitHub Pages.
- `docs/.nojekyll` — evita que GitHub procese el sitio con Jekyll (el generador es HTML estático).
- `README.md` — este archivo.

## GitHub Pages
El sitio se publica desde la carpeta `docs/` (configuración de Pages: fuente `main` → `/docs`).
Como el generador es HTML estático, `docs/.nojekyll` hace que GitHub lo sirva directamente sin Jekyll.

Para actualizar el sitio, reemplaza `docs/index.html` (y la copia `generador_firmas.html` si usas Caddy)
con la versión nueva y sube los cambios a la rama `main`.

URL del sitio: https://soul23-mx.github.io/signature-generator/

## Sirve con Caddy (local)
1. Instala Caddy: https://caddyserver.com/docs/install
2. Desde esta carpeta ejecuta:
   ```
   caddy run
   ```
3. Abre en el navegador: http://localhost:2015/ (sirve `generador_firmas.html`).

## Sin Caddy
Solo abre `generador_firmas.html` con doble clic en cualquier navegador moderno.
