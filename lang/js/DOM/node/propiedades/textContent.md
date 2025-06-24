Mejor rendimiento que `innerHTML-Text` en cuanto a modificar el contenido en texto de un nodo
en cuanto a su retorno es muy similar a [[nodeValue]] con las siguientes diferencias
- para nodos de tipo`fragment element` concatena el texto de cada uno de sus elementos secundarios, excluyendo nodos de tipo `comment`
- cuenta con `get` y `set`