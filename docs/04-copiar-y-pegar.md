## Copiar y pegar

En vi, "copiar" se llama yank (por eso el comando es y), y "cortar" en la práctica es lo mismo que borrar con d, porque lo borrado también queda guardado y se puede pegar.

## Copiar (yank)
Comando	Qué hace
yy	Copia (yank) la línea completa
yw	Copia una palabra
y$	Copia desde el cursor hasta el final de la línea


## Pegar (put)
Comando	Qué hace
p	Pega después de la línea o carácter actual
P	Pega antes de la línea o carácter actual

## Cortar (que en realidad es borrar)

Como se mencionó en la sección de edición, dd (borrar línea) o dw (borrar palabra) guardan lo borrado, así que después se puede pegar con p o P igual que si hubiera sido copiado.

dd   corta la línea actual
p    la pega debajo de donde esté el cursor
