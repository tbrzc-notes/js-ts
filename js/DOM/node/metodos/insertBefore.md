recibe dos parámetros `node.insertBefore(newNode, childNode)`
```js
mainElement.insertBefore(h3Element, mainElement.childNodes[3]);
mainElement.insertBefore(h3Element, null);//si le pasamos un null, funcionara como un appendChild y se agregara el nodo al final
```