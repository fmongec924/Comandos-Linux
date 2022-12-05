# Comandos Linux
|Comando|Descripcion|Ejemplo|
|--------|------------------------------------------------------|------------|
sudo su | Se utiliza para ejecutar comandos como un usuario root|
ls | Muestra los archivos o carpetas | ls /Descargas
cd | Lleva a una carpeta | cd /home/directorio1
cp | Copiar archivos o directorios | cp copia.txt /usuarioX
nano / touch | Genera o modifica un archivo| nano arch.txt / touch arch1.txt
clear| Borrar lo impreso en consola|
du | Tamaño de un archivo | du -h home/ 
ps | Procesos actuales |
exit| Salir del usuario root|
cat| Imprimir la información de un archivo en consola y permite tambien crear archivos| cat zapato.txt
tail | 10 ultimas lineas de un archivo| tail archivito.txt
head | 10 primeras lineas de un archivo | head archivito.txt
more | Permite ver el contenido completo de un archivo en diferentes páginas | more libro.txt
less | Muestra el texto en la terminal | less libro.txt
sta| Información del archivo| stat bunny.txt
zip / tar -czvf| Comprimir archivos | zip mini.zip cosa.txt / tar -czvf scripts.tar.gz zzz.txt
unzip / tar -xvf| Descomprimir archivos | unzip mini.zip / tar -xvf scripts.tar.gz
pwd | Directorio actual |
scp | Copiar archivos en maquinas remotas | scp frog.txt lia@10.8.0.2:/home/Downloads
wget | Descargar archivos de una pagina web | wget https://manjaro.org/download/
curl | Peticiones a una pagina web | curl -X GET -L https://genshin.hoyoverse.com/en/home
wc | Contar datos | wc /Downloads/sandalia.txt
find | Encontrar directorios o archivos | sudo find /X -empty
whoami | Para saber el usuario actual|
top| Estado de los procesos|
ps tree| Porcesos actuales en formato de arbol|
ping | Conexión de dos dispositivos| ping 10.8.0.9
ip addr| Información sobre las ip de la maquina|
fdisk | Permite editar o crear tablas de particiones | sudo fdisk -l /dev/sda
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
chown | Da permisos de pertenencia a un usuario sobre una carpeta o archivo| chown fmongec924 archivoX.txt
uname -a| Permite ver el kernel que esta utilizando el SO | sudo uname -a
pkill | Matar a un proceso | pkill terminal
adduser | Permite agregar usuarios a la maquina|  sudo adduser Nilo
passwd | Permite cambiar la contraseña de un usuario | sudo passwd Nilo
">" | Permite generar comandos dentro de archivos | sudo ls /bin > texto.txt
crontab -e | Permite editar el archivo Cron| 









