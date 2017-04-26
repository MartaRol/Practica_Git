##- �Qu� comando utilizaste en el paso 11? �Por qu�?

git reset --hard HEAD~1

Porque para deshacer el �ltimo commit perdiendo todos los cambios en el working copy me bastaba con retroceder un paso atr�s, a�adir --hard 
para deshacer lo que hab�i en el working copy tambi�n

##- �Qu� comando o comandos utilizaste en el paso 12? �Por qu�?

git reset --hard *ID del commit anterior*

Para volver al commit y recuperar lo que hice ten�a que ir al commit anterior usando el ID

##- El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?

No caus� ning�n conflicto, porque el archivo git-nuestro unicamente fue modificado por la rama styled.

##- El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?

Si, caus� conflicto porque el fichero git-nuestro estaba modificado por ambas ramas que fue lo que hicimos en el paso 9 y en el paso 17

##- El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?

No caus� ning�n conflicto porque ambas ramas estaban mergeadas correctamente

##- �Qu� comando o comandos utilizaste en el paso 25?

git log --graph 

Se puede mejorar usando el comando

git log --graph --decorate --oneline

##- El merge del paso 26, �Podr�a ser fast forward? �Por qu�?

Si, porque la rama title se creo desde la rama master por lo tanto las ramas estaban en l�nea

##- �Qu� comando o comandos utilizaste en el paso 27?

git reset HEAD~1

##- �Qu� comando o comandos utilizaste en el paso 28?

git stash

##- �Qu� comando o comandos utilizaste en el paso 29?

git branch -D title

##- �Qu� comando o comandos utilizaste en el paso 30?

git reset --hard ID (ID del merge del paso 26)

##- �Qu� comando o comandos usaste en el paso 32?

git reset ID (ID del commit inicial)

En el caso, que se quiera volver al commit inicial y deshacer lo que tenemos en el working copy podemos a�adir --hard al comando

##- �Qu� comando o comandos usaste en el punto 33?

git reset ID (ID del commit en el que pusimos el titulo)

En el caso, que se quiera volver al estado final y deshacer lo que tenemos en el working copy podemos a�adir --hard al comando
