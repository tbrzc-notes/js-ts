---
date-to-study: 2025-10-09
tags:
  - summary
---
---
## Title

```html
<!--
es util para scritps que deben ejecutarse antes de que se renderice el DOM, ya que bloquea el renderizado de este
 -->
<head>
  <script src="main.js"></script>
</head>
<!-- ideal para archivos que modifican el DOM -->
<body>
  <!-- contenido HTML -->
  <script src="main.js"></script>
</body>
<!-- El script se descarga en paralelo y se ejecuta despues de que el dom este listo, mantiene el orden de ejecucion -->
<head>
  <script src="main.js" defer></script>
</head>
<!-- El script se descarga en paralelo y se ejecuta tan pronte este listo, no mantiene ni respeta el orden de ejecucion -->
<head>
  <script src="analytics.js" async></script>
</head>
```
---
- [ ] summary  📅 2025-10-09
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 