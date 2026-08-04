# Generador de Firmas — Notaría Pública 39

Generador de firmmas de correo (estilizada y reply/móvil) para la Notaría Pública 39 · González & Valdés.

## Archivos
- `generador_firmas.html` — el generador (abrir en el navegador o servirlo con Caddy).
- `Caddyfile` — configuración para servirlo con Caddy.

## Sirve con Caddy
1. Instala Caddy: https://caddyserver.com/docs/install
2. Desde esta carpeta ejecuta:
   ```
   caddy run
   ```
3. Abre en el navegador:
   ```
   http://localhost:2015/
   ```
   (Caddy sirve `generador_firmas.html` como página de inicio).

## Sin Caddy
Solo abre `generador_firmas.html` con doble clic en cualquier navegador moderno.
