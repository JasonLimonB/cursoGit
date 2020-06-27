## Viajar en el tiempo con git

Para esto debemos hacer varios commit solo como prueba (cuando se esta en el curso)

1.- debemos tener el numero(id) para poder viajar a ese punto para luego
    git reset --soft id

## niveles de reset
1.- soft
2.- mixed
3.- hard

el punto de hard ya nos borra nuestros archivos o cambios que realizamos

## hicimos un hard por equivocacion
no hay qu epreocupar ya que git tiene algo como 
    git reflog

copiamos el id para volver a ese punto
    git reset --hard id

y todo vuelve al punto donde hicimos el primer hard

solo e sparte del curso

-----------------
entender el stash..