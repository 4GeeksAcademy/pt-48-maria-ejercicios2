# DIFERENCIAS ENTRE `VAR` Y `LET`

## La variable `var` permite ser creada varias veces en un mismo archivo:

`var` saludar = "buenos días";
console.log(saludar);
**Esto nos devolverá** > buenos días

Si creas otra variable llamada saludar sea intencionalmente o sólo porque se te olvidó que ya existia y le asignas un valor diferente, no hay inconveniente, el código corre sin problemas.
Solo se guarda al final el ultimo valor:

`var` saludar = "buenos días";
`var` saludar = "buenas tardes";
console.log(saludar);
**Esto nos devolverá** > buenas tardes

## Con `let` no ocurre lo mismo, no permite que dos variables tengan el mismo nombre:

`let` saludar = "buenos días";
`let` saludar = "buenas tardes";
**Esto nos devolverá un error** >:exclamation: Identifier "saludar" has already been declared

:sparkles: PODEMOS CAMBIAR EL VALOR DE LA VARIABLE SIN NECESIDAD DE CREARLA NUEVAMENTE SOLO ESCRIBIENDO EL NOMBRE DE LA VARIABLE SIN ANTEPONER VAR O LET, SIENDO SIEMPRE EL CONTENIDO DEL MISMO TIPO QUE EL ANTERIOR:

`let` saludar = "buenos días";
saludar = "buenas tardes";
**Esto nos devolverá** > buenas tardes

## Cuando una variable `var` se encuentra dentro de un bloque de función o condicional puede ser llamado por fuera de ese bloque ( fuera de { } )

`var` día = "true";  
`if`(día){
`var` saludar = "buenos días";
}
console.log(saludar);
**Esto nos devolverá** > buenos días

## No sucede lo mismo con `let` que es una variable que trabaja en bloque:

`var` día = "true";  
`if`(día){
`let` saludar = "buenos días";
}
console.log(saludar);
**Esto nos devolverá** > Uncaught ReferenceError: saludar is not defined
**Al ser definida dentro de un bloque (las llaves) solo existirá dentro de ese bloque.**

`var` día = "true";  
`if`(día){
`let` saludar = "buenos días";
console.log(saludar);
}
**Esto nos devolverá** > buenos días
