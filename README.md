# PROYECTO-Glosario
Proyecto final de fundamento de computación  
# Glosario de Programación

## 1. Algoritmo

Un algoritmo es una serie de pasos lógicos ordenados para que sigan para resolver un problema o realizar una tarea. Antes de programar algo, se puede decir que el algoritmo es que le indica al programa qué se va a hacer.

**Ejemplo:**

Para calcular el promedio de tres calificaciones, el algoritmo podría ser:

1. Pedir las 3 calificaciones.
2. Sumarlas.
3. Dividir el resultado entre 3.
4. Mostrar el promedio.

**Fuente:**  
IBM. (s. f.). *What is an algorithm?* IBM.  
https://www.ibm.com/think/topics/algorithm

---

## 2. Programa

Un programa es un conjunto de instrucciones que la computadora puede entender y ejecutar. Puede ser desde algo muy sencillo o algo más complejo.

**Ejemplo:**

Una aplicación para calcular las calificaciones de los alumnos.

**Fuente:**  
IBM. (s. f.). *What is programming?* IBM.  
https://www.ibm.com/think/topics/programming

---

## 3. Código fuente

El código fuente es el conjunto de instrucciones escritas por el programador utilizando un lenguaje de programación. Es la parte que una persona puede leer y modificar para indicar cómo debe funcionar un programa.

**Ejemplo:**

```python
print("hola mundo")
```
Fuente:
IBM. (s. f.). What is source code? IBM.
https://www.ibm.com/think/topics/source-code

## 4. Lenguaje de programación

Un lenguaje de programación es un sistema de reglas y palabras que permite escribir instrucciones para que una computadora pueda interpretarlas o ejecutarlas. Existen muchos lenguajes y cada uno tiene características y usos diferentes.

**Ejemplo:**

JavaScript, Python, Java y C++.

Fuente:
MDN Web Docs. (2026). JavaScript. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript

---

## 5. Sintaxis

La sintaxis son las reglas que indican cómo se deben escribir correctamente las instrucciones de un lenguaje de programación. Si se escribe algo de una manera que no respeta esas reglas, el programa puede producir un error.

**Ejemplo:**

Python:

Print"hola mundo"

Está mal escrito.

print("hola mundo")

Está bien la sintaxis.

Fuente:
MDN Web Docs. (2026). JavaScript language overview. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Language_overview

---

## 6. Variable

Las variables son espacios a los que se les asigna un nombre y un valor, dependiendo del tipo de dato que se quiera guardar, para poder utilizarlo o modificarlo después.

**Ejemplo:**

let edad = 17

Fuente:
MDN Web Docs. (2026). JavaScript language overview. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Language_overview

---

## 7. Constante

Una constante es un dato que se declara para que su referencia no pueda recibir posteriormente otro valor. Se utiliza cuando queremos que determinada información permanezca igual durante el programa.

**Ejemplo:**

const PI = 3.1416

Fuente:
MDN Web Docs. (2026). JavaScript language overview. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Language_overview

---

## 8. Tipo de dato

El tipo de dato indica qué clase de información representa un valor. Dependiendo del lenguaje, existen diferentes tipos, como números, texto o valores que representan verdadero o falso.

**Ejemplo:**

let edad = 17
let nombre = "Esmeralda"
let aprobado = true

Fuente:
MDN Web Docs. (2026). JavaScript language overview. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Language_overview

---

## 9. Operador

Un operador es un símbolo o palabra que permite realizar una operación sobre uno o más valores. Puede utilizarse para hacer cálculos, comparar datos o realizar operaciones lógicas.

**Ejemplo:**

Aritméticos: sirven para cuentas matemáticas como sumar (+), restar (-), multiplicar (*), dividir (/) o sacar el residuo de una división (%).

Fuente:
MDN Web Docs. (2026). Expressions and operators. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_operators

---

## 10. Expresión

Una expresión es una combinación de valores, variables y operadores que puede producir un resultado.

**Ejemplo:**

5 + 8 = 13

Fuente:
MDN Web Docs. (2026). Expressions and operators. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_operators

---

## 11. Condicional

Un condicional permite que un programa tome una decisión dependiendo de si se cumple o no una determinada condición. De esta manera, el programa puede ejecutar diferentes instrucciones según la situación.

**Ejemplo:**
```
if (edad >= 18) {
  console.log("Puede entrar");
} else {
  console.log("No puede entrar");
}
```
El programa revisa la edad y decide qué mensaje mostrar.

Fuente:
MDN Web Docs. (2026). Control flow and error handling. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling

---

## 12. Bucle

Un bucle es una estructura que permite repetir un conjunto de instrucciones varias veces. La repetición puede depender de una condición o de una cantidad determinada de veces.

**Ejemplo:**
```
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```
Este bucle muestra los números del 1 al 5 sin tener que escribir cinco veces la misma instrucción.

Fuente:
MDN Web Docs. (2026). Loops and iteration. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration

---

##13. Función

Una función es un bloque de instrucciones creado para realizar una tarea específica. Puede utilizarse varias veces sin tener que escribir nuevamente todas las instrucciones.

**Ejemplo:**
```
function saludar() {
  console.log("Hola");
}
```
saludar();

La función saludar contiene la instrucción que muestra el mensaje y puede llamarse cuando sea necesario.

Fuente:
MDN Web Docs. (2026). Functions. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

---

## 14. Parámetro

Un parámetro es una variable que se coloca en la definición de una función para recibir un dato cuando esa función sea utilizada.

**Ejemplo:**
```
function saludar(nombre) {
  console.log("Hola " + nombre);
}
```
En este caso, nombre es el parámetro de la función.

Fuente:
MDN Web Docs. (2026). Functions. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

---

## 15. Argumento

Un argumento es el valor que se proporciona a una función cuando la llamamos. Ese valor se utiliza para darle información a los parámetros de la función.

**Ejemplo:**
```
function saludar(nombre) {
  console.log("Hola " + nombre);
}

saludar("juanito");
```
"juanito" es el argumento que se envía al parámetro nombre.

Fuente:
MDN Web Docs. (2026). Functions. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

---

## 16. Retorno

El retorno es el resultado que una función puede devolver después de realizar una operación. En JavaScript se utiliza la palabra return para regresar ese valor.

**Ejemplo:**

function sumar(a, b) {
  return a + b;
}
```
let resultado = sumar(5, 3);
```
La función devuelve 8, que después se guarda en resultado.

Fuente:
MDN Web Docs. (2026). Functions. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

---

## 17. Arreglo

Un arreglo es una estructura que permite almacenar varios valores dentro de una misma variable. Los elementos se pueden identificar mediante una posición o índice.

**Ejemplo:**
```
let frutas = ["manzana", "pera", "uva"];
```

El arreglo frutas contiene tres elementos que pueden consultarse individualmente.

Fuente:
MDN Web Docs. (2026). Indexed collections. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections

18. Objeto

Un objeto es una estructura que permite reunir diferentes datos relacionados utilizando propiedades. Cada propiedad tiene un nombre y un valor, por lo que resulta útil para representar cosas o elementos con varias características.

Ejemplo:

let alumno = {
  nombre: "Esmeralda",
  edad: 17,
  semestre: 6
};

El objeto alumno reúne información relacionada con una misma persona.

Fuente:
MDN Web Docs. (2026). Working with objects. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects

19. Método

Un método es una función que está asociada a un objeto y que permite realizar una acción relacionada con ese objeto.

Ejemplo:

let nombre = "Juanito";
nombre.toUpperCase();

toUpperCase() es un método que puede utilizarse con una cadena de texto para convertir sus letras a mayúsculas.

Fuente:
MDN Web Docs. (2026). Working with objects. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects

20. Evento

Un evento es una acción o situación que ocurre mientras un programa está funcionando y que puede provocar que se ejecute determinado código. En una página web, puede ser una acción realizada por el usuario o algo que ocurre en el navegador.

Ejemplo:

Si tenemos un botón en una página, podemos hacer que al hacer clic sobre él se muestre un mensaje:

boton.addEventListener("click", function() {
  console.log("Hiciste clic");
});

El clic del usuario es el evento que provoca que se ejecute la función.

Fuente:
MDN Web Docs. (2026). Introduction to events. Mozilla.
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Events
