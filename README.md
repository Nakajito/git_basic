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
