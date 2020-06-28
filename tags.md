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

## conflictos con el stash

Podemos hacer cambios en el mismo archivo en el que trabajabamos en el momento de hacer el stash esto generara congflictos por los cmabios que debe tomar
el archivo asi que se deben resolver de la misma manera que con una rama. Pero esto nos dejara el stash activado y para eso debemos borrarlo y eso lo hacemos con:

    git stash drop


## Datos extra del git stash

Los comandos siguientes hacen practicamente lo mismo

    git stash y git stash save -> Salva los cambios y los pone en el stash

    git stash apply y git stash apply stash@{0} -> Mientras en las llaves no se ponga otro numero vamos a aplicar el stash 0

Para borrar un stash en especifico dependiendo su numero en la llave 

    git stash drop stash@{1} 

## Mas comando para el stash

Para guardar todo menos los archivos que estan en el stage

    git stash --kepp-index

Incluir todos los archivos incluyendo a los que git no da seguimiento

    git stash save --include-untracked

## Mas detalle del stash

    git show stash

Para agregar un comentario al hacer un stash 

    git stash save "Mensaje del stash"


## Borrar todos los stash

    git stash clear

Tener cuidado con este comando porque no pregunta y simplemente borra las entrdas del stash

un pequeño cambio
otro mas pequeño