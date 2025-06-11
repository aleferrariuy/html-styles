# Reinicia estilos CSS a valores por defecto

---

## Puntos necesarios para reiniciar los estilos de un archivo HTML versión 5

### 1️⃣ Eliminación de márgenes, padding y bordes
~~~
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
~~~

### 2️⃣ HTML5 display-role reset for older browsers
~~~
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
~~~

### 3️⃣ Lista y tablas
~~~
ol, ul { list-style: none; }
table { border-collapse: collapse; border-spacing: 0; }
~~~

### 4️⃣ Cajas y tipografía 
~~~
* { box-sizing: border-box; }
body { line-height: 1; }

a { text-decoration: none; color: inherit; }
~~~

### 5️⃣ Formularios 
~~~
button, input, select, textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  margin: 0;
}
button, input { overflow: visible; }
button, select { text-transform: none; }
button::-moz-focus-inner, input::-moz-focus-inner {
  border: 0; padding: 0;
}
input[type="search"] {
  -webkit-appearance: textfield;
  outline-offset: -2px;
}
~~~

### 6️⃣ Eliminación de estilos de enlaces en algunos navegadores 
~~~
a:focus, a:active { outline: none; }
~~~

### 7️⃣ Eliminar degradados de botones en iOS 
~~~
button, html input[type="button"], input[type="reset"], input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
~~~

### 8️⃣ SVG 
~~~
svg:not(:root) { overflow: hidden; }
~~~

### 9️⃣ Imágenes 
~~~
img { display: block; max-width: 100%; height: auto; }
~~~
---
---
