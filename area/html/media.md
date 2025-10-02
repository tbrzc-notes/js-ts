---
date-to-study: 2025-10-02
tags:
  - summary
---
---

## picture, img, source, srcset

```html
<picture>
   <source srcset="some-image.avif" type="image/avif">
   <source srcset="some-image.webp" type="image/webp">
   <img src="some-image.png" alt="imagen cualquiera">
</picture>
```

## Eager, Lazy loading
aplica a stylesheets, scripts, iframes, imgs
eager: el recurso se inicia tan pronto como se encuentra
lazy: cuando entra ima imagen al viewport, para mas control se usa javascript para controlar el lazy-loading
```html
<img loading="lazy" src="./html2.jpg">
```
## Avif o Webp
Avif: 
- máxima compresión sin perder calidad
- No tiene soporte para animaciones

Webp:
- animaciones tipo GIF pero con mejor compresión
- decodificación más rápida

## image maps
- utiles para en figuras incluir enlaces [ver](https://www.codeguage.com/examples/courses/html/image-map-3.html)
```html
<map name="m1">
   <area shape="rect" coords="38, 34, 180, 67" href="/" alt="Home" title="Home">
   <area shape="circle" coords="519, 175, 66" href="/courses/" alt="Explore courses" title="Explore courses">
   <area shape="poly" coords="562, 0, 647, 0, 647, 85" href="/about" alt="About us" title="About us">
</map>
```

## Audio Video
- https://www.codeguage.com/v1/courses/html/media-video
- https://www.codeguage.com/v1/courses/html/media-audio

## Docs

- https://www.codeguage.com/v1/courses/html/images-eager-and-lazy-loading
- https://www.codeguage.com/v1/courses/html/images-the-picture-element
- https://www.codeguage.com/v1/courses/html/images-image-maps
---
- [ ] summary  📅 2025-10-02
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 