## Navegación básica

Toda la navegación en vi se hace desde modo normal (sin estar en modo inserción).

## Movimiento por caracteres y líneas
Comando	Qué hace
h	Mueve el cursor a la izquierda
l	Mueve el cursor a la derecha
j	Mueve el cursor una línea hacia abajo
k	Mueve el cursor una línea hacia arriba

Estas 4 teclas reemplazan a las flechas del teclado (útil en terminales o teclados sin flechas).

## Saltos más grandes
Comando	Qué hace
w	Salta al inicio de la siguiente palabra
b	Salta al inicio de la palabra anterior
0	Va al inicio de la línea actual
$	Va al final de la línea actual
gg	Va al inicio del archivo
G	Va al final del archivo
:N	Va directo a la línea número N (ej: :25)

## Combinando número + movimiento

Casi todos los comandos de movimiento permiten colocar un número antes para repetir la acción varias veces. Por ejemplo, 8l mueve el cursor 8 caracteres hacia la derecha, mientras que 3j baja 3 líneas. Esto es útil cuando se necesita desplazarse rápidamente por un archivo.


