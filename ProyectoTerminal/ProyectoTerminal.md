cohorte8@RW-0546:~/Documents$ pwd
/home/cohorte8/Documents
cohorte8@RW-0546:~/Documents$ ls
Events  Franco  Porfolio  ProyectoCoders  Riwi  python
cohorte8@RW-0546:~/Documents$ ls -l
total 24
drwxrwxr-x  2 cohorte8 cohorte8 4096 Oct 13 14:21 Events
drwxrwxr-x  3 cohorte8 cohorte8 4096 Oct  1 16:50 Franco
drwxrwxr-x  2 cohorte8 cohorte8 4096 Oct  1 17:46 Porfolio
drwxrwxr-x  8 cohorte8 cohorte8 4096 Oct 15 14:50 ProyectoCoders
drwxrwxr-x 11 cohorte8 cohorte8 4096 Oct 15 07:47 Riwi
drwxrwxr-x  3 cohorte8 cohorte8 4096 Oct 15 14:40 python
cohorte8@RW-0546:~/Documents$ ls -a
.  ..  Events  Franco  Porfolio  ProyectoCoders  Riwi  python
cohorte8@RW-0546:~/Documents$ cd ~
cohorte8@RW-0546:~$ cd Documents/
cohorte8@RW-0546:~/Documents$ mkdir ProyectoTerminal
cohorte8@RW-0546:~/Documents$ mkdir ProyectoTerminal/documentos ProyectoTerminal/imagenes ProyectoTerminal/scripts
cohorte8@RW-0546:~/Documents$ cd ProyectoTerminal
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ ls
documentos  imagenes  scripts
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ touch documentos/notas.txt documentos/tareas.txt
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ touch imagenes/logo.png
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ mv imagenes/logo.png documentos/
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ cp documentos/notas.txt documentos/notas_backup.txt
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ mv documentos/tareas.txt documentos/pendientes.txt
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ rm documentos/logo.png
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ rmdir imagenes
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ cd ..
cohorte8@RW-0546:~/Documents$ cd ~
cohorte8@RW-0546:~$ cd Documents/
cohorte8@RW-0546:~/Documents$ ls -R ProyectoTerminal
ProyectoTerminal:
documentos  scripts

ProyectoTerminal/documentos:
notas.txt  notas_backup.txt  pendientes.txt

ProyectoTerminal/scripts:
cohorte8@RW-0546:~/Documents$ cd ProyectoTerminal/
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ touch ProyectoTerminal.md
cohorte8@RW-0546:~/Documents/ProyectoTerminal$ 

