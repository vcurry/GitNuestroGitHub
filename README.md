# GitNuestroGitHub
Paso 11:
$ git reset --hard HEAD~1
si hubiese utilizado  $ git reset , se hubiese mantenido el contenido del working copy. Añadiendo --hard HEAD~1,
además de deshacer los cambios hechos en el último commit, vaciamos el working copy.

Paso 12:
$ git reflog
$ git checkout <id_commit>
con $ git reflog listamos todas las acciones ejecutadas en git y podemos ver el identificador del commit que
queremos recuperar. Con $ git checkout <id_commit> movemos el HEAD a ese commit para recuperarlo.

Paso 13:
no, porque mientras hacíamos cambios y nuevos commits del fichero git_nuestro.md en la rama styled, en la rama
master no hicimos modificaciones en las mismas líneas.

Paso 19:
sí, porque en la rama htmlify sí hemos modificado el fichero git_nuestro.md en las mismas líneas que habíamos
modificado en la rama styled.

Paso 21:
no, porque en la rama master no habíamos modificado ninguna línea modificada en styled.

Paso 25:
$ git log --graph --decorate --pretty=oneline para que sea lo más completo y legible posible.

Paso 26:
sí, podría ser fast forward porque la referencia de la rama title está en la misma línea que la rama master,
no tiene otras ramificaciones.

Paso 27:
$ git reset HEAD~1
utilizamos $ git reset sin --hard, para poder recuperar los cambios

Paso 28:
$ git reset --hard HEAD@{num}

Paso 29:
$ git branch -D title
con esta instrucción borramos la rama title

Paso 30:
$ git reflog
$ git reset --hard HEAD@{num}
con $ git reflog listamos todas las acciones ejecutadas en git y con $ git checkout HEAD@{num}
movemos el HEAD a ese commit para rehacer el merge.

Paso 32:
$ git reflog
$ git reset --hard <id_commit_inicial>

Paso 33:
$ git reset --hard <id_commit_final>
