# Centrado de elementos

## position: absolute

Con las propiedades __left: 0__, __top: 0__, __right: 0__, __bottom: 0__ y __margin: auto__

```css
.dialog-box {
      position: absolute;
      left: 0;
      top: 0;
      right: 0;
      bottom: 0;

      margin: auto;

      /*inset: 0;*/ /*Para no poner left, top, right, bottom*/
    }
```

La propiedad de CSS __inset__ define el __bloque lógico__ que nos permite prescindir de __left: 0__, __top: 0__, __right: 0__, __bottom: 0__ y __margin: auto__.