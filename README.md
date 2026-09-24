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
```
const PI = 3.1416
```
Fuente:
MDN Web Docs. (2026). JavaScript language overview. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Language_overview

---

## 8. Tipo de dato

El tipo de dato indica qué clase de información representa un valor. Dependiendo del lenguaje, existen diferentes tipos, como números, texto o valores que representan verdadero o falso.

**Ejemplo:**
```
let edad = 17
let nombre = "Esmeralda"
let aprobado = true
```
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

---

## 18. Objeto

Un objeto es una estructura que permite reunir diferentes datos relacionados utilizando propiedades. Cada propiedad tiene un nombre y un valor, por lo que resulta útil para representar cosas o elementos con varias características.

**Ejemplo:**
```
let alumno = {
  nombre: "Esmeralda",
  edad: 17,
  semestre: 6
};
```
El objeto alumno reúne información relacionada con una misma persona.

Fuente:
MDN Web Docs. (2026). Working with objects. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects
---

## 19. Método

Un método es una función que está asociada a un objeto y que permite realizar una acción relacionada con ese objeto.

**Ejemplo:**
```
let nombre = "Juanito";
nombre.toUpperCase();
```
toUpperCase() es un método que puede utilizarse con una cadena de texto para convertir sus letras a mayúsculas.

Fuente:
MDN Web Docs. (2026). Working with objects. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_objects

---

## 20. Evento

Un evento es una acción o situación que ocurre mientras un programa está funcionando y que puede provocar que se ejecute determinado código. En una página web, puede ser una acción realizada por el usuario o algo que ocurre en el navegador.

**Ejemplo:**

Si tenemos un botón en una página, podemos hacer que al hacer clic sobre él se muestre un mensaje:
```
boton.addEventListener("click", function() {
  console.log("Hiciste clic");
});
```
El clic del usuario es el evento que provoca que se ejecute la función.

Fuente:
MDN Web Docs. (2026). Introduction to events. Mozilla.
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting/Events

---

# Herramientas para programar
## 21. Compilador

Es un programa que agarra tu código completo, escrito en un lenguaje como C o Java, y lo traduce de una sola vez a lenguaje de máquina (puros ceros y unos que entiende el procesador). Genera un archivo nuevo, ejecutable, y ya no necesita el código original para correr. Si hay un error de sintaxis en cualquier parte, ni siquiera te deja terminar de compilar, así que te obliga a corregir todo antes de ver resultados.

**Ejemplo:**

Escribes un programa en C, lo compilas con GCC y obtienes un .exe que corre solo, sin que Windows sepa que viene de C.

Fuente:
Pressman, R. S. (2010). Ingeniería del software: un enfoque práctico. México: McGraw-Hill.

---

## 22. Intérprete

En vez de traducir todo de golpe, va leyendo y ejecutando tu código línea por línea, al momento. No genera un archivo aparte: cada vez que quieres correr el programa, se vuelve a interpretar desde cero. Esto lo hace más lento que un compilado, pero también más flexible para probar cosas rápido.

**Ejemplo:**

Abres la terminal de Python, escribes print("hola") y le das enter, y ahí mismo ves el resultado sin compilar nada.

Fuente:
Pressman, R. S. (2010). Ingeniería del software: un enfoque práctico. México: McGraw-Hill.

---

## 23. Depurador (debugger)

Es la herramienta que usas cuando tu programa no hace lo que debería y no encuentras por qué. Te deja pausar la ejecución en una línea exacta (un "breakpoint"), y desde ahí revisas qué valor tiene cada variable, ejecutas paso a paso, y vas viendo en qué momento las cosas van mal. Ahorra muchísimo tiempo comparado con solo adivinar.

**Ejemplo:**

Tu programa calcula mal un total; pones un breakpoint antes del cálculo y descubres que una variable llegó en 0 en lugar de 100.

Fuente:
Sommerville, I. (2011). Ingeniería de software. España: Pearson Addison Wesley.

---

## 24. IDE

Significa "entorno de desarrollo integrado" y es básicamente una caja de herramientas completa para programar: editor de texto, compilador o intérprete, depurador, autocompletado y hasta control de versiones, todo en una sola aplicación. La idea es que no tengas que andar saltando entre programas distintos.

**Ejemplo:**

Android Studio trae todo lo necesario para hacer, probar y depurar una app de Android sin salir del programa.

Fuente:
Sommerville, I. (2011). Ingeniería de software. España: Pearson Addison Wesley.

---

## 25. Editor de código

Es más sencillo que un IDE: básicamente un bloc de notas mejorado, pensado para escribir código. Colorea la sintaxis para que se lea más fácil, te sugiere autocompletados y marca errores obvios, pero no trae compilador ni depurador integrados por defecto.

**Ejemplo:**

VS Code o Sublime Text; aunque VS Code con extensiones puede terminar pareciéndose bastante a un IDE.

Fuente:
Documentación oficial de Visual Studio Code.
https://code.visualstudio.com/docs

---


## 26. Biblioteca (library)

Es un conjunto de funciones y herramientas que alguien más ya programó, para que tú no tengas que reinventar la rueda. Tú decides cuándo y cómo usarla dentro de tu propio código: el control lo tienes tú, la biblioteca solo responde cuando la llamas.

**Ejemplo:**

Usas la librería math de Python para calcular una raíz cuadrada con math.sqrt() en vez de programar la fórmula tú mismo.

Fuente:
Documentación oficial de Python.
https://docs.python.org/

---

## 27. Framework

Se parece a una biblioteca, pero funciona al revés: en vez de que tú llames a sus funciones, es el framework el que define la estructura general del proyecto y llama a tu código en los momentos que él decide. Tú te acomodas a sus reglas y solo rellenas las partes que te toca.

**Ejemplo:**

React te obliga a organizar tu página en "componentes" y a seguir su forma de manejar el estado; tú no armas la estructura desde cero, la sigues.

Fuente:
Documentación oficial de React.
https://react.dev/

---

## 28. API

Son las reglas que definen cómo dos programas pueden comunicarse entre sí sin que uno tenga que saber cómo está hecho el otro por dentro. Es como el menú de un restaurante: pides algo específico y te lo entregan, sin necesidad de meterte a la cocina a ver cómo se preparó.

**Ejemplo:**

Tu app le pide el clima a la API de OpenWeather mandando una ciudad, y recibe de vuelta la temperatura en un formato como JSON.

Fuente:
MDN Web Docs.
https://developer.mozilla.org/

---

Guardar y versionar
## 29. Repositorio

Es la carpeta de tu proyecto, pero con superpoderes: además de los archivos actuales, guarda todo el historial de cambios que ha tenido desde que empezaste. Puede estar en tu computadora (local) o subido a internet (remoto).

**Ejemplo:**

El repositorio de tu página web tiene el HTML, el CSS, el JavaScript, y también recuerda cómo se veían hace tres semanas.

Fuente:
Documentación oficial de Git.
https://git-scm.com/doc

---

## 30. Control de versiones

Es el sistema que se encarga de llevar ese historial: registra qué cambió, quién lo cambió y cuándo, y te permite regresar a una versión anterior si algo se rompió. Piénsalo como un "deshacer" gigante que funciona incluso días o semanas después.

**Ejemplo:**

Metes un cambio que tira el botón de login y, en vez de entrar en pánico, regresas el proyecto a como estaba el día anterior.

Fuente:
Piattini, M. G. (2017). Calidad de sistemas informáticos. México: Alfaomega.

---

## 31. Git

Es el sistema de control de versiones más usado en el mundo. Corre en tu propia computadora, así que no necesitas internet para llevar el historial de tu proyecto; internet solo hace falta si quieres compartirlo o respaldarlo en otro lado.

**Ejemplo:**

Después de terminar una función, escribes:
```
git commit -m "arreglo del login"
```
para guardar ese avance con su explicación.

Fuente:
Documentación oficial de Git.
https://git-scm.com/doc

## 32. GitHub

Es una plataforma en internet donde subes tus repositorios de Git para tenerlos respaldados en la nube y poder trabajar en equipo con otras personas. Ojo: Git es la herramienta que usas en tu compu, GitHub es el sitio web donde la guardas y compartes.

**Ejemplo:**

Subes tu proyecto escolar a GitHub y le mandas el link a tu compañero para que lo descargue y te ayude a programar.

Fuente:
GitHub Docs.
https://docs.github.com/

## 33. Rama (branch)

Es una copia paralela de tu proyecto que te deja experimentar o desarrollar algo nuevo sin arriesgar la versión que ya funciona bien. Cuando terminas de probar y todo sale bien, puedes juntar esa rama con la principal.

**Ejemplo:**

Creas una rama llamada modo-oscuro para trabajar ese detalle, mientras la rama principal del proyecto sigue intacta y funcionando.

Fuente:
Documentación oficial de Git.
https://git-scm.com/doc

---

## 34. Commit

Es básicamente una "foto" de tu proyecto en un momento específico, acompañada de un mensaje corto que explica qué se hizo en ese cambio. Entre más claros sean tus mensajes de commit, más fácil es entender después qué pasó en el proyecto.

**Ejemplo:**

Haces un commit con el mensaje "agregué el botón de registro" justo después de terminar esa parte.

Fuente:
Documentación oficial de Git.
https://git-scm.com/doc

---

## 35. Merge

Es el proceso de unir dos ramas para juntar el trabajo que se hizo por separado en cada una. La mayoría de las veces se junta sin problema, pero si dos personas cambiaron la misma línea de código, aparece un "conflicto" que hay que resolver a mano, decidiendo qué versión se queda.

**Ejemplo:**

Terminas de trabajar en la rama modo-oscuro y la fusionas (merge) con la rama principal para que ese cambio quede incluido en el proyecto final.

Fuente:
GitHub Docs.
https://docs.github.com/

---

Cómo se ejecuta el código
## 36. Callback

Es una función que le pasas como argumento a otra función, para que esta la ejecute después, normalmente cuando termine algo o cuando ocurra un evento. Es una forma de decirle al programa "cuando pase esto, entonces haz aquello".

**Ejemplo:**

boton.addEventListener("click", saludar)

La función saludar no se ejecuta de inmediato, sino hasta que alguien realmente hace clic en el botón.

Fuente:
MDN Web Docs.
https://developer.mozilla.org/

---

## 37. Programación síncrona

Es cuando las instrucciones se ejecutan una tras otra, en orden, y ninguna tarea empieza hasta que la anterior haya terminado por completo. Si una tarea tarda mucho (como descargar un archivo grande), todo el programa se queda esperando y no puede hacer nada más mientras tanto.

**Ejemplo:**

El programa se congela por completo mientras espera a que termine de descargar un archivo pesado de internet.

Fuente:
MDN Web Docs.
https://developer.mozilla.org/

---

## 38. Programación asíncrona

Aquí, en cambio, cuando una tarea va a tardar, el programa la manda a hacer "en segundo plano" y sigue ejecutando otras cosas mientras tanto; cuando la tarea tardada por fin termina, el programa se entera y reacciona (muchas veces usando un callback). Esto evita que la aplicación se quede congelada esperando.

**Ejemplo:**

Una app de fotos sigue dejándote hacer scroll mientras, al mismo tiempo, va cargando imágenes desde internet en segundo plano.

Fuente:
MDN Web Docs.
https://developer.mozilla.org/

---

Lenguajes
## 39. JavaScript

Es un lenguaje de programación interpretado que originalmente se creó para darle interactividad a las páginas web: animaciones, validaciones de formularios, botones que reaccionan al hacer clic, etc. Con el tiempo también se empezó a usar fuera del navegador, por ejemplo en servidores, gracias a herramientas como Node.js.

**Ejemplo:**

Validar con JavaScript que un usuario haya escrito bien su correo antes de dejarlo enviar un formulario.

Fuente:
MDN Web Docs. (2026). JavaScript. Mozilla.
https://developer.mozilla.org/en-US/docs/Web/JavaScript

---

## 40. TypeScript

Es básicamente JavaScript, pero con una capa extra que obliga (o al menos permite) especificar qué tipo de dato es cada variable: número, texto, booleano, etc. Esto ayuda a detectar errores desde que estás escribiendo el código, antes de siquiera ejecutarlo. Al final, el código en TypeScript se convierte ("se compila") a JavaScript normal para poder correr.

**Ejemplo:**
```
let edad: number = 18;
```
Si más adelante intentas meterle el texto "dieciocho", TypeScript te marca el error de inmediato, sin esperar a que el programa falle en producción.

Fuente:
Documentación oficial de TypeScript.
https://www.typescriptlang.org/

---
