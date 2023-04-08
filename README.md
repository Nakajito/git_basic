# GIT
Git es un sistema de control de versiones distribuido que te permite registrar los cambios que haces en tus archivos y volver a versiones anteriores si algo sale mal.

* Git está optimizado para guardar cambios de forma incremental.

* Permite contar con un historial, regresar a una versión anterior y agregar funcionalidades.

* Lleva un registro de los cambios que otras personas realicen en los archivos.

# git_basic

Conocer la versión de git
~~~
git --version
~~~

Configurar usuario y correo

~~~
git config --global user.name "<USER_NAME>"
git config --global user.mail "<USER_MAIL>"
~~~

comprobar se aplicaron los cambio adecuadamente
~~~
git config --list
~~~

# Configuración del repositorio

crear la carpeta del proyecto o arbol de trabajo
~~~
mkdir <nombre_carpeta>
cd <nombre_carpeta>
~~~

inicializar el repositorio (v 2.28 o superior)
~~~
git init --initial-branch=main
git init -b main
~~~

inicializar repositorio (v anterior)
~~~
git init
git checkout -b main
~~~

mostrar el estado del arbol de trabajo
~~~
git status
ls -a
~~~

# Comandos básicos
~~~
git status // muestra etado del arbol
git add // almacenamiento provicional
git commint // Confirmación de cambios
git log // Ver información sobre las confirmaciones anteriores
git help // obtener ayuda
~~~
