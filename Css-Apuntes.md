# **APUNTES CSS**

## <br>

## [**VIDEITOS DE FRONTEND**](https://www.youtube.com/watch?v=u_GIT5MJAtc)

## **LISTA CON LOS TÉRMINOS COMO SE SUELEN USAR EN LOS ARCHIVOS CSS:**

<br>

---

-`Selector`: Selecciona elementos HTML a los que se aplicarán estilos.

Pueden ser selectores de etiquetas, clases, IDs, atributos, etc.

-`Propiedad`: Define la característica de estilo que deseas cambiar, como el
color, el tamaño, la posición, etc.

-`Valor`: Especifica el valor que deseas asignar a la propiedad seleccionada.
Por ejemplo, para la propiedad "color", el valor podría ser "red", "#FF0000",
"rgb(255, 0, 0)", etc.

-`Background`: Establece el fondo de un elemento.

-`Color`: Establece el color del texto.

-`Font-family`: Establece el tipo de fuente que se utilizará para el texto.

-`Font-size`: Establece el tamaño de la fuente.

-`Margin`: Establece márgenes alrededor de un elemento.

-`Padding`: Establece el espacio interior de un elemento.

-`Border`: Establece un borde alrededor de un elemento.

-`Display`: Especifica cómo se muestra un elemento en el diseño de la página.

-`Position`: Especifica el método de posicionamiento de un elemento.

-`Float`: Especifica si un elemento debe flotar a la izquierda, a la derecha o
no flotar en absoluto.

-`Flexbox`: Un conjunto de propiedades que se utilizan para el diseño flexible
de elementos en un contenedor.

-`Grid`: Un conjunto de propiedades que se utilizan para el diseño de
cuadrículas de elementos en un contenedor.

---

## **EJEMPLOS DE ALGUNAS ETIQUTAS**

---

`Selectores`

```css
/* Selector */
p {
  /* Propiedad */
  color: red; /* Valor */
}

/* Selector de clase */
.btn {
  background: #007bff; /* Valor hexadecimal */
  color: white; /* Valor */
  font-family: Arial, sans-serif; /* Valor */
  font-size: 16px; /* Valor */
  padding: 10px 20px; /* Valor */
  border: 1px solid #007bff; /* Valor hexadecimal */
}

/* Selector de ID */
#header {
  display: flex; /* Valor */
  justify-content: space-between; /* Valor */
  align-items: center; /* Valor */
  padding: 20px; /* Valor */
  background-color: #333; /* Valor hexadecimal */
  color: white; /* Valor */
  font-family: "Arial Black", sans-serif; /* Valor */
}

/* Selector de atributo */
input[type="text"] {
  border: 1px solid #ccc; /* Valor hexadecimal */
  padding: 5px; /* Valor */
}

/* Selector de pseudoclase */
a:hover {
  color: #ff4500; /* Valor hexadecimal */
}

/* Selector combinado */
.container div {
  margin: 10px; /* Valor */
}

/* Selector descendiente */
article p {
  margin-bottom: 20px; /* Valor */
}

/* Selector hijo */
ul > li {
  list-style: none; /* Valor */
}

/* Selector adyacente */
h2 + p {
  font-weight: bold; /* Valor */
}

/* Selector universal */
* {
  box-sizing: border-box; /* Valor */
}
```

---

`Propiedades`

```css
/* Cambiar el color del texto */
color: rojo;

/* Establecer el tamaño de la fuente */
font-size: 16px;
```

---

`Valores`

```css
/* Usar un color hexadecimal */
color: #ff0000;

/* Utilizar una fuente específica */
font-family: Arial, sans-serif;
```

---}

`Background`

```css
/* Establecer un color de fondo */
background-color: #f0f0f0;

/* Usar una imagen de fondo */
background-image: url("imagen.jpg");
```

---

`Margin`

```css
/* Establecer márgenes en todos los lados */
margin: 10px;

/* Especificar márgenes para cada lado */
margin-top: 10px;
margin-bottom: 20px;
margin-left: 5px;
margin-right: 15px;
```

---

`Padding`

```css
/* Establecer relleno en todos los lados */
padding: 20px;

/* Especificar relleno para cada lado */
padding-top: 10px;
padding-bottom: 15px;
padding-left: 5px;
padding-right: 5px;
```

---

`Border`

```css
/* Establecer un borde sólido */
border: 1px solid #000;

/* Especificar estilos de borde individuales */
border-width: 2px;
border-color: #00ff00;
border-style: dashed;
```

---

`Display`

```css
/* Mostrar como bloque */
display: block;

/* Mostrar como en línea */
display: inline;

/* Mostrar como en línea con bloque */
display: inline-block;
```

---

`Position`

```css
/* Posicionar de forma absoluta */
position: absolute;

/* Posicionar de forma relativa */
position: relative;

/* Posicionar de forma fija */
position: fixed;
```

---

`Float`

```css
/* Flotar a la izquierda */
float: left;

/* Flotar a la derecha */
float: right;

/* No flotar */
float: none;
```

---

## **EJEMPLO RESET "Es para aplicarselo al maquetado del archivo HTML y luego empezar hacer los cambios al CSS"**

---

```html
//Muy importante si se va aplicar el reset tiene que ser antes de empezar a
alterar el CSS, de lo contrario si se aplica despues se puede echar a perder
esteticamente lo que ya esta hecho
```

---

```html
% !todo lo que esta en un html es un dom % !selectores: cuerpo completo que son
las etiquetas (tag) o sea el body el header el main etc... selectores de clase
('.' es la manera de llamarlo)===(class)."las clases, estas si se pueden
reutilizar, todo lo contrario a las id" id ('#' es la manera de
llamarlo)===(id)."los id no se pueden repetir, debes ser unicos por cada
elementos" css aplicar estilos % !primer metodo inadecuada 1 se puede editar con
css dentro del mismo html, no es lo mas recomendable pero se puede hacer,
simplemente dentro del cierre de las etiquetas se escribr (style), pero no es lo
mas optimo, queda feo y no es eficiente % ! segundo metodo inadecuado 2 / pero
no tanto dentro del mismo archivo html, pero entre el head y el body se pone una
etiqueta (<style></style>) dentro de hay ya se pueden aplicar los selectores,
tanto de etiqueta como id y clases, se puede aplicar estilos de esta manera pero
no es la mas conveniente. % ?tercer metodo adecuado 3 / y el que se va usar
generar un archivo externo con un nombre y el prefijo de css que es (.css) obvio
con la devida conexion, que en el head se conecta con (<link
  rel="stylesheet"
  href="./index.css" />) //ubicacion del archivo o nombre regla 20min trabajo
solo, sin nadie, si preguntar, sin internet, sin nada ni nadie, ya despues si no
consigo la solucion ppreguntar
```

---

```css
/* Reset CSS */

/* Box model */
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section,
summary,
time,
mark,
audio,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
  box-sizing: border-box;
}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

body {
  line-height: 1;
}

ol,
ul {
  list-style: none;
}

blockquote,
q {
  quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

/* End Reset CSS */
```

---

```css

selector: Selecciona elementos HTML para aplicar estilos.

Ejemplo:

css Copy code /_ Selector de etiqueta _/ p { color: blue; }

/_ Selector de clase _/ .mi-clase { font-size: 18px; }

/_ Selector de ID _/ #mi-id { background-color: #ffffff; } propiedad: Define las
características de estilo que deseas aplicar.

Ejemplo:

css Copy code /_ Cambiar el color del texto _/ color: rojo;

/_ Establecer el tamaño de la fuente _/ font-size: 16px; valor: Especifica el
valor que deseas asignar a la propiedad seleccionada.

Ejemplo:

css Copy code /_ Usar un color hexadecimal _/ color: #ff0000;

/_ Utilizar una fuente específica _/ font-family: Arial, sans-serif; background:
Establece el fondo de un elemento.

Ejemplo:

css Copy code /_ Establecer un color de fondo _/ background-color: #f0f0f0;

/_ Usar una imagen de fondo _/ background-image: url('imagen.jpg'); margin:
Define los márgenes alrededor de un elemento.

Ejemplo:

css Copy code /_ Establecer márgenes en todos los lados _/ margin: 10px;

/_ Especificar márgenes para cada lado _/ margin-top: 10px; margin-bottom: 20px;
margin-left: 5px; margin-right: 15px; padding: Define el espacio interior de un
elemento.

Ejemplo:

css Copy code /_ Establecer relleno en todos los lados _/ padding: 20px;

/_ Especificar relleno para cada lado _/ padding-top: 10px; padding-bottom:
15px; padding-left: 5px; padding-right: 5px; border: Define un borde alrededor
de un elemento.

Ejemplo:

css Copy code /_ Establecer un borde sólido _/ border: 1px solid #000;

/_ Especificar estilos de borde individuales _/ border-width: 2px; border-color:
#00ff00; border-style: dashed; display: Especifica cómo se muestra un elemento
en el diseño de la página.

Ejemplo:

css Copy code /_ Mostrar como bloque _/ display: block;

/_ Mostrar como en línea _/ display: inline;

/_ Mostrar como en línea con bloque _/ display: inline-block; position:
Especifica el método de posicionamiento de un elemento.

Ejemplo:

css Copy code /_ Posicionar de forma absoluta _/ position: absolute;

/_ Posicionar de forma relativa _/ position: relative;

/_ Posicionar de forma fija _/ position: fixed; float: Especifica si un elemento
debe flotar a la izquierda, a la derecha o no flotar en absoluto.

Ejemplo:

css Copy code /_ Flotar a la izquierda _/ float: left;

/_ Flotar a la derecha _/ float: right;

/_ No flotar _/ float: none;

/_ Flotar a la izquierda _/ float: left;

/_ Flotar a la derecha _/ float: right;

/_ No flotar _/ float: none;
```
