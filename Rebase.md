## Esto se usa para cuando queremos evitar conflictos la hacer un merge
(Cambios en la rama rebasePrueba para rebase 1)
(Cambios en la rama rebasePrueba para rebase 2)
tenemos una rama que tiene dos commit y la rama master tiene igualmente dos commits a la par

* *
| | 
* *
|/

entonces aqui vamos a tomar los dos commits del del master esten primero que los de la rama parapoder hacer el merge

*
|
*
|
*
|
*
|

(Cambios para el rebase 4)

## Rebase Squash

Este comando es para unir dos commits.

el comando es: 

    git rebase -i HEAD~4

"El 4 es de los ultimos 4 commits, esto puede variar"

al hacer ese comando nos parece una pantalla en el editor de la consola en el cual nos da un par de opciones con los 4 ultimos commits realizados asi que  al que queremos hacerle
el squash vamos a pornerle una letra s para que lo una conel commit seguido de la parte de arriba

    p "este es un commit"
