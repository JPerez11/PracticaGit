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
# 
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