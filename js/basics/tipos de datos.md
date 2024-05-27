# Primitivos
existen siete tipos de datos primitivos
- `undefined`: ausencia de un valor
- `null`
- `numbers`
- `strings`
- `boolean`
- `Symbols`
- `BigInt`
## wrapper types
- autoboxing
excluyendo a `null` y `undefined`
### Eliminar de la memoria la variable temporal, estableciéndola en `undefined`
```js
const str = 'Autoboxing';
let strBoxed = new String(str);
console.log(strBoxed.length);
strBoxed = undefined;
```
## Object data types
- Arrays
- Las funciones son objetos también
## other
- `object`: compuesto por primitivos, conocido también como `reference type`
- `typeof` retorna un string `undefined` cuando no existe una variable, o cuando la variable no esta inicializada
-<mark style="background: #FF5582A6;"> cuando se use typeof en null retorna un object y esto es un bug, no usar</mark>
```js
const x = 10
typeof x !== 'undefined' //true
```