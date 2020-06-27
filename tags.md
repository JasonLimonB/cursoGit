## Tags

Para hacer un tag del ultimo commit realizado es

    git tag primerTag

Para hacer un tag de un commit anterior
    1.- Debemos tener el id del commit y eso podemos checarlo con 
        git log --oneline
    2.- hacemos el tag
        git tag tagAnterior idCommit -m "Mensaje"

## Git stash

El stash nos sirve para poder a salvo cambios nuevos en lo que se libera una version en un commit anterior, para ello usamos el comando 

    git stash

Esto nos sirve para poder hacer cambios de emergencia y mantener nuestros cambios nuevos a salvo en caso que se requierie una liberacion u algun otro tema relacionado

    para ver los stash WIP (Work in progress)
     git stash list

En este estado podemos hacer modificaciones rapidas en otro documentos que seran agregados a nuestro archivo cuando salgamos del stash 
para salir del stash es

    git stash pop