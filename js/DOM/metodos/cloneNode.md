recibe `true - false`, por defecto es false lo que significa que todos los atributos del nodo serán clonados, excepto el contenido y sus hijos, con true es completamente lo contrario
```js
var paraElement = document.getElementById('para');
var paraElementClone = paraElement.cloneNode(true);
```