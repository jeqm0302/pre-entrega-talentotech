# Pixel Arena — Sitio web de tienda gamer

Sitio web multipágina de una tienda ficticia de periféricos y accesorios gamer, desarrollado con HTML y CSS como trabajo del curso de Front-End de Talento Tech.

**Sitio publicado:** https://pixel-arena-jesus.netlify.app

## Páginas

| Página | Archivo | Contenido |
|--------|---------|-----------|
| Inicio | `index.html` | Presentación de la tienda y accesos rápidos |
| Productos | `productos.html` | Cards de productos con imagen, descripción y precio |
| Reseñas | `resenas.html` | Opiniones de clientes |
| Próximamente | `proximamente.html` | Video de YouTube embebido |
| Contacto | `contacto.html` | Formulario de contacto |

Todas las páginas están enlazadas entre sí mediante enlaces relativos y comparten el mismo menú y la misma hoja de estilos.

## Tecnologías

- HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3 en un archivo externo: Flexbox, Grid, Media Queries y degradados
- Google Fonts (Orbitron y Roboto)
- Formspree para el envío del formulario
- Netlify para el hosting

## Estructura del proyecto

```
pre-entrega-talentotech/
├── index.html
├── productos.html
├── resenas.html
├── proximamente.html
├── contacto.html
├── styles.css
└── img/
    ├── producto1.png
    ├── producto2.png
    └── producto3.png
```

## Diseño responsivo

En pantallas de hasta 768 px el menú pasa a columna, las cards y reseñas se muestran de a una por fila y el formulario ocupa todo el ancho.

## Accesibilidad

- Menú con `aria-label` y página actual marcada con `aria-current`.
- Imágenes con texto alternativo y dimensiones declaradas.
- Formulario con `label` asociado a cada campo.

## Cómo verlo localmente

1. Clonar o descargar el repositorio.
2. Abrir la carpeta en Visual Studio Code.
3. Abrir `index.html` con la extensión Live Server.

## Autor

Jesús Enrique Quijada Martínez