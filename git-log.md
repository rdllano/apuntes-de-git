### git log
Muestra todo el historial de commits del proyecto

git log --pretty=format:"%h - %an, %ar : %s"
Muestra el historial con el formato que indicamos.

##Limitar la salida del historial
git log -n:Cambiamos la n por cualquier numeri entero, por ejemplo: git log -2 nos mostrara los 2 commit mas recientes.
git log --after="2016-04-07 00:00:00":Muestra los commits realizados despues de la fecha


`git log --oneline`
Este comando nos muestra el historial en una sola linea por commit.
