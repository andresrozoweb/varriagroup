# Varria Group — home (borrador de dirección visual)

Sitio estático (HTML + CSS + JS sin dependencias de build). Los logos y las imágenes de los casos son de ejemplo.

## Desplegar en Coolify

1. New Resource → Public/Private Repository → `andresrozoweb/varriagroup`, rama `main`.
2. Build Pack: **Dockerfile** (usa el `Dockerfile` de la raíz, nginx en el puerto 80).
   - Alternativa: Build Pack **Static**, Base Directory `/`, sin comando de build.
3. Ports Exposes: `80`. Asigna el dominio y activa HTTPS.

## Pendiente antes de producción

- Formulario de cotización: pega la URL de tu endpoint (Formspree, etc.) en `FORM_ENDPOINT` al inicio del script de `index.html`. Vacío = solo simula el envío.
- Reemplazar imágenes de `assets/` por fotos reales, y los logos de ejemplo por los de los clientes.
- Quitar la nota "Borrador de dirección visual…" del pie.
- Confirmar el enlace de Instagram y las cifras de los casos.
