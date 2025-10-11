
- los tipos de datos son dinamicos
# Primitivos
existen siete tipos de datos primitivos
- `undefined`: ausencia de un valor con espacio en memoria
- `null`: sin asignacion del espacio de memoria
- `numbers`
	- octal | 0o
	- hexadecimal | 0x
	- binario| 0b1010
	- notacion cientifica | 1.23e4
- `strings`
- `boolean`
- `Symbols`
- `BigInt`

## Numbers
- los numeros en js se dividen basicamente en enteros y decimales
```js
let entero = 42;
let decimal = 3.
```

## wrapper types
- autoboxing
excluyendo a `null` y `undefined`
### Eliminar de la memoria la variable temporal, estableciéndola en `undefined`
- convierte el primitivo automaticamente en su objeto wrapper para permitir el uso de metodos
```js
const str = 'Autoboxing';
let strBoxed = new String(str);
console.log(strBoxed.length);
strBoxed = undefined;
```
- no recomendable
```js
"hola" === new String("hola"); // false
```
## Object data types
- Arrays

- Las funciones son objetos también
```js
function greet() {
    console.log("Hello, World!");
}
greet.language = "English";
console.log(greet.language); // "English"
```
## other
- `object`: compuesto por primitivos, conocido también como `reference type`
- `typeof` retorna un string `undefined` cuando no existe una variable, o cuando la variable no esta inicializada
-<mark style="background: #FF5582A6;"> cuando se use typeof en null retorna un object y esto es un bug, no usar</mark>
- el valor de una variable declarada tiene el valor de `undefined` si no ha sido inicializada
```js
const x = 10
typeof x !== 'undefined' //true
```