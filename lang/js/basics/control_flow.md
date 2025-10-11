# flujo de control iterativo y condicional
para valores booleanos en las variables es recomendable usar `isSomething = true/false`
```js
// if
if (isRaining) alert("Don't forget an umbrella!");
```
- mala practica
```js
if(permiso == 'admin' || permiso == 'root') canDelete == true;
else canDelete == false

//si la condicion devuelve true o false mejor guardar ese valor en la variable directamente

canDelete = permiso == 'admin' || permiso == 'root'
```
- switch simple: el default al final es por convención y no es necesariamente requerido