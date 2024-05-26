`node.removeChild(childNode)`
- pese a que el elemento sea eliminado del DOM tree, es posible acceder a este si se almacena en una variable
## Trick 
```js
var paraElement = document.getElementById('para');
paraElement.parentNode.removeChild(paraElement);
```