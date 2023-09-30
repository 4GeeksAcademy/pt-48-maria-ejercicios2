# COMILLAS DOBLES / COMILLAS SIMPLES

En programación, las comillas simples (') y las comillas dobles (") son utilizadas para definir cadenas de caracteres (strings). Ambas se utilizan para representar texto, pero hay algunas diferencias sutiles entre ellas. Aquí tienes las diferencias clave con ejemplos en JavaScript:

## Comillas Simples (')

Se utilizan para definir cadenas de caracteres.

Pueden incluir comillas dobles dentro de la cadena sin problemas.

A menudo se usan cuando se necesita incluir comillas dobles en la cadena.

    let cadenaConComillasSimples = 'Esta es una cadena con comillas simples.';

    console.log(cadenaConComillasSimples);

##### DEVUELVE: Esta es una cadena con comillas simples.

    let cadenaConComillasDobles = 'puedes usar "comillas dobles" dentro de comillas simples.';

    console.log(cadenaConComillasDobles);

##### DEVUELVE: puedes usar "comillas dobles" dentro de comillas simples.

## Comillas Dobles (")

También se utilizan para definir cadenas de caracteres.

Pueden incluir comillas simples dentro de la cadena sin problemas.

A menudo se usan cuando se necesita incluir comillas simples en la cadena.

    let cadenaConComillasSimples = "puedes usar 'comillas simples' dentro de comillas dobles.";

    console.log(cadenaConComillasSimples);

##### DEVUELVE: puedes usar 'comillas simples' dentro de comillas dobles.

    let cadenaConComillasDobles = "Esta es una cadena con comillas dobles.";

    console.log(cadenaConComillasDobles);

##### DEVUELVE: Esta es una cadena con comillas dobles.

## Interpolación de Variables:

En algunos lenguajes, como JavaScript moderno, puedes incluir variables dentro de cadenas de caracteres utilizando comillas inversas (backticks) (``) para realizar interpolación de variables. Esto no es posible con comillas simples o dobles.

    let nombre = "Juan";

    let edad = 30;

    let mensaje = `Hola, mi nombre es ${nombre} y tengo ${edad} años.`;

    console.log(memsaje);

##### DEVUELVE: Hola, mi nombre es Juan y tengo 30 años.

## Escape de Caracteres Especiales:

Ambas comillas simples y dobles permiten escapar caracteres especiales utilizando la barra invertida (\). Por ejemplo, para incluir una comilla dentro de una cadena encerrada en comillas del mismo tipo, puedes hacerlo de la siguiente manera:

     let cadenaConComillaDentro = "Ella dijo, \"Hola.\"";

        console.log(cadenaConComillaDentro);

##### DEVUELVE: Ella dijo, "Hola."

    let cadenaConComillaDentro2 = 'Él dijo, \'Hola.\'';

    console.log(cadenaConComillaDentro2);

##### DEVUELVE: Él dijo, 'Hola.'
