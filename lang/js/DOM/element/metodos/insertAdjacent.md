1. `insertAdjacentElement()`
```js
element.insertAdjacentElement(position, elementNode)
```
3. `insertAdjacentText()`
```js
element.insertAdjacentText(position, text)
```
5. `insertAdjacentHTML()` -> mejor que innerHTML
```js
element.insertAdjacentHTML(position, html)
```

- insertAdjamentHTML al momento de remplazar no recuenta los nodos por lo que es ideal para esta operacion
- usar [[innerHTML]] cuando queramos remplazar el contenido y obtener nodos en forma de string