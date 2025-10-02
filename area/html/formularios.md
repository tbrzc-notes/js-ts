---
date-to-study: 2025-06-28
tags:
  - summary
---
---
## form_tag

```html
  <form action="/procesar-registro" method="POST" enctype="multipart/form-data" autocomplete="on">
    <fieldset>
      <legend>Información Personal</legend>

      <label for="nombre">Nombre completo:</label>
      <input type="text" id="nombre" name="nombre" required placeholder="Tu nombre aquí">

      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required>

      <label for="password">Contraseña:</label>
      <input type="password" id="password" name="password" required minlength="6">

      <label for="fecha">Fecha de nacimiento:</label>
      <input type="date" id="fecha" name="fecha">

      <label for="genero">Género:</label>
      <select id="genero" name="genero">
        <option value="">Selecciona una opción</option>
        <option value="masculino">Masculino</option>
        <option value="femenino">Femenino</option>
        <option value="otro">Otro</option>
      </select>

      <label for="foto">Foto de perfil:</label>
      <input type="file" id="foto" name="foto" accept="image/*">
    </fieldset>

    <fieldset>
      <legend>Preferencias</legend>

      <label>
        <input type="checkbox" name="suscripcion" value="boletin">
        Deseo recibir el boletín informativo
      </label>

      <label>Idioma preferido:</label>
      <label><input type="radio" name="idioma" value="es" checked> Español</label>
      <label><input type="radio" name="idioma" value="en"> Inglés</label>

      <label for="comentarios">Comentarios adicionales:</label>
      <textarea id="comentarios" name="comentarios" rows="4" placeholder="Escribe tus observaciones..."></textarea>
    </fieldset>

    <input type="hidden" name="token" value="abc123xyz">

    <button type="submit">Enviar</button>
    <button type="reset">Limpiar</button>
  </form>
```

## implicit_labeling
```html
<form>
   <p>Gender</p>

   <label><input type="radio" name="gender" value="male"> Male</label>

   <label><input type="radio" name="gender" value="female"> Female</label>
   
   <label><input type="radio" name="gender" value="other"> Other</label>
</form>
```

## input_types
- Single-line text inputs — `"text"`
- Password inputs — `"password"`
- Radio buttons — `"radio"`
- Checkboxes — `"checkbox"`
- File inputs — `"file"`
```html
<form method="POST" enctype="multipart/form-data">
   <p>CV (Upload a PDF.)</p>
   <input type="file" name="cv">
</form>
```
- Hidden inputs — `"hidden"`
usually contain authentication tokens and/or other ancillary information in a form
```html
<form>
   <input type="hidden" name="csrf_token" value="somerandomvalue">
</form>
```
```html
<textarea cols="30" rows="6">Hello</textarea>
```
| Value              | Meaning                                                     |     |
| ------------------ | ----------------------------------------------------------- | --- |
| `"email"`          | A specialized text box for email addresses.                 |     |
| `"search"`         | A specialized text box for search queries.                  |     |
| `"number"`         | A specialized text box for numbers.                         |     |
| `"tel"`            | A specialized text box for telephone numbers.               |     |
| `"url"`            | A specialized text box for URLs.                            |     |
| `"range"`          | A slider input for choosing a particular number in a range. |     |
| `"color"`          | A color picker.                                             |     |
| `"date"`           | A date picker.                                              |     |
| `"month"`          | A month picker.                                             |     |
| `"week"`           | A week picker.                                              |     |
| `"time"`           | A time picker.                                              |     |
| `"datetime-local"` | A date and time picker.                                     |     |
| `"email"`          | A specialized text box for email addresses.                 |     |
| `"search"`         | A specialized text box for search queries.                  |     |
| `"number"`         | A specialized text box for numbers.                         |     |
| `"tel"`            | A specialized text box for telephone numbers.               |     |
| `"url"`            | A specialized text box for URLs.                            |     |
| `"range"`          | A slider input for choosing a particular number in a range. |     |
| `"color"`          | A color picker.                                             |     |
| `"date"`           | A date picker.                                              |     |
| `"month"`          | A month picker.                                             |     |
| `"week"`           | A week picker.                                              |     |
| `"time"`           | A time picker.                                              |     |
| `"datetime-local"` | A date and time picker.                                     |     |                                                            |     |

## buttons
We should **always use `<button>` over `<input>`** for creating a button. Period.

|Value|Meaning|
|---|---|
|`"submit"`|A submit button for submitting a form.|
|`"reset"`|A reset button for resetting a form to its original state.|
|`"button"`|A normal button without any default behavior.|
|`"image"`|A submit button rendered using an image.|

- **`minlength`**
- **`maxlength`**

## datalist
```html
<label>
   Country
   <input type="text" name="country" list="country-list" autocomplete="off">
</label>

<datalist id="country-list">
   <option value="VI">U.S. Virgin Islands</option>
   <option value="UG">Uganda</option>
   <option value="UA">Ukraine</option>
   <option value="AE">United Arab Emirates</option>
   <option value="GB">United Kingdom</option>
   <option value="US">United States</option>
   <option value="UY">Uruguay</option>
   <option value="UZ">Uzbekistan</option>
</datalist>
```


## output element


## Docs
- https://www.codeguage.com/v1/courses/html/forms-input-types
- https://www.codeguage.com/v1/courses/html/forms-fieldsets
- https://www.codeguage.com/v1/courses/html/forms-datalists
- https://www.codeguage.com/v1/courses/html/forms-the-output-element
---
- [ ] summary  📅 2025-06-28
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 