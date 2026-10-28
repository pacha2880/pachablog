# Pachablog

Blog personal de pacha2880: <https://pacha2880.github.io/pachablog/>

Hecho con Jekyll y publicado con GitHub Pages. No hay que instalar nada.

## Escribir una entrada

1. Crea un archivo en la carpeta `_posts/` con el nombre `AAAA-MM-DD-titulo-de-la-entrada.md`, por ejemplo `2026-11-03-mi-primer-viaje.md`. Desde la web de GitHub: entra a `_posts`, pulsa **Add file → Create new file**.
2. Empieza el archivo con este encabezado:

   ```markdown
   ---
   title: Mi primer viaje
   tags: [viajes, personal]
   ---

   Aquí va el texto, en Markdown.
   ```

3. Haz commit. En uno o dos minutos la entrada aparece en el blog.

Para Google conviene agregar `description: Una frase que resuma la entrada` al encabezado (sale bajo el título en los resultados) y usar palabras clave en el título y en el nombre del archivo, que forma la URL.

Las etiquetas son opcionales. La fecha sale del nombre del archivo; si una entrada no aparece, revisa que la fecha no sea del futuro.

La entrada `_posts/2026-10-22-guia-de-formato.md` muestra todo el formato disponible (títulos, listas, código, tablas, imágenes).

## Imágenes

Súbelas a `assets/img/` y úsalas así: `![descripción](/pachablog/assets/img/foto.jpg)`.

Al compartir un enlace en un chat se muestra `assets/img/logo.jpg`. Para que una entrada muestre otra imagen, agrega `image: /assets/img/foto.jpg` a su encabezado.

## Visitas

Las cuenta [GoatCounter](https://pacha2880.goatcounter.com). El código está en `goatcounter` dentro de `_config.yml`; bórralo para quitar los contadores. Un contador sin datos no se muestra.

## Cambiar textos

- Título, subtítulo y autor: `_config.yml`
- Página "Sobre mí": `sobre-mi.md`
- Colores y tipografía: `assets/css/style.css` (variables al inicio)
