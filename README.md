Mario, una de las franquicias más conocidas, posiblemente el videojuego más conocido de todo el mundo. Recientemente estrenó una pésima excelente película de esta franquicia, rompiendo varios récords de taquilla. Obviamente, con semejante torta de plata, se dieron cuenta de que la franquicia puede recaudar en otros formatos multimedia, por lo que nos pidieron que hiciéramos un parcial temático con el fin de aumentar las ventas.
Como todos sabemos, Mario es un plomero, una noble profesión que nos salva las papas del fuego cuando se nos rompen los caños de la casa y no tenemos ni la más pálida idea de por dónde arrancar. 
De los plomeros conocemos su nombre, la caja de herramientas que llevan, el historial de reparaciones que han hecho y el dinero que llevan encima (¡no trabajan gratis!). 
Hay unas cuantas herramientas que un plomero puede tener encima, y de cada una conocemos su denominación (nombre de la herramienta), su precio y el material de su empuñadura, que puede ser hierro, madera, goma o plástico.

Se pide, usando los conceptos del paradigma funcional:
Modelar a los plomeros y sus herramientas.
Mario, un plomero que tiene $1200, no hizo ninguna reparación hasta ahora y en su caja de herramientas lleva una llave inglesa con mango de hierro que tiene un precio de $200 y un martillo con empuñadura de madera que le salió $20.
Wario, tiene 50 centavos encima, no hizo reparaciones, lleva infinitas llaves francesas, obviamente de hierro, la primera le salió un peso, pero cada una que compraba le salía un peso más cara. La inflación lo está matando. 

Saber si un plomero:

- Tiene una herramienta con cierta denominación.

- Es malvado: se cumple si su nombre empieza con Wa.

- Puede comprar una herramienta: esto sucede si tiene el dinero suficiente para pagar el precio de la misma.

- Saber si una herramienta es buena, cumpliendose solamente si tiene empuñadura de hierro que sale más de $10000 o es un martillo con mango de madera o goma.
  
Todo plomero necesita comprar una herramienta, cuando lo hace paga su precio y agrega la herramienta a las suyas. Solo sucede si puede pagarlo.

Hay un sinfín de reparaciones que los plomeros deben resolver. Cada una de ellas goza de una descripción del problema a reparar y un requerimiento que varía dependiendo de la reparación. 

Por ejemplo, una filtración de agua requiere que un plomero tenga una llave inglesa en su caja de herramientas.

Modelar las reparaciones y la filtración de agua.

Saber si una reparación es difícil: esto ocurre cuando su descripción es complicada, es decir que tiene más de 100 caracteres y además es un grito, es decir está escrito totalmente en mayúsculas.

Saber el presupuesto de una reparación, el cual se calcula como el 300% de la longitud de su descripción (por eso es importante describir los problemas de manera sencilla).

Hacer que un plomero haga una reparación. Si no puede resolverla te cobra $100 la visita. Si puede hacerla, cobra el dinero por el presupuesto de la misma y agrega esa reparación a su historial de reparaciones, además de:
- Si el plomero es malvado, le roba al cliente un destornillador con mango de plástico, claramente su precio es nulo.
- Si no es malvado y la reparación es difícil, pierde todas sus herramientas buenas.
- Si no es malvado ni es difícil la reparación, sólo se olvida la primera de sus herramientas.
Un plomero puede hacer una reparación si cumple su requerimiento o es un plomero malvado con un martillo.

Nintendo, pese a ser una empresa de consolas y juegos, gana millones de dólares con su red de plomeros. Cada plomero realiza varias reparaciones en un día. Necesitamos saber cómo afecta a un plomero una jornada de trabajo. Bajan línea desde Nintendo que no usemos recursividad.

Nintendo beneficia a sus plomeros según ciertos criterios, es por eso que necesita saber, dado un conjunto de reparaciones a realizar en una jornada laboral, cuál de todos sus empleados es:

El empleado más reparador: El plomero que más reparaciones tiene en su historial una vez realizada su jornada laboral.

El empleado más adinerado: El plomero que más dinero tiene encima una vez realizada su jornada laboral.

El empleado que más invirtió: El plomero que más plata invertida tiene entre las herramientas que le quedaron una vez realizada su jornada laboral.

