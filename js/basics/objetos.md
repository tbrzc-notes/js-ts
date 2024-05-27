El objeto mas simple es conocido como `object literal` o `plain object`
```js
{key1: value1, key2: value2, ..., keyN: valueN}
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