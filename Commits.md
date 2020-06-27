## Commits

cosas que podemos hacer con los commits en resumen

## cambiar el mensaje

si nuestro ultimo commit pusimos un comentario que no era o simplemente mala ortografia podemos usar lo siguiente

git commit --amend -m "Nuetsro mensaje"

## Revirtiendo el commit

El problema que surge es que si en un commit olvidamos un pequeño cambio y muy facilmente podemos hacer commit de nuevo para eso podemos revertir un commit, mala practica crear commits con canbios "insignificantes"

Revertimos el commit

    git reset --soft HEAD^

y ahora solo queda hacer un commit como cualquier otro


(Cambio para el rebase 3)