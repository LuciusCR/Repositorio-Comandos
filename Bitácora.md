## **Bitácora de comandos de Sistemas Operativos**


| Comando | Descripción | Ejemplo de uso |
| ------- | ----------- | -------------- |
| Cat /var/log/dmesg + more | Para validar la información del archivo. | Se utiliza comando para validar la información que contiene el archivo |
 echo "texto" >> nombrearchivo | Agregar texto a archivo | Comando se utiliza para agregar texto a un archivo, sin sobreescribirlo sino agregando texto |
 cat | Muestra más info - contenido de archivo en caso de txt. | Permite mostrar mayor información sobre el contenido de un archivo de txt |
 cd .. | Directorio inicio | Comando se utiliza para movilizarse al directorio de inicio |
 cd /home | Directorio de Home | Comando se utiliza para movilizarse a directorio de Home |
 cd Documentos | Trasladar directorio a documentos | Comando se utiliza para trasladar el directorio al de Documentos |
 clear | Limpia terminal | Comando se utiliza para limpiar terminal de comandos |
 cp | Copiar archivo | Comando se utiliza para copiar un archivo desde la terminal de comandos |
 cp nombre de archivo - ingresa nuevo nombre | Comando para copiar archivos. | Se utiliza para copiar archivo específico desde terminal de comandos |
 docker images |  Imágenes instaladas | Docker images, permite visualizar las imágenes que tenemos instaladas |
 docker info |  Comprobar driver en uso | Docker info, se utiliza para comprobar la versión del driver en uso en nuestro sistema |
 docker version |  Validar versión | Docker Version para validar versión en la que nos encontramos utilizando docker |
 find / -name file | Buscar archivo con nombre | Comando de find se utiliza para realizar busqueda de archivo por nombre |
 head -n# var/log/dmesg | Para ver una parte en específico del inicio (cantidad de líneas) | Permite mostrar una cantidad específica de lineas de archivo |
 history  grep apt | Muestra resultados de comandos con apt | Permite visualizar el historial de los comandos utilizados apt |
 history  grep ls | Muestra resultados de comandos con LS | Permite visualizar el historial de los comandos utilizados ls |
 history | Muestra historial de comandos | Permite visualizar historial de comandos utilizados |
 hostname | Nombre del Host | Permite realizar visualización de nombre del host |
 Ip a | Para ver ip del equipo | Permite visualizar el IP del equipo en el que nos encontramos |
 kill idproceso | Detener proceso | Comando realiza detención de un proceso específico |
 logout | Cerrar Sesión | Comando realiza cierre de sesión del equipo |
 ls | Directorio de contenidos  | Permite mostrar el directorio de contenidos en el que nos encontramos |
 lsblk -fm | Comprobar estado de discos | Permite visualizar el estado de los discos de nuestros equipo |
 man | Manual de uso | Permite visualizar manual de uso del sistema |
 man apt | Manual del apt | Permite visualizar el manual de uso de los apt |
 man ls | Manual de listado de directorio de contenidos | Permite visualizar el manual de uso de ls |
 mkdir | Crear carpeta o directorio | Comando se utiliza para crear una nueva carpeta o directorio en nuestro sistema |
 more | Muestra más info - contenido de archivo en caso de txt. También para leer archivos muy largos. |
 mv nombre de archivo Documentos/ | Mover archivo a documentos | Comando se utiliza para mover un archivo específico a Documentos |
 nano | Crear archivo de texto | El comando nano se utiliza para crear un nuevo archivo de texto donde podemos editar su contenido |
 neofetch | Ejecutar paquete neofetch | Comando se utiliza para función neofetch que permite tener una visualización en consola |
 passwd | Modificar contraseña | Comando passwd permite realizar modificación de contraseña |
 pdw | Conocer el directorio donde estoy ubicado | Comando permite visualizar el directorio donde el usuario se encuentra ubicado |
 ps -aux | Validar procesos del sistema | Comando ps-aux facilita la posibilidad de visualizar los procesos activos en el sistema |
 reboot | Reinicio de Sistema | Comando reboot busca ejecutar el reincio del sistema |
 rm -rf | Eliminar carpeta de forma recursiva | Comando rem -rf se utiliza para eliminar una carpeta de forma recursiva |
 rmdir | Eliminar carpeta | Comando es utiliza para eliminar carpeta |
 stat | Brinda información de permisos, tamaño, fecha de creación, fecha de modificación de una archivo | Comando se utiliza para identificar información de permisos, tamaño, fecha de creación, fecha de modificación del archivo |
 sudo adduser  | Crear otro usuario en el sistema operativo | Comando sudo adduser se utiliza para crear un nuevo usuario |
 sudo apt install apache2 |  Instalar apache | Comando se utiliza para instalar paquete de apache |
 sudo apt install mdadm rsync initramfs-tools -y | Instalar paquete mdadm | Comando se utiliza para instalar paquete de mdadm |
 sudo apt install openssh-server | Instalar apt para conectar a terminus | Comando se utiliza para instalar paquete necesario para conectar a terminus |
 sudo apt update | Valida actualizaciones de sistema operativo | Comando se utiliza para actualizar sistema y sus paquetes |
 sudo apt upgrade -y | Realizar upgrade de sistema | Comando se utiliza para actualizar sistema y sus paquetes |
 sudo fdisk /dev/sdb | Crear partición de discos | Comando se utiliza para crear partición de discos |
 sudo mdadm -C /dev/md0 -l raid5 -n 3 /dev/sd[b-d]1 | Crear volumen RAID-5 | Comando se utiliza para establecer un volumen de RAID-5 |
 sudo mkfs.ext4 /dev/md0 | Formatear volumen | Comando se utiliza para formatear el volumen creado |
 sudo nautilus /media/usuario | Cambiar permisos de volumen | Comando se utiliza para modificar los permisos del volumen creado |
 sudo pacman -S unrar zip unzip p7zip gzip bzip2 |  Instalar nuevos paquetes para comprimir y descomprimir archivos | Comando es utilizado para instalar paquetes de .zip y adicionalmente comprimir y descomprimir archivos |
 sudo pacman -S yay |  Instalar el Repositorio AUR | Comando se utiliza para instalar repositorio AUR |
 sudo pacman -Syuu |  Actualizar los paquetes disponibles del sistema | Comando se utiliza para actualizar paquetes disponibles en el sistema |
 sudo password | Cambiar password |
 sudo su | Cambiar usuario al root (super-admin) | Comando se utiliza para cambiar el usuario al root (super admin) |
 sudo useradd | Crear nuevo usuario | Comando se utiliza para crear un nuevo usuario en sistema |
 sudo useradd -m nombredeusuario -G wheel -p passworddelusuario |  Crear usuarios nuevos | Comando se utiliza para crear un nuevo usuario y establecer su contraseña |
 sudo userdel | Eliminar usuario | Comando para eliminar usuario existente en sistema |
 sudo yay -S --needed base-devel |  Instalar el Repositorio AUR | Comando se utiliza para instalar repositorio AUR |
 tail -n# var/log/dmesg | Para ver una parte en específico del final (cantidad de líneas) | Comando para visualizar cantidad específica de lineas de archivo desde el final del archivo |
 touch + nombre del archivo | Crear un archivo de texto vacío | Crea un nuevo documento de texto vacio |
 tree | Arbol de Ficheros | Comando muestra el arbol de ficheros del sistema |
 unzip | Descomprimir archivo .zip | Comando para descomprimir un archivo .zip específico |
 whoami | Para saber el usuario conectado | Comando para conocer el usuario que se encuentra activo en sistema |
 yay -S google-chrome |  Instalar google-chrome | Comando utilizado para instalar paquete de Google Chrome |
add ficheros/"ubicación" | Agregar ficheros a la ruta establecida | Comando se utiliza para agregar nuevos ficheros a una ruta establecida para el usuario |
apt install neofetch | Instalar paquete neofetch | Comando es utilizado para instalar paquete de neofetch |
cmd [ ] | Ingresar parámetros | Comando se utiliza en dockerfile para ingresar parámetros |
docker build -t "nombre":ubuntu | Compilar contenido de la imagen  | Comando es utilizado para compilzar contenido de una imagen en docker |
docker find ./ | Validar fichero de Dockerfile | Comando se utiliza para realizar unas busqueda de fichero en docker |
docker history | Cantidad de Capas de una imagen | Permite visualizar la cantidad de capas en una imagen de docker |
docker ps -a | Ver estado de contenedores | Permite visualizar el estado de un contenedor en docker |
docker pull alpine:latest  |  Descargar imagen alpine:latest | Comando se utiliza para instalar la imagen de alpine en docker |
docker pull ubuntu |  Descargar imagen ubuntu | Comando docker pull se utiliza para descargar una imagen, en este caso ubuntu |
docker rm "identificador" | Eliminar contenedor | Comando se utiliza para eliminar un contenedor de docker |
docker rm "identificador" -f | Eliminar contenedor de forma forzada | Eliminar un contenedor docker de forma forzada |
docker rmi ubuntu:16.04 | Eliminar imagen ubuntu y su versión | Comando se utiliza para eliminar una imagen de docker, en este caso ubuntu y su versión específica |
docker run -ti  --rm ubuntu | Una vez se ejcute el comando del contenedor lo elimina del disco | Este comando se utiliza para ejecutar y posteriormente eliminar el contenido del contenedor en el disco |
docker run -ti ubuntu | Ejecuta imagen de forma interactiva | Comando se utiliza para ejecutar la imagen de forma interactiva y permita realizar más ajustes |
docker run -ti ubuntu:16.04 | Ejecuta imagen con la versión específica de forma interactiva | Comando se utiliza para ejecutar la imagen de forma interactiva y permita realizar más ajustes  en versión específica |
docker run ubuntu | Ejecuta imagen ubuntu | Ejecutar comando para correr imagen de ubuntu en docker |
docker stop "identificador" | Detener contenedor | Comando docker stop se utiliza para detener contenedor específico |
env variable1 valor1 | Configurar variable | Comando se utiliza para configurar variables que sean necesarias utilizar en dockerfile |
exit | Salir del terminal | Comando se utiliza para salir de terminal de comandos |
expose "#" | Indica Puerto a utilizar en el contenedor | Comando se utiliza para indicar en nuestro dockerfile cuál es el puerto a utilizar |
from ubuntu:16.04 | Heredar contenido de la imagen | Comando se utiliza en docker para heredar el contenido de una imagen a nuestra imagen actual |
run apt -get install  -y nginx | Ejecutar instalación de paquete mediante dockerfile | Comando se utiliza para instalar paquete de datos mediante dockerfile |
run echo "hola" > /root/saludos.txt | Crear fichero en nuestro dockerfile | Comando funciona para crear un nuevo fichero dentro de nuestro dockerfile |
sudo apt upgrade | Actualizar sistema operativo | Permite realizar actualización de sistema y paquetes |
telnet towel.blinkenlights.nl |  Starwars | Este comando ejecuta un scrip sobre las películas de starwars |
vim Dockerfile | Validar dockerfile | Comando permite validar nuestro dockerfile |
pstree | Muestra arbol de procesos con relación padre-hijo | pstree en la máquina ubuntu para verificar procesos en estructura de árbol |
