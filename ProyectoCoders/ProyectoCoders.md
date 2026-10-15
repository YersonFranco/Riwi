cohorte8@RW-0546:~/Documents$ mkdir ProyectoCoders
cohorte8@RW-0546:~/Documents$ cd ProyectoCoders
cohorte8@RW-0546:~/Documents/ProyectoCoders$ mkdir src assets docs tests config backup
cohorte8@RW-0546:~/Documents/ProyectoCoders$ pwd
/home/cohorte8/Documents/ProyectoCoders
cohorte8@RW-0546:~/Documents/ProyectoCoders$ ls
assets  backup  config  docs  src  tests
cohorte8@RW-0546:~/Documents/ProyectoCoders$ touch src/app.txt src/database.txt src/functions.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ echo "ProyectoCoders es un proyecto de practica para organizar codigo, recursos y documentacion usando la terminal de Linux." > docs/README.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ echo "idioma=es" > config/settings.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ echo "modo=desarrollo" >> config/settings.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ echo "ip=192.168.10.1" >> config/settings.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ cp config/settings.txt backup/
cohorte8@RW-0546:~/Documents/ProyectoCoders$ mkdir src/database
cohorte8@RW-0546:~/Documents/ProyectoCoders$ mv src/database.txt src/database/
cohorte8@RW-0546:~/Documents/ProyectoCoders$ cp src/functions.txt backup/
cohorte8@RW-0546:~/Documents/ProyectoCoders$ mv src/app.txt src/main.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ rm src/functions.txt
cohorte8@RW-0546:~/Documents/ProyectoCoders$ ls -R
.:
assets  backup  config  docs  src  tests

./assets:

./backup:
functions.txt  settings.txt

./config:
settings.txt

./docs:
README.txt

./src:
database  main.txt

./src/database:
database.txt

./tests:
cohorte8@RW-0546:~/Documents/ProyectoCoders$ cat docs/README.txt
ProyectoCoders es un proyecto de practica para organizar codigo, recursos y documentacion usando la terminal de Linux.
cohorte8@RW-0546:~/Documents/ProyectoCoders$ cat config/settings.txt
idioma=es
modo=desarrollo
ip=192.168.10.1
cohorte8@RW-0546:~/Documents/ProyectoCoders$ cat backup/settings.txt
idioma=es
modo=desarrollo
ip=192.168.10.1
cohorte8@RW-0546:~/Documents/ProyectoCoders$ touch ProyectoCoders.md
cohorte8@RW-0546:~/Documents/ProyectoCoders$ 

Reflexión y discusión:
1. ¿Por qué es importante mantener una estructura organizada en el desarrollo de
software?

R/ Una estructura organizada te ayuda a encontrar los archivos más rapido, que otros entiendan en trabajo que hiciste, poder corregir y agregar información de una manera más sencilla, como coder mantener una estructura organizada es fundamental.

2. ¿Cómo pueden los atajos de teclado y los comandos del sistema mejorar la
productividad?

R/ Ayuda demasiado a realizar de manera más rápida nuestro trabajo como coders, ya que crear carpeta por carpeta, archivo por archivo, todo uno por uno quita mucho tiempo, también los atajos como Tab para autocompletar o flecha hacia arriba para hacer el mismo comando te ahorra mucho tiempo.

