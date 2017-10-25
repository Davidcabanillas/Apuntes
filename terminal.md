# Terminal

## Redirecciones

flecha mayor o menor que se usa para redireccion
gt=greater than= mayor que
lt= less than
&gt; : redirecion de salida. Crea un fichero nuevo.

&gt;&gt; : doble redireccion de S. Anexa a un fichero.

&lt;: Redirigir la entrada.

&lt;&lt;: here document 

&lt;&lt;&lt;: here string
2>: redirigir stderr
|: Pipe, tuberia (usa en secreto un fichero anonimo)

Redireccion de copia.

## Metacaracteres
- $: dime el valor de una variable 
- ~: mi directorio HOME
- .: Directorio actual
- ..: directorio de arriba
- " ": es un espacio, sirve para partir palabras
- "\ ": la barra lo convierte en un espacio normal
- "\\": Secuencia de escape ==> Kriptonita de los metacaracteres
- -- (a veces el guion representa al fichero que corresponde con la terminal) 
- "comillas": Quitan el poder a casi todos los meta, menos a $
- ' ': Quita el poder a todos los meta
- *: cualquier parametro
	- *b*: todo lo que contenga una b
	\*: cualquier secuencia de caracteres
- ?: cualquier caracter
- []: conjunto de seleccion
- {}: combinacion de secuencia
- $#: convierte en comentario lo que vaya tras el 
- $?: variable que contiene el ultimo comando ejecutado
- $: dikme el valor de una variable
- \: ejecutar un comando y sustituir por el resultado
- &: Ejecutar una cosa en segundo plano

## Variable
#: Cantidad de parametros

## Otros

- #! shebang: interprete con el que hay que ejecutar el archivo
- !!: El ultimo comando
- !*: Los ultimos parámetros

### Operadores lógicos
- &&: AND
- ||: OR
- !: NOT

