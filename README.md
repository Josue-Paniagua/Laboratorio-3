# Laboratorio-3
1. Análisis del Programa
*Variables Locales vs Variables Globales*

o	¿Qué datos deben ser accesibles en todo el programa?

•	Los datos que deberían de ser accesibles en todo el programa son aquellos que este no cambia su valor que seria una contante por ejemplo o alguno que otro tipo fijo como tasas o IVA ya que esos datos se van a usar de la misma manera en todos los ámbitos.

o	¿Qué datos solo son necesarios dentro de una función específica?

•	Unos de los datos que son solamente necesarios dentro de una función podrían ser aquellas que solo tiene relevancia dentro de un bloque de código en especifico o la que se utilice en alguna comparación lógica. 


2. MODULARIZACION

Definir Variables Locales y Globales
o	¿Qué datos necesitan ser compartidos entre múltiples funciones?

•	Las configuraciones generales como tasas de impuestos o valores que ya tienen un dato predeterminado o también las listas de ya
sea usuarios en el sistema o del registro que se desee contar o almacenar para no hacer uso de muchos listas con almacenamiento de estos.

o ¿Qué datos solo son relevantes dentro de una función específica?
•	Estos pueden ser las comparaciones lógicas como lo es el if-else, el switch, el while o hasta el for ya que esta va depender de
cada función y se va adaptar dependiendo de lo que el usuario quiera tan así como los parámetro para una función que seria un poco 
lo mismo que lo antes mencionado .

3.Preguntas Guía

1.	¿Qué ventajas tiene dividir el código en funciones?

o	Considerando que las funciones es un modo de trabajar de una manera ordenada ya que este nos permite clasificar muchas líneas de
código y separar varias funciones podría ayudar a evitar errores de compilación del código o de alguna variable y también considerando
que para el lector es más cómodo el ver donde esta cada parte de cierto código.

2.	¿Por qué es importante limitar el uso de variables globales?
o	En un código largo una función modificada poder mover la variable global lo que dificultaría encontrar los cambio que a esta se 
le hagan también el uso de memoria ya que se sabe que estás siguen en función durante todo el programa y eso roba memoria sin necesidad.

3.	¿Cómo se puede mejorar la legibilidad del código?
o	AL momento de declarar variables utilizar un modo de lenguaje en el cual sea legible para todo el mundo y mucho menos si el código 
será compartido o es en grupo en pocas palabras no inventar palabras o que solo nosotros las conozcamos y que esta refleje su propósito,
otra cosa que puede ayudar es agregar comentarios con el // en el código así se hará mas fácil para el lector y hasta a nosotros mismo que
estamos haciendo en esa parte del código. 
