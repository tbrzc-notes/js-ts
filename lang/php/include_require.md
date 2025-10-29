---
date-to-study: 2025-10-30
tags:
  - summary
---
---

- es preferible usar `require_once()` sobre include, para importar funciones
- require en caso de fallar retorna false y 1 en caso de ser exitoso, util para importar archivos opcionales

## damnbrother

```php
//_header.php
<header>
    <h1>Mi Sitio Web</h1>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#servicios">Servicios</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</header>

//index.php
ob_start();
include './src/views/area/admin/partials/_header.php';
$nav = ob_get_clean();
echo $nav;
```


https://www.youtube.com/watch?v=pQLO6l5lp-Y&list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-&index=21

---
- [ ] summary  📅 2025-10-30
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 