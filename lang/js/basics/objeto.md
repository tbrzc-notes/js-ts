## literal
El objeto mas simple es conocido como `object literal` o `plain object`
```js
{key1: value1, key2: value2, ..., keyN: valueN}
```
### optimizacion
```js
//ejemplo practico, siempre hacer esto
function obtenerX(obj) {
  return obj.x;
}

obtenerX({x: 1, y: 2});
obtenerX({x: 2, y: 3});
obtenerX({x: 3, y: 4});
obtenerX({x: 4, y: 5});
obtenerX({x: 5, y: 6});

//multiples objetos diferentes, MALA practica

function obtenerX(obj) {
  return obj.x;
}

obtenerX({x: 1, z: 2});
obtenerX({x: 2, w: 3});
obtenerX({x: 3, e: 4});
obtenerX({x: 4, u: 5});

//en su medida hacer esto
function obtenerX(obj) {
  return obj.x;
}

obtenerX({x: 1, z: undefined, w: undefined, e: undefined, u: undefined, y: 1});
```


dos formas de acceder a estos
```js
url.protocol
url['protocol']
```
y mediante el igual podemos crear un nuevo atributo
```js
url['hash'] = null
```
**un metodo no deja de ser un atributo, con la unica diferencia que tiene como valor una funcion**

```js
var url = {
   protocol: 'https',
   domain: 'www.codeguage.com',
   path: '/',

   // return the full URL, as a string
   getURL: function() {
      return url.protocol + '://' + url.domain + url.path;
   }
};
```