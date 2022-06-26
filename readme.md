- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1: al pedir que se pierdan los cambios en el working copy decido usar el HARD para machacar el working space.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reset --hard <codigo de commit>: para mover la rama styled an commit con esos cambios restaurando el working copy.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Informa de que está "up to date".

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Hay conflicto al ser dos versiones del mismo archivo.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
Ningún conflicto, pero el git-nuestro.md aparece vacío (New File).

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Podría ser fast forward ya que los ficheros son iguales

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reset --hard 32941312348b5caec6f26b5a575a98f494a9084d

- ¿Qué comando o comandos usaste en el paso 32?
git reset c09c58a61e59c0f4504e9ac650b906dfb9850712

- ¿Qué comando o comandos usaste en el punto 33?
git reset 32941312348b5caec6f26b5a575a98f494a9084d


