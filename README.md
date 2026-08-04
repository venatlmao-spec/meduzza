# MEDUZZA

Sitio web de **Meduzza** — producción de eventos, sonido profesional, iluminación,
pantallas LED, efectos especiales y tarimas en Bogotá.

🌐 **meduzza.store**

## Estructura

```
index.html              La página completa (HTML + CSS + JS en un solo archivo)
CNAME                   Dominio personalizado para GitHub Pages
assets/
  logo.png              Logo oficial de Meduzza
  event-01..10.jpg      Fotografías de eventos reales
  videos/
    evento-01.mp4       "La rumba encendida"
    evento-02.mp4       "Luces y láser en acción"
    evento-03.mp4       "El montaje detrás del show"
```

## Editar el sitio

Todo el sitio vive en `index.html`. Los estilos están dentro de la etiqueta
`<style>` y el JavaScript al final, dentro de `<script>` — no hay que compilar nada.

Para ver los cambios: abre `index.html` en el navegador.

### Cambiar los combos y precios

Busca la sección `<!-- ================= PAQUETES ================= -->`.
Cada combo es un bloque `<div class="ticket">`.

### Cambiar los videos

Reemplaza los archivos en `assets/videos/` conservando los mismos nombres.

### Datos de contacto

El WhatsApp y el correo aparecen en la sección de contacto y en el pie de página.
Busca `wa.me` y `contacto@meduzza.co` para actualizarlos.

## Publicar cambios

```bash
git add .
git commit -m "Descripción del cambio"
git push
```

El sitio se actualiza solo, un par de minutos después del push.
