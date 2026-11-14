# Arcana & Elixires · Coven Bar — Sitio web

Sitio corporativo de 5 páginas en HTML, CSS y JavaScript puro (sin frameworks ni dependencias).

## Estructura
```
index.html        Inicio
nosotros.html     Historia, misión, visión, valores, equipo y cifras
productos.html    Catálogo con filtro por categoría
clientes.html     Testimonios, marcas aliadas y casos de éxito
contacto.html     Formulario, datos de contacto, horarios, mapa y redes
css/styles.css    Estilos (variables de diseño al inicio del archivo)
js/main.js        Menú móvil, animaciones, contadores, filtro y formulario
img/              Fotografías y favicon
robots.txt, sitemap.xml
```

## Cómo verlo
Abre `index.html` en tu navegador, o sube la carpeta completa a cualquier hosting
(Netlify, Vercel, GitHub Pages, cPanel…).

## Formulario de contacto
Por defecto, al enviar se abre el correo del visitante con el mensaje redactado hacia
`hola@covenbar.co`. Para recibir los mensajes automáticamente:
1. Crea un formulario gratis en https://formspree.io
2. Copia tu endpoint (ej. `https://formspree.io/f/abcdwxyz`)
3. Pégalo en `FORM_ENDPOINT` al inicio de `js/main.js`

## Antes de publicar
Reemplaza los datos de ejemplo por los reales:
- Dirección, teléfono/WhatsApp (+57 310 555 0137), correos y horarios (footer de cada página y contacto.html)
- Coordenadas del mapa (iframe en contacto.html)
- Enlaces de redes sociales
- Precios, cifras, testimonios y nombres del equipo
- En `sitemap.xml`, `robots.txt` y la etiqueta `og:image`, usa la URL final de tu dominio

## Personalizar el diseño
Colores, tipografías, radios y sombras están centralizados como variables en la sección
"1. Tokens de diseño" de `css/styles.css`.
