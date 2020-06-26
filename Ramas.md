## Empezando con las ramas

Para crear una nueva rama

    git brnach nombreRama

Para ver las ramas que tenemos y en la que estamos posicionados

    git branch

Para movernos a la rama que creamos

    git checkout nombreRama

Comando para ver diferencia en una rama de otra

    git diff nombreRama nombreRamaMaster

Ahora par aunir una rama a la master(debemos estar en la master)

    git merge nombreRama

Para borrar una rama

    git branch -d nombreRama

Para crear una rama y movernos a esa rama en automatico

    git checkout -b nombreRama

¿Qué es un fast forward?