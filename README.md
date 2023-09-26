# get_next_line - Leer Líneas de un File Descriptor

Este proyecto tiene como objetivo implementar la función `get_next_line` en C, que permite leer líneas de texto de un file descriptor (archivo o entrada estándar) de manera eficiente y dinámica.

## Descripción

La función `get_next_line` es una herramienta útil para leer líneas de texto de un archivo o la entrada estándar línea por línea. Estas son algunas de las características clave de esta función:

- Llamando repetidamente a `get_next_line` en un bucle permite leer el contenido del archivo línea por línea hasta el final.
- La función devuelve la línea que acaba de leer y la almacena en un buffer.
- Si no hay nada más que leer o si ocurre un error, la función devuelve NULL.
- La línea devuelta siempre termina con el carácter `\n` (salto de línea), excepto si se llega al final del archivo y este no termina con un `\n`.
