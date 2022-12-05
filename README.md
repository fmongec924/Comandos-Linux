# Comandos Linux
|Comando|Descripcion|Ejemplo|
|--------|------------------------------------------------------|------------|
sudo su | Se utiliza para ejecutar comandos como un usuario root|
ls | Muestra los archivos o carpetas | ls /Descargas
cd | Lleva a una carpeta | cd /home/directorio1
cp | Copiar archivos o directorios | cp copia.txt /usuarioX
nano | Genera un archivo| nano arch.txt
clear| Borrar lo impreso en consola|
ps | Procesos actuales |
exit| Salir del usuario root|
cat| Imprimir la información de un archivo en consola| cat zapato.txt
tail | 10 ultimas lineas de un archivo| tail archivito.txt
head | 10 primeras lineas de un archivo | head archivito.txt
more | Permite ver el contenido completo de un archivo en diferentes páginas | more libro.txt
whoami | Para saber el usuario actual|
top| Estado de los procesos|
ps tree| Porcesos actuales en formato de arbol|
ip addr| Información sobre las ip de la maquina|
chmod | Da permisos para poder modificar o ejecutar un archivo | chmod +x archivo
history | Permite ver todos los comandos ejecutados | 
grep | Permite escoger archivos con ciertas palabras o formato| sudo grep hola saludos.txt
apt install| Comandos para la instalación de aplicacion| sudo apt install sudoku
sudo demicode --type 17 cat /proc/meminfo | Imprime el tamaño de la memoria|
for file in /proc/* /status ; do awk '/VmSwap!Name/{printf $2 " " $3}END{ print ""}' $file; done ! sort -k 2 -n -r ! less | Memoria de cada programa|
pacman| Comando de instalación de Manjaro | sudo pacman sudoku
mkdir | Permite |crear un nuevo directorio | mkdir prueba
rm | Borra un archivo | rm /cosas/archivobasura
rmdir | Borra un directorio | rmdir /directbasura
chown | Da permisos de pertenencia a un usuario sobre una carpeta o archivo| chown fmongec924 archivoX
uname -a| Permite ver el kernel que esta utilizando el SO | sudo uname -a
pkill | Matar a un proceso | pkill terminal
adduser | Permite agregar usuarios a la maquina|  sudo adduser Nilo
passwd | Permite cambiar la contraseña de un usuario | sudo passwd Nilo
">" | Permite generar comandos dentro de archivos | sudo ls /bin > texto.txt
crontab -e | Permite editar el archivo Cron| 









