# Corrección Actividad



## Prompt 1

### Instrucciones.

vas a actuar como un docente de programación para estudiantes de 17 - 24 años con enfoque en JavaScript, donde a manera de pregunta y respuesta me vas explicando varios conceptos que no entiendo. Mas adelante te daré un contexto de mi persona y la situación, como sera la entrada de lo que te comente anteriormente y como me responderás.

### Contexto:

Soy estudiante de programación, donde actualmente me estoy enfocando en el lenguaje de JavaScript, específicamente Vanilla. En mi etapa inicial de aprendizaje, he tenido dificultades para aprender los conceptos de los tipos de declaración de variables, pese a que yo los implemente adentro de mi código, pero lo hago sin entender su concepto.

### Entrada

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de casa de estudio como funciona dicho concepto. Esta pregunta sera de manera directa como mensaje del prompt.

### Salida

me responderás con una explicacion pedagogica a nivel de caso de estudio, donde mezcles la explicacion teorica con ejemplos codificable y texto argumentativo, haciendo linea al codigo que se genera.

### Ejemplo

La sumatoria de variables en JavaScript se puede realizar con numeros enteros de la siguiente manera:

```javascript
a = 5;
b = 2;
c = a+b;
console.log(c);
```

En donde:

1. a y b = Son variables que contienen los valores de 5 y 2.
2. c = Realiza la sumatoria de las variables "a" y "b".
3. console.log(c) = Muestra el resultado generado de la sumatoria de "a" y "b".

### Pregunta #1

¿como se puede entender los conceptos de var, let y const?

------



## Prompt 2

### Instrucciones.

vas a actuar como un instructor de programación para desarrolladores junior con enfoque en JavaScript, donde a manera de pregunta y respuesta me vas explicando este concepto que no entiendo. Te voy aportar un contexto y la situación, como sera la entrada de lo que te comente anteriormente y como me responderás.

### Contexto:

Soy estudiante de programación, donde actualmente me estoy enfocando en el lenguaje de JavaScript, específicamente Vanilla. Durante mi aprendizaje, en mis conocimientos no me ha quedado por sentado el concepto de condicionales aunque ya los he usado sigo sin entender del todo el concepto.

### Entrada

Aqui va la Pregunta, con el fin de que me expliques a nivel de casa de estudio como funciona dicho concepto. Esta pregunta sera de manera directa como mensaje del prompt.

### Salida

Me responderás con una explicacion adecuada segun la instruccion y contexto correspondiente, donde mezcles la explicacion teorica con ejemplos y texto argumentativo, haciendo linea al codigo que se genera.

### Ejemplo

Los condicionales en JavaScript se puede realizar con :

```javascript
// ejemplo
```
### Pregunta #1

¿como se puede entender los conceptos de Condicionales?

------





## Prompt 3



### Instrucciones.

vas a actuar como un docente de programación para estudiantes que están empezando en JavaScript. A manera de pregunta y respuesta me vas explicando este concepto que aún no comprendo bien. Más adelante te daré el contexto como entrada.

### Contexto:

Estoy aprendiendo JavaScript Vanilla y todavía me cuesta entender realmente qué es una función y por qué se usa. La puedo escribir y ejecutarla, pero no logro entender bien su propósito a nivel conceptual.

### Entrada

Aquí irá mi pregunta puntual para que me expliques a nivel de casa de estudio cómo funciona dicho concepto. La pregunta será directa en el mensaje del prompt.

### Salida

me responderás combinando explicación teórica, ejemplos prácticos y texto argumentativo que haga relación directa con el código generado.

### Ejemplo
function saludar() {
  console.log("Hola");
}

saludar();

### Pregunta #1

¿qué es y para qué sirve una función en JavaScript?

------





## Prompt 4



## Instrucciones.

vas a actuar como instructor de programación para estudiantes en nivel inicial, donde por medio de preguntas y respuestas me aclararás conceptos relacionados con arreglos en JavaScript.

## Contexto:

Aunque ya he usado arrays en algunos ejercicios, no tengo claro qué los diferencia de una variable normal y cuándo debería utilizarlos correctamente dentro de mi código.

## Entrada

Aquí irá la pregunta puntual sobre el concepto que necesito entender mejor.

## Salida

Me responderás usando explicación teórica, ejemplos de código y texto argumentativo que acompañe la parte práctica.

## Ejemplo
let frutas = ["manzana", "pera", "uva"];
console.log(frutas[1]);

## Pregunta #1

¿qué es un array y en qué casos se debería usar en JavaScript?






------





## Prompt 5


### Instrucciones.

vas a actuar como un docente que guía a estudiantes de JavaScript en su proceso de aprendizaje inicial, explicando conceptos paso a paso mediante preguntas.

### Contexto:

Estoy aprendiendo sobre funciones flecha (arrow functions), pero aunque las escribo, no entiendo muy bien qué diferencia tienen con las funciones tradicionales.

### Entrada

Aquí colocaré la pregunta puntual.

### Salida

Deberás responder combinando teoría, ejemplos de código y un argumento que conecte todo para que entienda el concepto.

### Ejemplo
const sumar = (a, b) => a + b;
console.log(sumar(2,4));

#### Pregunta #1

¿qué diferencia hay entre una función tradicional y una arrow function?


------





## Prompt 6


### Instrucciones.

actuarás como instructor de programación para explicarme conceptos que estoy usando pero no entiendo completamente. El formato será pregunta y respuesta.

### Contexto:

Estoy viendo objetos en JavaScript, pero me cuesta relacionarlos con escenarios reales y entender por qué son tan usados.

### Entrada

Aquí irá la pregunta puntual.

### Salida

Me responderás con teoría, ejemplos y texto argumentativo.

### Ejemplo
let persona = {
  nombre: "Ana",
  edad: 21
};
console.log(persona.nombre);

### Pregunta #1

¿qué es un objeto y por qué es tan importante en JavaScript?

# Prompt 7

### Instrucciones

Este prompt lo utilizaré para comprender cómo maneja JavaScript la programación asíncrona en su forma más básica. Busco una explicación clara que me permita entender el concepto de callbacks desde una perspectiva práctica y conceptual, adecuada para alguien que está dando sus primeros pasos en este tema.

### Contexto

Aunque he visto ejemplos de funciones que reciben otras funciones como argumento, todavía no comprendo el propósito ni el funcionamiento detallado de los callbacks. Me cuesta visualizar qué papel juegan dentro del flujo del programa.

### Entrada

Aquí incluiré una pregunta específica relacionada con callbacks, la cual reflejará mi duda principal mientras estudio o practico este concepto.

### Salida

La respuesta deberá integrar explicación teórica, un ejemplo sencillo y una descripción clara de cómo se ejecuta un callback dentro del flujo de un programa.

### Ejemplo

```
function ejecutar(callback){
  callback("Listo");
}
```

### Pregunta #1

¿qué es un callback en JavaScript y cuál es su propósito?

------

# Prompt 8

### Instrucciones

Este prompt lo usaré para aclarar cómo funcionan las reglas internas que determinan dónde se puede acceder a una variable. Busco una explicación completa del concepto de scope, orientada a un desarrollador en aprendizaje que desea una visión clara y aplicable.

### Contexto

He experimentado errores en mis ejercicios porque algunas variables no están disponibles donde espero. Puedo intuir que esto tiene relación con el alcance, pero no termino de entender cómo se define realmente.

### Entrada

Aquí escribiré la pregunta puntual sobre scope que necesito aclarar, expresada de forma directa y realista.

### Salida

La explicación debe incluir teoría, un ejemplo corto que muestre distintos tipos de alcance y un texto argumentativo que permita entender la lógica detrás del comportamiento de las variables.

### Ejemplo

```
function ejemplo(){
  let x = 10;
  console.log(x);
}
```

### Pregunta #1

¿qué es el scope en JavaScript y cómo afecta el acceso a las variables?

------

# Prompt 9

### Instrucciones

Este prompt lo quiero usar para comprender mejor cómo toma decisiones JavaScript cuando evalúa expresiones lógicas. Necesito una explicación orientada a alguien que está aprendiendo a escribir código más expresivo y confiable.

### Contexto

Aunque uso operadores lógicos en mis ejercicios, muchas veces no entiendo por qué ciertas combinaciones devuelven verdadero o falso. Esto me dificulta controlar correctamente el flujo de mis programas.

### Entrada

Aquí colocaré una pregunta específica sobre operadores lógicos, enfocada en su funcionamiento o aplicación.

### Salida

La explicación debe integrar teoría, un ejemplo corto y un comentario argumentado que muestre cómo interpretar los resultados lógicos.

### Ejemplo

```
let acceso = edad >= 18 && tieneID;
```

### Pregunta #1

¿cómo funcionan los operadores lógicos AND, OR y NOT en JavaScript?

------

# Prompt 10

### Instrucciones

Usaré este prompt para comprender cómo repetir acciones de forma controlada en JavaScript. La explicación debe orientarse a alguien que está aprendiendo a identificar patrones que requieren ciclos en el código.

### Contexto

Los ciclos están presentes en la mayoría de lenguajes, pero me cuesta ver de manera clara en qué situaciones debo aplicarlos y cómo funcionan internamente dentro del programa.

### Entrada

Aquí escribiré mi pregunta exacta sobre ciclos, enfocándome en la duda central que tengo al usarlos.

### Salida

La respuesta debe combinar teoría, un ejemplo corto y una explicación paso a paso de cómo se ejecuta el ciclo en tiempo real.

### Ejemplo

```
for(let i = 0; i < 3; i++){
  console.log(i);
}
```

### Pregunta #1

¿qué es un ciclo y para qué se utiliza en JavaScript?

------

# Prompt 11

### Instrucciones

Este prompt me servirá para entender cómo JavaScript interpreta y transforma valores cuando se realizan operaciones entre tipos distintos. La explicación debe ser clara y orientada a un desarrollador que aún se adapta a la flexibilidad del lenguaje.

### Contexto

He visto resultados inesperados al combinar valores numéricos y cadenas, lo cual entiendo que tiene que ver con la coerción de tipos. Sin embargo, necesito comprender qué hace JavaScript exactamente en estos casos.

### Entrada

Aquí incluiré la pregunta puntual relacionada con la coerción de tipos.

### Salida

La explicación debe integrar teoría, un ejemplo mínimo y un argumento que me ayude a entender por qué este comportamiento puede causar confusión o errores.

### Ejemplo

```
console.log("4" - 2);
```

### Pregunta #1

¿qué es la coerción de tipos en JavaScript y cómo afecta los resultados?

------

# Prompt 12

### Instrucciones

Usaré este prompt para entender un formato de datos esencial en desarrollo web moderno: JSON. Necesito una explicación clara que me permita comprender su estructura y su relación con JavaScript.

### Contexto

JSON aparece constantemente en ejemplos y documentación, pero aún no tengo claro cómo se relaciona con objetos o por qué es el formato estándar para enviar información entre sistemas.

### Entrada

Aquí escribiré mi pregunta específica sobre JSON para orientar la explicación.

### Salida

La respuesta debe incluir teoría, un ejemplo sencillo y una descripción clara sobre la utilidad de JSON en el ecosistema JavaScript.

### Ejemplo

```
let datos = '{"nombre": "Luis"}';
```

### Pregunta #1

¿qué es JSON y por qué es tan utilizado en JavaScript?

------

# Prompt 13

### Instrucciones

Este prompt me ayudará a profundizar en métodos avanzados para trabajar con arrays en JavaScript. Busco una explicación detallada y práctica que me ayude a entender cómo transforman o filtran información.

### Contexto

He usado `map`, `filter` y `reduce`, pero no termino de comprender qué hace exactamente cada uno ni cómo debería aplicarlos en casos reales.

### Entrada

Aquí escribiré la pregunta relacionada con el uso de estos métodos.

### Salida

Debes proporcionar teoría clara, un ejemplo corto y una narrativa que conecte su uso con problemas comunes en el manejo de arrays.

### Ejemplo

```
let nums = [1,2,3];
nums.map(n => n * 2);
```

### Pregunta #1

¿cómo funcionan los métodos map, filter y reduce en JavaScript?

------

# Prompt 14

### Instrucciones

Este prompt lo usaré para entender correctamente cómo compara valores JavaScript. Necesito una explicación clara que evite confusiones al trabajar con igualdad flexible y estricta.

### Contexto

Los operadores `==` y `===` son muy similares visualmente, pero su comportamiento difiere. Esto me ha generado errores sutiles que quiero evitar comprendiendo sus diferencias.

### Entrada

Aquí incluiré una pregunta puntual sobre estos operadores.

### Salida

La explicación debe incluir teoría, un ejemplo breve y un análisis del comportamiento de cada comparación.

### Ejemplo

```
console.log(5 == "5");
console.log(5 === "5");
```

### Pregunta #1

¿qué diferencia hay entre == y === en JavaScript?

------

# Prompt 15

### Instrucciones

Este prompt me ayudará a profundizar en cómo JavaScript interactúa con páginas web a través del DOM. Deseo una explicación clara que me permita manipular elementos de manera más segura y efectiva.

### Contexto

Aunque he logrado modificar textos y atributos de algunos elementos, aún no comprendo completamente qué representa el DOM ni cómo está estructurado.

### Entrada

Aquí escribiré mi pregunta puntual sobre el DOM.

### Salida

La explicación debe combinar teoría, un ejemplo corto y una narrativa que muestre el impacto de las modificaciones en la página.

### Ejemplo

```
document.querySelector("#titulo").textContent = "Hola";
```

### Pregunta #1

¿qué es el DOM y cómo se manipula desde JavaScript?

------

# Prompt 16

### Instrucciones

Quiero entender cómo reaccionan las páginas web a acciones del usuario. Este prompt me permitirá profundizar en el concepto de eventos dentro de JavaScript.

### Contexto

He usado eventos como el click, pero aún no comprendo cómo se ejecutan ni cómo funcionan internamente para responder a la interacción del usuario.

### Entrada

Aquí escribiré mi pregunta sobre eventos.

### Salida

La explicación debe ser clara, acompañada de un ejemplo breve y una narrativa sobre cómo se desencadena un evento.

### Ejemplo

```
boton.addEventListener("click", () => console.log("Click"));
```

### Pregunta #1

¿qué es un evento en JavaScript y cómo funciona su ejecución?

------

# Prompt 17

### Instrucciones

Este prompt lo utilizaré para comprender el funcionamiento del valor `this`, uno de los aspectos más particulares de JavaScript. Necesito una explicación apta para un desarrollador que está dando el salto hacia conceptos más avanzados.

### Contexto

He visto que `this` puede apuntar a distintos objetos según dónde se use, y eso me genera confusión al escribir funciones y métodos.

### Entrada

Aquí escribiré la pregunta específica sobre el valor de `this`.

### Salida

La respuesta debe incluir teoría clara, un ejemplo corto y una explicación práctica de cómo se define su valor.

### Ejemplo

```
let obj = {
  nombre: "Sara",
  mostrar(){ console.log(this.nombre); }
};
```

### Pregunta #1

¿qué es `this` en JavaScript y cómo se define su valor?

------

# Prompt 18

### Instrucciones

Este prompt me servirá para mejorar la forma en la que trabajo con texto dentro de JavaScript. Busco entender por qué las template strings son tan utilizadas en código moderno.

### Contexto

He visto su sintaxis usando backticks y variables embebidas, pero quiero comprender claramente por qué son más convenientes que otras formas de concatenar texto.

### Entrada

Aquí escribiré mi pregunta concreta sobre las template strings.

### Salida

La explicación debe mezclar teoría, un ejemplo mínimo y una narrativa argumentada que muestre su utilidad práctica.

### Ejemplo

```
let nombre = "Ana";
console.log(`Hola ${nombre}`);
```

### Pregunta #1

¿qué son las template strings y qué ventajas tienen?

------

# Prompt 19

### Instrucciones

Este prompt lo usaré para comprender un concepto clave en programación asíncrona: las Promises. Necesito una explicación orientada a un desarrollador en proceso de aprendizaje.

### Contexto

Las promesas aparecen en múltiples ejemplos y documentación, pero me cuesta entender qué representan exactamente y cómo gestionan tareas asíncronas.

### Entrada

Aquí escribiré mi pregunta puntual sobre Promises.

### Salida

La respuesta debe incluir teoría, un ejemplo corto y una explicación clara de cómo se resuelve o rechaza una promesa.

### Ejemplo

```
let p = new Promise(resolve => resolve("ok"));
```

### Pregunta #1

¿qué es una Promise en JavaScript y cómo funciona?

------

# Prompt 20

### Instrucciones

Este prompt lo usaré para comprender mejor el manejo moderno de tareas asíncronas utilizando async y await. Quiero entender su rol dentro del flujo del programa.

### Contexto

Aunque ya he visto ejemplos usando await, todavía no comprendo cómo transforma la manera de manejar Promises ni por qué hace el código más fácil de leer.

### Entrada

Aquí pondré mi duda puntual sobre async/await.

### Salida

La explicación debe integrar teoría, un ejemplo claro y una narrativa que muestre cómo cambia el flujo de ejecución cuando se utiliza await.

### Ejemplo

```
async function cargar(){
  let r = await fetch("url");
}
```

### Pregunta #1

¿cómo funcionan async y await en JavaScript y cuándo conviene usarlos?