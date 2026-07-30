# Rafael Ortiz Lozano — Sitio web

Sitio estático (HTML + CSS + JS plano, sin build) para Rafael Ortiz
Lozano: contaduría, producción de eventos y sus emprendimientos
gastronómicos MONCH, DANKAI y CINCO97.

## Estructura

```
index.html
trayectoria.html
emprendimientos-gastronomia.html
servicios-profesionales.html
produccion-de-eventos.html
contacto.html
assets/
  css/style.css
  js/main.js
  img/{monch,dankai,cinco97}/
```

## Desarrollo local

No requiere build. Basta con servir la carpeta:

```bash
python3 -m http.server 8080
```

## Despliegue

Sitio estático, sin configuración especial: Vercel/GitHub Pages lo
sirven directamente desde la raíz del repositorio.

## Formulario de contacto

`contacto.html` envía a través de [FormSubmit](https://formsubmit.co/).
El campo `_next` se completa automáticamente por JS con la URL del
dominio real (ver `assets/js/main.js`), así que funciona igual en
cualquier dominio donde se despliegue.
