---
date-to-study: 2025-10-29
tags:
  - summary
---
---

[tipos_de_datos](https://www.youtube.com/watch?v=KH4MmQsCDuw&list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-&index=5)

## scalar 
bool: 1true, 0false, `ìs_bool()`
int:
`PHP_INT_` global
- [entero](https://www.youtube.com/watch?v=rjEP_GUdg6o&list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-&index=7)
- cuando un entero hace overflow, el tipo de dato se convierte en float
- `ìs_int()`
- 2_000_000

float
- `PHP_FLOAT_` global
- `floor()`redondea hacia abajo, `ceil()`redondea hacia arriba 
- nunca comparar numeros de tipo float [leer](https://floating-point-gui.de/)
- si un float tiene overflow, devuelve `INF`, metodo `is_infinite()`
- siempre que un valor string se intente convertir a entero o flotante, el resultado de la conversion sera 0

string

## compound
array: pueden contener diferentes datatypes, [deep_lecture](https://www.youtube.com/watch?v=C8ZFLq24g_A&list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-&index=11)
```php
//la funcion `print_r()` implrime el arreglo
echo "<pre>";
print_r($array);
echo "</pre>";
```
object
callable
iterable
## special
resource
null: si una variable ha sido declarada pero no ha sido asignada es null, `unset()` destruye la variable
```php
$typedvar = null
(int)$typedvar
```

https://www.php.net/manual/es/language.types.intro.php


```php
var_dump($variable)//inspecciona el tipo y valor de una variable
$uint32 = $valor & 0xFFFFFFFF; // Resultado: 4294967295
```

*ES PREFERIBLE EVITAR LA COERCION(conversion automatica de un tipo a otro)

---
- [ ] summary  📅 2025-10-29
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 