# practicaGit
Práctica Git del KC Boot IV

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset --hard HEAD~1
Para mover la rama al commit anterior descartando cambios en el working copy.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog
git reset --hard e6662617
Para conocer el commit al que moverme y mover tanto puntero HEAD como puntero de rama styled hasta él.
No se ha utilizado checkout para evitar el detached head (lo manda el padre git nuestro).

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No hay conflicto, aunque indica "Already up-to-date" porque las ramas ya están *mergeadas*.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

Sí, porque el mismo fichero tiene líneas diferentes en ambas ramas (todas menos la primera).

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

No. Se hace un fast forward.

- ¿Qué comando o comandos utilizaste en el paso 25?

git superlog (soy así de chulo ;))
Se trata de un alias a "log --graph --all --decorate"

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

Sí, porque no se perderían commits.

- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? 

git checkout -- git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29? 

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? 

git reflog
git reset --hard 74490fd

- ¿Qué comando o comandos usaste en el paso 32?

git log
git reset --hard 4301bf9

- ¿Qué comando o comandos usaste en el punto 33?

git reflog
git reset --hard 74490fd
