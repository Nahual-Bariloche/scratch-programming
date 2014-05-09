scratch-programming
===================

Introducción a conceptos básicos de programación (flujo de control, variables, etc. ) usando ejercicios de [scratch](http://scratch.mit.edu)

## Introducción:

El editor de scratch está en http://scratch.mit.edu/projects/editor/

Se pueden guardar los programas creados desde: Archivo => Descargar a tu computadora

Se pueden subir los programas guardados desde: Archivo => Subir de tu computadora

Los bloques son el equivalente a las instrucciones de código y se encuentran en la parte central de la pantalla, y están agrupados por su tipo (ej: Movimiento, Eventos, Apariencia, etc. ). Para poder armar un programa debemos arrastrar los bloques hacia la parte izquierda de la pantalla.

Los bloques tienen secciones de "encastre", si un bloque puede ir a continuación o "adentro" de otro, entonces sus formas coinciden, de forma similar a un rompecabezas.

Para poder correr (ejecutar) el programa se debe usar alguno de los bloques de la solapa "Eventos", por ejemplo podemos utilizar el bloque "al presionar la tecla espacio" y correr nuestro programas presionando dicha tecla.

En algunos casos es necesario usar el bloque "Esperar (1) segundos" de la solapa control, o los bloques que se realizan por un determinado tiempo, de lo contrario la acción se realiza tan rápidamente que no se puede visualizar.



##Ejercicios


La idea es que se presenten los ejercicios a los alumnos y ellos traten de resolverlos por su cuenta, únicamente interviniendo el profesor en el caso de que se traben. Las soluciones son sólo para orientar al profesor y de ninguna manera la única solución posible al ejercicio.



###Ejercicio "La vuelta al mundo"


Hacer que el personaje de scratch camine en círculo hasta volver al punto inicial

Tip: Como cada vez que corremos el programa no se vuelve al estado inicial para este ejericio es mejor setear la dirección y la posición inicial del personaje de scratch como primer paso. Para eso utilizamos los bloques "apuntar en dirección (90)" e "ir a x: (-50) y: (50)".

Conceptos introducido: iteración (for)

Solución: "La vuelta al mundo.sb2"



###Ejercicio "Ayyy"


Hacer que al poner el mouse sobre el personaje de scratch diga "Ayyyy"


Conceptos introducidos:  if, else, iteración infinita (while true)

Solución: "Ayyy.sb2"



###Ejercicio "Hola Juan"


Hacer que el personaje de scratch nos pregunte el nombre y luego que diga "Hola" seguido de nuestro nombre.


Conceptos introducidos: variable, input del usuario

Solución: "hola Juan.sb2"



###Ejercicio "Jugar a las escondidas"


Hacer que el personaje de scratch cuente hasta 10 y luego diga "Punto y coma el que no se escondió se embroma"



Concepto introducido: iteración de 10 pasos (for), que el alumno se de cuenta de la ventaja de usar una variable y un ciclo en vez de usar 10 instrucciones

Solución: "jugar a la escondida.sb2"



###Ejercicio "Adivinanza"


Hacer que el personaje piense un número del 1 al 10 y nos pida a nosotros que lo adivinemos y nos diga si acertamos o no, y en el caso de que no adivinemos que nos diga cual es el número en el que estaba pensando.


Tip: Usar el bloque "número al azar entre (1) y (10)" de la solapa operadores para generar un número aleatorio.


Conceptos introducidos: variable, número aleatorio, input del usuario

Solución: "adivinar numero.sb2"



###Ejercicio "Atrapame"


Hacer que el personaje de scratch se mueva aleatoriamente. Al poner el mouse sobre el mismo que diga "Ayyyy"


Tip: Usar el bloque "número al azar entre () y ()" de la solapa operadores, para generar el movimiento aleatorio.

Solución: "atrapame.sb2"
