# Corporación Selva Futuro — Sitio web (prototipo)

Prototipo visual del sitio web oficial de la **Corporación Selva Futuro (CORPOSELFUTURO)**,
una entidad sin ánimo de lucro del Guaviare (El Retorno, Colombia) dedicada a la conservación
ambiental, el fortalecimiento comunitario y el desarrollo sostenible, con especial compromiso
con la **juventud rural**.

> *« Por la vida en la selva, en comunidad y territorio. »*

## 👀 Ver la página

Este prototipo es un único archivo `index.html` (usa Tailwind y Google Fonts por CDN,
por lo que requiere conexión a internet).

- **Localmente:** descarga el repo y abre `index.html` en tu navegador, o desde la carpeta
  ejecuta `python3 -m http.server 8000` y abre http://localhost:8000
- **En vivo (GitHub Pages):** se puede activar en *Settings → Pages* del repositorio.

## 🖼️ Cambiar el logo

Coloca tus archivos en `assets/logo/` con estos nombres exactos:

| Archivo | Uso |
|---------|-----|
| `assets/logo/selva-futuro.png`        | Logo del header (fondo transparente) |
| `assets/logo/selva-futuro-blanco.png` | Logo del footer (versión clara) |
| `assets/logo/favicon.png`             | Ícono de la pestaña (512×512) |

## 📷 Cambiar las fotos

Coloca las fotos reales del Guaviare en `assets/img/` con estos nombres exactos.
En cuanto exista el archivo, aparece automáticamente en su lugar (si no, se muestra una etiqueta marcadora).

| Archivo | Sección | Formato ideal |
|---------|---------|---------------|
| `hero-guaviare.jpg`          | Fondo del hero (portada) | Apaisada 1920×1080+ |
| `jovenes-rurales.jpg`        | Jóvenes rurales | 4:3 |
| `territorio-bosques.jpg`     | Galería territorio | Vertical 3:4 |
| `territorio-rios.jpg`        | Galería territorio | Vertical 3:4 |
| `territorio-fauna.jpg`       | Galería territorio | Vertical 3:4 |
| `territorio-comunidades.jpg` | Galería territorio | Vertical 3:4 |
| `productivo-1.jpg`           | Ficha productiva | 16:9 |
| `productivo-2.jpg`           | Ficha productiva | 16:9 |
| `productivo-3.jpg`           | Ficha productiva | 16:9 |

> **Cómo cambiarlas en GitHub (sin instalar nada):** entra a la carpeta `assets/img/`,
> pulsa *Add file → Upload files*, y sube la imagen con el nombre exacto de la tabla.
> Si subes una con el mismo nombre, la reemplaza.

## 🛈 Estado del prototipo

- Interacciones reales: navegación, menú móvil, animaciones al hacer scroll.
- Solo visual por ahora (se activa en fases posteriores): selector de idiomas, donaciones, envío del formulario.
- Contacto real: coselfuturo26@gmail.com · 317 798 9684 · El Retorno, Guaviare.
