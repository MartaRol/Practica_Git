##- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1

Porque para deshacer el último commit perdiendo todos los cambios en el working copy me bastaba con retroceder un paso atrás, añadir --hard 
para deshacer lo que habái en el working copy también

##- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reset --hard *ID del commit anterior*

Para volver al commit y recuperar lo que hice tenía que ir al commit anterior usando el ID

##- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causó ningún conflicto, porque el archivo git-nuestro unicamente fue modificado por la rama styled.

##- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, causó conflicto porque el fichero git-nuestro estaba modificado por ambas ramas que fue lo que hicimos en el paso 9 y en el paso 17

##- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No causó ningún conflicto porque ambas ramas estaban mergeadas correctamente

##- ¿Qué comando o comandos utilizaste en el paso 25?

git log --graph 

Se puede mejorar usando el comando

git log --graph --decorate --oneline

##- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, porque la rama title se creo desde la rama master por lo tanto las ramas estaban en línea

##- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

##- ¿Qué comando o comandos utilizaste en el paso 28?

git stash

##- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

##- ¿Qué comando o comandos utilizaste en el paso 30?

git reset --hard ID (ID del merge del paso 26)

##- ¿Qué comando o comandos usaste en el paso 32?

git reset ID (ID del commit inicial)

En el caso, que se quiera volver al commit inicial y deshacer lo que tenemos en el working copy podemos añadir --hard al comando

##- ¿Qué comando o comandos usaste en el punto 33?

git reset ID (ID del commit en el que pusimos el titulo)

En el caso, que se quiera volver al estado final y deshacer lo que tenemos en el working copy podemos añadir --hard al comando
