![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/%F0%9F%92%BB%F0%9F%A4%97Comandos_de_Linux_%5B_%5D.png)
![GitHub contributors](https://img.shields.io/github/contributors/melaniearista/BitacoraComandosSO?color=magenta&label=Creado%20por%20Melanie%20Arista&style=plastic)

# Bitácora de Comandos Linux
A continuación los comandos aprendidos durante el curso de Sistemas Operativos.

## Cd
`cd` funciona para navegar en los directorios.
```ruby
cd home/Desktop/Documents/Sistemas_Operativos
```
Este ejemplo entraría al contenido de Sistemas_Operativos.
## Sudo
`sudo` nos da los permisos de administrador y podemos ejecutar tareas como root.
```python
sudo apt install chromius
```
Este ejemplo nos descargaría el navegador 🌏Chrome.
## Clear 
`clear` o `Ctrl + l` nos ayuda a limpiar la terminal.

![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon%20(1).png)

## Su
`su` nos permite cambiar de usuarios y ejecutar tareas como èl.
```python
su - MelanieArista
```
En este ejemplo entraríamos a 👤MelanieArista.

## Ls
`ls` lista todos los directorios y archivos y puede dar información detallada de estos.
```ruby
ls ~/Universidad/
```
Para mostrar los archivos dentro de la carpeta universidad.
```python
#Output
Curso1  PresentacionFinal  Curso2   Exposicion
```
## Mkdir
`mkdir` funciona para la creación de nuevos directorios.
```ruby
mkdir IVCuatrimestre
```
Nos crearía un nuevo directorio llamado 📂IVCuatrimestre.

## Rmdir
`rmdir` funciona para la eliminación de directorios.
```ruby
rmdir -p dir1/dir2/dir3
```
Elimina el directorio y sus ancestros.

## Cp
`cp` hace una copia de un archivo.
```ruby
cp -a presentacionfinal.pdf /home/Desktop/Ayuda/
```
Copia incluyendo los permisos y ajustes del archivo a la carpeta 📂Ayuda

## Mv
`mv` mueve archivos y directorios, también puede cambiar el nombre.
```python
mv presentacionfinal.pdf /bin
```
Mueve el archivo a la carpeta 📂bin

## Rm
`rm` elimina archivos y directorios.
```ruby
rm universidad*
```
🗑Elimina todos los archivos que contengan la palabra universidad.

## Ipaddr
`ipaddr` nos muestra nuestra ip.
```ruby
#Output
ip: 120.20.10.10
```

## Netstat
`netstat` nos muestra el estado de comunicación de la red de la máquina.
```ruby
netstat -f
```
Muestra conexiones activas de TCP.

## Nmap
`nmap` nos muestra información de las IPs activadas en nuestra red.
```ruby
nmap -h
```
Pedimos ayuda con nmap al utilizar este comando.

## Ps
`ps` imprime procesos que están ejecutándose, puede ir con distintas indicaciones. 

![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon.png)

Imprime todos los procesos con información detallada.

## Pkill
`pkill` cierra o *mata* procesos.

```python
pkill -n firefox
```
Cierra los procesos 🌏firefox creados más recientemente.

## Kill 
`kill` *mata* un proceso.

```python
kill -9 $PID
```
Fuerza al proceso a terminar inmediatamente.

## Bash
`bash` funciona para ejecutar archivos de tipo .sh

```ruby
bash archivocool.txt
```
Va a ejecutar el 📑archivocool.txt

## Ln
`ln` crea enlaces para archivos o directorios.
```ruby
ln /home/MelanieArista/Universidad/EvidenciaTaller.mp4 hard_link_a_evidenciataller
```
Se crea un **hard link** con la referencia 📎*hard_link_a_evidenciataller*

## Man
`man` nos da un manual del uso de comandos.
```ruby
man ls
```
Nos dará una descripción y lista de posibles usos.

## Whoami
`whoami` nos indica con cuál usuario estamos loggeados. 
![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon%20(2).png)

Imprime el nombre del usuario.

## Useradd
`useradd` funciona para crear usuarios.
```ruby
sudo useradd -m Pepe
```
Crea el usuario 👤Pepe incluyendo el directorio home.

## Touch
`touch` crea nuevos archivos.
```python
touch historialdecomandos.txt
```
📜Crea un archivo de txt que se llama historial de comandos.

## Head
`head` mostrar las primeras palabras de un archivo.
```python
head -n 100 magia.txt
```
Imprime las primeras 100 palabras del archivo magia.txt📜

## Tail
`head` mostrar las últimas palabras de un archivo.
```ruby
tail magia.txt
```
Imprime las últimas 10 líneas del archivo **magia.txt**

## Vim
`vim` es un tipo de editor de texto dentro de la terminal.
```ruby
vim historialdecomandos.txt
```
Nos abrirá el archivo 📑**historialdecomandos** donde se podrá editar.

## Nano
`nano` es un tipo de editor de texto dentro de la terminal.
```python
nano historialdecomandos.txt
```
Nos abrirá el archivo 📑**historialdecomandos** donde se podrá editar.

## Pacman
`pacman` es un package manager predeterminado para las distribuciones ArchLinux.
```python
sudo pacman -S root
```
Descarga el paquete root.

## Wget
`wget` nos ayuda a instalar files de la web.
```ruby
wget -O descarga1 https://amazon/
```
Va a descargar el paquete del url y asignarle el nombre *descarga1*

## Cat
`cat` imprime el contenido de un archivo.
```python
cat contrasenyassecretas.txt
```
Nos va a mostrar en terminal el contenido del archivo 📜.
```python
#Output
mariano1;hola123
susanitx12;contrasenya
juan;123456
```

## Grep
`grep` nos ayuda a buscar archivos y directorios.
```ruby
grep -i perritos inventariomascotas.txt
```
Nos va a buscar en el archivo de *inventariomascotas* la palabra 🐶**perritos** sin distinguir mayúsculas ni minúsculas.

## Find
`find` nos ayuda a encontrar archivos y directorios.
```ruby
find . -type f -maxdepth 1 -perm 777

```
Para encontrar archivos con derechos 777.

## Locate 
`locate` nos ayuda a localizar archivos y directorios.
```ruby
locate perritos.txt

```
Busca el archivo 📜🐶perritos.txt

## Tree
`tree` imprime la jerarquía del directorio y sus subdirectorios.
![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon%20(3).png)

Imprimirá la jerarquía del directorio actual.

## Chmod
`chmod` funciona para cambiar los permisos de archivos y directorios.
```ruby
chmod 777 confidencial.txt
```
Da todos los permisos para el archivo 📑confidencial.txt

## Chown
`chown` funciona para cambiar el ownership de un archivo.
```ruby
chown MelanieArista ejemplo.txt
```
Cambia el ownership del archivo 📜ejemplo.txt

## Df
`df` funciona para mostrar cantidad de espacio del disco.
```ruby
df -h
```
Muestra la cantidad de disco usado.

## Mount
`mount`  montaje de dispositivos en los archivos.
```ruby
sudo mount -v
```
Muestra la versión.

## Pwd
`pwd` muestra el directorio actual.
```ruby
pwd
```
**Muestra el directorio.**

## Crontab
`crontab` nos permite que las tareas se ejecuten a un tiempo específico.
```python
sudo crontab -e
```
Nos permite editar los crontab.

## Curl
`curl` nos permite hacer peticiones a páginas web.
```python
curl -o archivo.tar.gz http://google.com/wow.tar.gz
```
Va a guardar el archivo como 📜archivo.tar.gz

## Gitclone
`gitclone` funciona para clonar repositorios de GitHub.
```python
gitclone https://github.com/melaniearista/BitacoraComandosSO/
```
Va a clonar el repositorio BitacoraComandosSO.

## History
`history` imprime la lista de los últimos comandos ejecutados en la terminal.
![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon%20(5).png)

Veremos los comandos escritos.

## Reboot
`reboot` reinicia nuestra máquina.

![](https://github.com/melaniearista/BitacoraComandosSO/blob/main/carbon%20(6).png)

## Tar
`tar` manejo de archivos tar, nos ayuda a descomprimir y comprimir archivos.
```python
tar -cvf gatos.tar /home/Melanie/Universidad/
```
Comprime el archivo.
