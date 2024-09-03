# HACK - GIT 7

##### ### ## ELIMINAR UN ARCHIVO EN EL REPOSITORIO REMOTO.

-Crear un nuevo repositorio en github nombre: git_h_7

-Crear un repositorio local

-git init

-Registrar el repositorio remoto con tú repositorio local

-git remote add origin (pegar_la_ruta_del_repositorio_local)

-Verificamos la ruta remota

-git remote -v

-Creamos 3 archivos "foo.txt" "bar.txt" y "qux.txt" y hacemos push, (revisamos el repositorio remoto)

-Ahora eliminamos a "foo.txt"

-git rm --cached foo.txt

-Verificamos el stage

-git status

-Hacemos un commit y al hacer push damos de baja el archivo "foo.txt" en el repositorio remoto

-git commit -m "feat: remove foo.txt"

-git push 




##  FIN.
