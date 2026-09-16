# manual-vi-editor

Este repositorio contiene un manual básico sobre el editor de texto Vi, una herramienta disponible en los sistemas GNU/Linux y Unix.

El objetivo es explicar de manera sencilla los principales modos, comandos y funcionalidades de vi, con ejemplos prácticos para facilitar su aprendizaje y uso desde la terminal.

## Contenido


El manual está organizado en diferentes temas:

1	Modos y creación de archivos	docs/01-modos-y-creacion.md
2	Navegación básica	docs/02-navegacion.md
3	Edición y deshacer	docs/03-edicion-y-deshacer.md
4	Copiar y pegar	docs/04-copiar-y-pegar.md
5	Buscar y reemplazar	docs/05-buscar-y-reemplazar.md
6	Insertar texto	docs/06-insertar-texto.md
7	Guardar y salir	docs/07-guardar-y-salir.md

## ¿Qué es vi?

vi es un editor de texto que viene instalado por defecto en casi cualquier sistema Unix/Linux. A diferencia de un editor como el Bloc de notas, no puedes simplemente abrirlo y empezar a escribir: primero tienes que entender que trabaja con modos distintos — uno para moverte y dar comandos, y otro para escribir texto de verdad.

Al principio se siente incómodo porque cada tecla "hace algo" en vez de solo escribir letras, pero una vez entiendes la lógica de modos, se vuelve muy rápido de usar sin tocar el mouse ni las flechas.



Cheat sheet — comandos que más uso
Comando	Qué hace	Mi ejemplo
i	Entra en modo inserción antes del cursor	(tu ejemplo)
dw	Borra una palabra completa	(tu ejemplo)
dd	Borra la línea completa	(tu ejemplo)
yw	Copia (yank) una palabra	(tu ejemplo)
p / P	Pega después / antes del cursor	(tu ejemplo)
u	Deshace el último cambio	(tu ejemplo)


 Créditos

Esta actividad corresponde al Laboratorio 7 — Documenta, versiona y publica lo que aprendes del Seminario de Linux, FUNLAM.

Docente: Bayron Jesit Ospina Cifuentes · bayron.ospinaci@amigo.edu.co
