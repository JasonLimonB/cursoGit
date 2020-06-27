## Tags

Para hacer un tag del ultimo commit realizado es

    git tag primerTag

Para hacer un tag de un commit anterior
    1.- Debemos tener el id del commit y eso podemos checarlo con 
        git log --oneline
    2.- hacemos el tag
        git tag tagAnterior idCommit -m "Mensaje"
        