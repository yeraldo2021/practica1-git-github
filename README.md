- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

git reset HEAD~1
git restore git-nuestro.md 

Primero se elimino el commit y luego los cambios del archivo .md

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog
git reset --hard b36b3aa

Primero se tiene que ver el ID de commit y luego hacer un reset  --hard con referencia al ID para poder rehacer

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causo conflicto, 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si causo conflicto

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No causo conflicto

- ¿Qué comando o comandos utilizaste en el paso 25?

Git graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

No por que tiene bifurcación

- ¿Qué comando o comandos utilizaste en el paso 27?

git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?

git restore git-nuestro.md 

- ¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

- ¿Qué comando o comandos usaste en el paso 32?

git checkout 37418879ac09a1acbeae40054d02cf7425284ee4


- ¿Qué comando o comandos usaste en el punto 33?

git reset --hard 3c3faf3
