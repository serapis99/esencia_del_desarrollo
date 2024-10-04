---
tags:
  - Definicion
---
# Tipado Débil

## Definición 

Cuando hablo de tipado débil quiero decir que  para hacer operaciones entre datos de diferentes tipos este lo hace ignorando el tipo y se debe usar una operador diferente para indicar que se debe evaluar el tipo.
## Ejemplo

Un ejemplo claro es comparar un numero entero con un el carácter, en los lenguajes de tipado débil, aparece el triple igual para indicarle al lenguaje que queremos hacer comparación de tipos.

```javascript
// Comparacion de tipos: esta comparacion da false
if (1==='1'){console.log('true')} 
else {console.log('false')}

// Comparacion de valores: esta comparacion da true
if(1=='1'){console.log('true')}
else {console.log('false')}
```

## Lenguajes

+ [[PHP]]
+ [[JavaScript]]