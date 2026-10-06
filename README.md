# Roldán Lauzán Eiras — sitio web

Maqueta inicial de un portafolio artístico estático.

## Estructura

- `index.html` — página completa y responsive.
- `pinturas.json` — listado de las 15 obras y sus rutas.
- `cloudcannon.config.json` — configuración inicial para CloudCannon.
- `images/` — imágenes de las obras.
- `logos/` — logotipos locales, incluido Instagram.

## Galería

La cuadrícula usa una proporción visual fija de 4:5 para que las miniaturas tengan el mismo formato aunque los originales tengan diferentes proporciones. La imagen ampliada se muestra completa, sin deformarla.

Al tocar/clicar una obra se abre un visor. Se puede avanzar y retroceder con las flechas, con el teclado o deslizando mentalmente la navegación en móvil mediante los botones laterales. Escape cierra el visor.

## Sustituir las obras

Reemplaza las imágenes de `images/` y actualiza `pinturas.json`. El campo `url` puede apuntar a archivos locales o a URLs externas/CDN.

## GitHub Pages

Para una publicación inicial gratuita, sube este repositorio a GitHub y activa GitHub Pages desde **Settings → Pages**. Para un sitio personal, el repositorio puede llamarse `USUARIO.github.io`; GitHub Pages lo publicará en `https://USUARIO.github.io/`.

## CloudCannon

CloudCannon puede conectarse al repositorio Git y trabajar con el contenido del sitio. `pinturas.json` está separado de `index.html` para que la galería pueda mantenerse sin tocar el código.

Nota: la configuración de CloudCannon es deliberadamente conservadora en esta primera versión. Cuando se conozca exactamente el flujo de edición que se usará para subir/eliminar fotografías, se puede añadir un esquema de edición más cómodo para el artista.
