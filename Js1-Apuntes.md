# **VARIABLES**

UNA VARIABLE ES UN ELEMENTO QUE NOS PERMITE ALMACENAR DATOS,COMO UNA CAJA. PARA
INDICAR UNA VAREABLE ES CON `var`, Y LUEGO SE INDICA EL NOMBRE, VALOR Y LA
ASIGNACION DE LA VARIABLE, EJEMPLO `edad = 26`

```js
var                     edad                       =               26;

palabra reservada      nombre de la variable      asignacion      valor

```

#### **MAS EJEMPLOS**

```js
var edad = 18;
var nombre = "pepito";
```

<br>

```js
//? Variables
var nombre = "Felipe";
var edad = 24;
var profesion = "Instructor";
var empresa = "Soy Henry";
// Camel Case
var nombreMama = "Aurora";
var nombreDeLaEsposa = "Estefania";
// Snake Case
var nombre_mama = "Aurora";
var nombre_de_la_esposa = 'El autor dijo: "estuvo muy rico"';
// Typescript
//? Tipos de Datos
//* Strings -> Es una cadena de texto
// "Hola, como estas"
//* Number -> -2, 5,
var numero = 6;
//* Boolean -> true, false
var algo = false;
//* Undefined -> la variable si existe, pero no tiene valor
var caja;
//* Not Defined -> la variable no existe
console.log(colegio);
//* Null
var filaDelBanco = null;
filaDelBanco = "Esteban";
//* Object -> Permite agrupar datos
// billetera -> ["plata", "tarjetas", "fotos"]
// persona1 = -> { billetera: ["plata", "fotos"] , vehiculos: ["moto", "carro"]}
//? Operadores
//* Aritmeticos -> + - / * % **
// () ** / * + -
//* De comparacion -> > >= < <= == ===
// 6>8 -> false
// 6>=6 -> true
// 6 == 6 -> sean el mismo valor
// 6 === 6 -> sean el mismo valor y que tengan el mismo tipo de dato
// 6 === "6" -> false
// 87 == "87" -> true
// 70 === "70" -> false
//* Logicos -> not !, and &&, or ||
//? Metodos
var saludo = "hola";
// saludo.length -> 4
var numero = 5; // -> "5"
// numero.toString()
//? Controlador de flujo if, else, else if
if (numero == 3) {
  console.log("hola");
} else if (numero == 5) {
  console.log("me gane la loteria");
} else {
  console.log("chao");
}
//? Funciones
// Una funcion es una maquinita
// le ingresa algo
// efectua un proceso
// devuelve algo
function saludar(nombre) {
  // nombre: "Feli"
  console.log("hola " + nombre);
  // "hola " + "Feli"
  // "hola Feli"
}
saludar("pepito");
//? Math
// Math.ceil(5.6) -> 6
```

CTRL + } para comentar

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
