# `factory methods` para crear nodos
- [[createElement]]()
- [[document fragment]]
- createTextNode() -> es mejor usar las propiedade`innerHTML` o `textContent`
## obtener elementos
```js
const elm = document.getElementById("#id")//retorna null si no existe
const elm = document.getElementByClassName(".class")//retorna todos los elementos con esa clase
const elm = document.getElementByTagName("div")//puedes buscar desde el elemento raiz o desde un elemento en especifico
const elm = document.getElementByName("")//retorna el elemento con el name dado, solo se puede usar el metodo sobre el document
```