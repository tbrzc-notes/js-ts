La interfaz 'node' es abstracta lo que significa que no puede ser instanciada pero si extendida por otras clases
# propiedades y métodos
## obtener elementos
[[nodelist]]
- [[childNodes]] 
- [[first-lastChilld]]
- [[next-previusSibling]]
- parentNode
- nodeName
![[node interface-20240523164725746.webp]]
## modificar elementos
### añadir
- [[appendChild]]()
- [[insertBefore]]
- [[cloneNode]]
### remover
- [[removeChild]]
### replace 
- `node.replaceChild(newNode, oldNode)`
![[node interface-20240523164850109.webp]]
- nodeType y constantes de la interface `Node`
```js
var mainElement = document.getElementById('main')
mainElement.childNodes[0].nodeType === Node.ELEMENT_NODE
```
![[node interface-20240523165059266.webp]]