## Buscar y reemplazar
es la función que permite localizar una cadena de texto específica dentro de uno o varios archivos para sustituirla automáticamente por otra. En Linux, esta tarea se realiza según el entorno en el que trabajes:

## Desde modo normal:

Comando	Qué hace
/palabra	Busca "palabra" hacia adelante en el archivo
?palabra	Busca "palabra" hacia atrás
n	Repite la búsqueda en la misma dirección
N	Repite la búsqueda en dirección contraria
El comando :s (de "substitute") se usa junto con rangos y la bandera g (global):

## Comando	Qué hace
:s/viejo/nuevo/	Reemplaza la primera aparición en la línea actual
:s/viejo/nuevo/g	Reemplaza todas las apariciones en la línea actual
:%s/viejo/nuevo/g	Reemplaza todas las apariciones en todo el archivo
:%s/viejo/nuevo/gc	Igual, pero pide confirmación (c) antes de cada cambio
:%s/hola/adios/g

Esto cambia cada aparición de "hola" por "adios" en todo el documento.
