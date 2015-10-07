**1. ¿Podés nombrar dos paradigmas de programación importantes para los desarrolladores de aplicaciones JavaScript?**

   JavaScript es un lenguaje multi-paradigma, soporta programación imperativa/procedural en conjunto con OOP 
(Programación Orientada a Objetos) y programación funcional. JavaScript soporta programación orientada a objetos con herencia de prototipos.

   **Es bueno saber:**

      * Herencia de prototipos (también: prototipos, OLOO).
      * La programación funcional (también: closures, funciones de primera clase, lambdas).

   **Alertas:**

      * Ni idea de lo que es un paradigma, ninguna mención de oo de prototipos o de programación funcional.

   **Aprende más:**
   
      * [Los dos pilares de JavaScript Parte 1 - OO Prototipado](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)
      * [Los dos pilares de JavaScript Parte 2 - Programación Funcional](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4)
	
**2. ¿Qué es la programación funcional?**

   La programación funcional produce programas por la composición de funciones matemáticas y evita el estado compartido y los datos mutables. Lisp (especificado en 1958) fue uno de los primeros lenguajes en soportar programación funcional y fue fuertemente inspirado en el cálculo lambda. Lisp y muchos lenguajes de la familia Lisp todavía son de uso común hoy en día. La programación funcional es un concepto esencial en JavaScript (uno de los dos pilares de JavaScript). Varias utilidades funcionales comunes se añadieron a JavaScript en ES5.
	
   **Es bueno saber:**
	
      * Funciones puras / función de pureza.
      * Evitar los efectos secundarios.
      * Función de composición simple.
      * Ejemplos de lenguajes funcionales: Lisp, ML, Haskell, Erlang, Clojure, Elm, F Sharp, OCaml, etc ...
      * La mención de características que apoyan la FP: funciones de primera clase, funciones de orden superior, funciones como argumentos / valores.
		
   **Alertas:**
	
      * No hay mención de funciones puras / evitando efectos secundarios.
      * Incapaz de dar ejemplos de lenguajes de programación funcional.
      * No es posible identificar las características de JavaScript que permiten a FP.	

   **Aprende más:**
	
     * [Los dos pilares de JavaScript Parte 2](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4)
     * [El Dao de inmutabilidad](https://medium.com/javascript-scene/the-dao-of-immutability-9f91a70c88cd)
     * [La Más Adecuada Guía del profesor Frisby para la Programación Funcional](https://github.com/MostlyAdequate/mostly-adequate-guide)
     * [La Escuela de Música de Haskell](http://haskell.cs.yale.edu/wp-content/uploads/2015/03/HSoM.pdf)	

**3. ¿Cuál es la diferencia entre la herencia clásica y herencia de prototipos?**

   **Herencia de Clase:** las instancias heredan de las clases (como un modelo - una descripción de la clase), y crear relaciones de sub-clase: la taxonomía de clase jerárquica. 
	Las instancias se suelen crear a través de funciones constructoras con la palabra clave "new". La herencia de clases puede o no utilizar la palabra clave "class" de ES6.

   **Herencia de prototipos:** las instancias heredan directamente de otros objetos. Las instancias suelen ser instanciaciadas a través de las funciones factory o 'Object.create ()'. 
	Las instancias pueden estar compuestas de muchos objetos diferentes lo que permite que la herencia selectiva sea sencilla.

    En JavaScript, la herencia de prototipos es simple y más flexible que la herencia de clase.

   **Es bueno saber:**
	
      * Clases: crean acoplamiento apretado o jerarquías / taxonomías.
      * Prototipos: menciones de la herencia por concatenación, la delegación de prototipo, la herencia funcional, composición de objetos.
		
   **Alertas:**
	
      * Sin preferencia por herencia de prototipos y composición sobre la herencia de clases.
		
   **Aprende más:**
	
      * [Los dos pilares de JavaScript Parte 1 - OO Prototipado](https://medium.com/javascript-scene/the-two-pillars-of-javascript-ee6f3281e7f3)
      * [Conceptos erróneos comunes acerca de la herencia en JavaScript](https://medium.com/javascript-scene/common-misconceptions-about-inheritance-in-javascript-d5d9bab29b0a)		

**4. ¿Cuáles son los pros y los contras de la programación funcional vs la programación orientada a objetos?**

	**OOP Pros:** Es fácil entender el concepto básico de objetos y fácil de interpretar el significado de las llamadas a métodos. 
	OOP tiende a utilizar un estilo imperativo en lugar de un estilo declarativo, el cuál se lee como un conjunto de instrucciones 
	bien definidas para que la computadora lo realice.

	**OOP Contras:** OOP normalmente depende del estado compartido. Los objetos y los comportamientos adjuntarse en la misma entidad, a la cual se puede acceder de forma aleatoria 
	por cualquier número de funciones en un orden no determinista, que puede llevar a comportamientos indeseables, tales como condiciones de carrera.
	
	**FP Pros:** Usando el paradigma funcional, los programadores evitan cualquier estado compartido o efectos secundarios, lo que elimina los errores causados ​​por múltiples funciones que compiten por los mismos recursos. 
	Con características tales como la disponibilidad de estilo point-free (aka programación tácita), las funciones tienden a ser radicalmente simplificadas 
	y fácilmente recompuestas para un código reutilizable más general en comparación con programación orientada a objetos.	
