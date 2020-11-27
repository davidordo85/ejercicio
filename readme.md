# Preguntas y respuestas.

*¿Qué comando utilizaste en el paso 11? ¿Por qué?

- He utilizado el comando "git reset --hard HEAD~1", que deshace el último commit, con el modificador "--hard" que borra también los cambios en el working copy. 

*¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

- He usado el comando "git reflog" para ver todo lo que ha ocurrido en el repositorio y sacar el identificador del commit anterior.
- Después he utilizado el comando "git reset --hard (ID commit)" para volver al commit anterior y que vuelvan los cambios en el working copy. 

*El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

- Realmente no ha pasado nada por que la rama styled ya está actualizada.

*El merge del paso 19, ¿causó algún conflicto? ¿Por qué?

- Si ha causado un conflicto, ya que se han modificado las mismas lineas en las dos ramas styled y htmlify.

*El merge del paso 21, ¿causó algún conflicto? ¿Por qué?

- No, ya que la rama master no tiene ninguna modificación. 

*¿Qué comando o comandos utilizaste en el paso 25?

- "git log --graph".

*El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

- Si, git sólo tendria que mover el puntero master al commit de la rama title y absorber los cambios.

*¿Qué comando o comandos utilizaste en el paso 27?

- "git reset HEAD~1"

*¿Qué comando o comandos utilizaste en el paso 28?

- "git checkout -- git-nuestro.md"

*¿Qué comando o comandos utilizaste en el paso 29?

- git branch -D title.

*¿Qué comando o comandos utilizaste en el paso 30?

- "git reflog"
- "git reset --hard (ID commit)"

*¿Qué comando o comandos utilizaste en el paso 32?

- "git log --graph"
- "git reset --hard (ID commit inicial)"

*¿Qué comando o comandos utilizaste en el paso 33?

- "git reflog"
- "git reset --hard (ID ultimo commit)"




