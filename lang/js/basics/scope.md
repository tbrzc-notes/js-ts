---
date-to-study: 2025-10-10
tags:
  - summary
---
---
## const
- usar const por defecto y cambia a let si necesitas reasignar
- let es de ambito de bloque
- generalmente en objetos puedes mutar el objeto pero no la referencia
```js
const config = { modo: "prod" };
config.modo = "dev"; // ✅ permitido (objeto mutable)
config = {};         // ❌ TypeError (referencia inmutable)
```
## var 
- el prpoblema de var es el hoisting y un ambito global o de funcion

---
- [ ] summary  📅 2025-10-10
- [ ] 3-day 
- [ ] 1-week 
- [ ] 1-month 
- [ ] 3-month 
- [ ] 1-year 