## ¿Qué es la programación imperativa?

un sistema imperativo controla una máquina o mecanismo que ayuda a producir el resultado deseado. Normalmente, los usuarios expresan sus deseos sobre el resultado final en una especificación y un programador crea un sistema para producir ese resultado”

## ¿Qué es la programación declarativa?

La programación declarativa es un paradigma de programación que enfatiza la expresión del resultado o resultado deseado, en lugar de un procedimiento paso a paso para obtenerlo. Se centra en describir lo que debería lograr un programa, en lugar de detallar explícitamente cómo debería lograr esos objetivos.

### Ventajas de la programación imperativa

Más fácil de entender: principalmente, los lenguajes son relativamente sencillos de aprender, pues el código se lee con una instrucción paso a paso. Es por esto que los programadores aprenden el lenguaje imperativo como parte de su entrenamiento.

Su ejecución no requiere esfuerzo: en los funcionamientos diarios, el personal puede mantener y optimizar los programas sin demasiado esfuerzo. Sin embargo, esto aplica solo si el mantenimiento y la optimización no está relacionado a una sola persona.

Son de buena legibilidad: la legibilidad en la programación imperativa es un factor decisivo al momento de usarla. Este aspecto permite que, el mantenimiento y la optimización de las aplicaciones no dependan exclusivamente de una persona, sino que los puede llevar a cabo cualquier colaborador, sin necesidad de que este haya escrito el código desde cero.

### Desventajas de la programación imperativa

Un código extenso: esta programación se basa en el orden del programa, por lo que en algunos casos, es difícil organizarlo, por ende, requiere más código para realizar tareas simples, lo que significa que para programas más complejos, el código se vuelve muy voluminoso y pierde su claridad debido a su tamaño.

Modificación puede traer problemas: al hacer el proceso de modificación del código, es decir, agregar características u optimizarlo por ejemplo, el riesgo de errores es alto.

En conclusión, a diferencia de la programación declarativa, en la que se puede usar métodos para implementar extensiones de forma separada, en la programación imperativa la implementación produce errores no deseados, lo que causa que la optimización sea más difícil.

### Ventajas de la programación declarativa

Cuando pensamos en los beneficios de programar en forma declarativa, en general se empieza pensando en las ventajas propias del lenguaje a utilizar. Por ejemplo, si se está usando un lenguaje funcional, la principal ventaja es que al lidiar puramente con funciones, no necesitamos preocuparnos por el estado de la información, ya que los datos sean inmutables. Por otro lado, en el caso de los lenguajes basado en reglas, los programas son más claros y entendibles incluso por los usuarios.

A pesar de todo esto, la ventaja más importante de la programación declarativa consiste en que el indicar a la computadora“qué” tarea es la que tiene que hacer, en lugar de “cómo” hacerla nos protege de cambios en el contexto tecnológico. En ese sentido, el qué perdura mucho más que el cómo.

##### EJEMPLO:

int suma = 0;  
 for (int i = 1 to 100)  
 suma += i;
return suma;

Una solución declarativa podría ser simplemente:
suma = Sum(1, 100)
