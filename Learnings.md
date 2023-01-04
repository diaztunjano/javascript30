# Random nuggets of info:

## General

- Referenciar el css desde el html en la parte del `<head>`: `<link rel="stylesheet" href="style.css" />`

## CSS

- Background con opacidad `(rgba(0,0,0,0.4))` y text-shadow hacen maravillas para resaltar letras. Ver como funciona en la clase .key del ejercicio 1 de drum-kit.

- Puedo seleccionar un div en una const y luego a esa, le puedo cambiar los estilos como:

```javascript
const secondHand = document.querySelector(".second-hand");
secondHand.style.transform = `rotate(${secDegree}deg)`;
```

## Por mejorar:

- Aprender cómo funciona position: relative/absolute
