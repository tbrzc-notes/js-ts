funciona como get y set, se recomienda usar la menor cantidad de innerHTML
- si existen elementos dentro estos son reescritos 
```js
const mainElement = document.getElementById('main')

mainElement.innerHTML = `//template literal
	<h1>A new heading</h1>
	<p>A new paragraph</p>
`
```