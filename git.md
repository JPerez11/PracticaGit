**CURSO GIT**

***COMANDOS***

```bash
git init
# Crea un repositirio Git o reinicia uno existente.

git add _Nombre del archivo_
# Agrega el contenido del archivo al index.

git add .
# Agrega todos los archivos al staging area.

git status
# Muestra un resumen del cual los archivos tienen cambios que se organizan para la próxima configuración.

git status -s
# La opción s de short, da una salida en formato corto.

git commit
# Registra los cambios en el repositorio.

git commit -m "Mensaje de confirmación"
# La opción m de message, se utiliza para dar un mensaje de confirmación.

git log
# Muestra los registros de confirmación (commits)..

git log --oneline
# formatea el log para mostrar los mensajes en una línea.

git reset
# Reestablece el HEAD actual al estado especificado.

git reset --hard _id de la copia_
# Reestablece el indice y el árbol de trabajo.

git commit -am ""
# hace el commit sin necesidad del add ., ya que, con -am lo hace automaticamente.

git commit --amend
# Editor vim
# Permite arreglar o modificar la descripción del commit.


git remote add origin _dirección del repositorio_
# Comando para iniciar un repositorio remoto.

git branch -M main
# Cambia el nombre de la rama.

git push -u origin main
# Comando para actualizar el repositorio en github.

git push
# Permite actualizar referencias remotas junto con objetos asociados.

git pull
# Permite obtener e integrar repositorios o un branch local.

git tag _nombre del tag_ -m "_Descripción del tag_"
# Crea una etiqueta o tag para referenciar una versión del proyecto.

git push --tags
# Actualiz el tag en el repositorio de github.

git branch
# Lista las ramas existentes.

git branch _nombre de la rama_
# Crea la rama con el nombre del parametro.

git checkout _nombre de la rama_
# Cambia a la rama del parametro.

git merge _nombre de la rama_
# Desde la rama principal, une el branch que del parametro con ella.
```
***Pasos básicos para utilizar repositorio Git***

```bash
# Primero se debe crear el repositorio.
git init
# Luego se deben agregar los archivos al staging area.
git add .
o
git add _nombre del archivo_
# El siguiente paso es enviar al repositorio local.
git commit -m  ""
```