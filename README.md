# Bienvenidos(as) al Repositorio

### Creado por Sebastián André López Corrales

Este repositorio está creado para exponer comandos vistos en el curso de sistemas operativos en 2021, III Cuatrimestre.

### Comandos Linux Base

| Comando                             | Sirve Para                                                      | Ejemplo                                                                                            |
| ----------------------------------- | --------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| ip addr                             | Retorna la dirección IP de la máquina                           | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/1.png)  |
| ping {ip}                           | Trata de conectar con la IP indicada                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/2.png)  |
| sudo apt install {paquete}          | Instala el paquete indicado                                     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/3.png)  |
| sudo apt install neofetch           | Instala neofetch, para ver un resumen del sistema operativo     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/4.png)  |
| neofetch                            | Muestra información del sistema                                 | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/5.png)  |
| sudo apt update && sudo apt upgrade | Actualiza los paquetes y el instalador de paquetes              | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/6.png)  |
| clear                               | Limpia la consola                                               | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/7.png)  |
| pwd                                 | Muestra donde está la terminar en uso                           | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/8.png)  |
| sudo apt install cmatrix            | Instala el programa de matrix                                   | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/9.png)  |
| cmatrix                             | Ejecuta un efecto visual como la matrix                         | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/10.png) |
| whoami                              | Muestra el usuario actual                                       | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/10.png) |
| man                                 | Muestra el manual de los comandos                               | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/11.png) |
| exit                                | Sale de la consola                                              | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/12.png) |
| nano {archivo}                      | Abre un editor de texto para un archivo especificado            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/13.png) |
| cat {nombre}                        | Abre el contenido del archivo de texto                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/14.png) |
| ls                                  | Muestra los archivos y carpetas de la carpeta actual            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/15.png) |
| su -                                | Modo root, tiene todos los privilegios                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/16.png) |
| mkdir {nombre}                      | Crea una arpeta con el nombre especificado                      | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/17.png) |
| cp {archivo1} {archivo2}            | Copia el contenido de un texto a otro                           | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/18.png) |
| mv {archivo} {ruta}                 | Mueve archivo a la ruta especificada                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/18.png) |
| ls {ruta} / grep {archivo}          | Muestra contenido de la ruta y grep busca una expresión regular | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/19.png) |
| rm {archivo}                        | Borra el archivo especificado                                   | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/20.png) |
| Touch {nombre}                      | Crea un archivo con el nombre indicado                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/21.png) |
| rm -r {folder}                      | Eliminar un folder especificado                                 | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/22.png) |
| rm -Rf {folder}                     | Borra de manera forzada el folder específicado                  | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/23.png) |
| Rm -Rf                              | Borra todo, puede dar el sistema.                               | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/24.png) |
| sudo apt install openssh-server     | Instala el server openssh                                       | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/25.png) |

### Comandos de Utilidades y GitHub

| Comando                                    | Sirve Para                                                                          | Ejemplo                                                                                            |
| ------------------------------------------ | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| scp {archivo} {usuario}@{serverip}:/{ruta} | Secure Copy Protocol, funciona para mover archivos desde local a una máquina remota | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/26.png) |
| git clone {link}                           | Clona desde github                                                                  | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/27.png) |
| curl -X {verbo} -L {link}                  | Hace una petición HTTP al link indicado                                             | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/28.png) |
| wc {ruta}                                  | Cuenta la cantidad de lineas en el archivo                                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/29.png) |
| wc {ruta} -m                               | Cuenta la cantidad de caracteres de un archivo                                      | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/29.png) |
| wc {ruta} -w                               | Cuenta la cantidad de palabras en un archivo                                        | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/30.png) |
| head {ruta}                                | Muestra la primea línea de un archivo                                               | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/31.png) |
| wc {ruta} -n {cantidad}                    | Muestra la cantidad de lineas iniciales del archivo indicado                        | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/32.png) |
| tail {ruta}                                | Muestra las ultimas lineas de un archivo                                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/33.png) |
| less {ruta}                                | Muestra linea por linea el contenido de un archivo                                  | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/34.png) |
| ls -1 / -R                                 | Imprime todas las carpetas del sistema                                              | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/33.png) |
| history                                    | Muestra los comandos ejecutados                                                     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/35.png) |
| history                                    | grep curl {palabra_a_buscar}                                                        | Busca comandos que contengan la palabra indicada                                                   | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/36.png) |
| reboot                                     | Reinicia la computadora                                                             | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/37.png) |
| shutdown                                   | Apaga la computadora                                                                | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/38.png) |
| history                                    | Muestra los comandos ejecutados                                                     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/39.png) |
| grep -r {palabra} {ruta}                   | Busca una palabra en un archivo                                                     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/40.png) |
| find {ruta} -name {nombre}                 | Busca una archivo en una ruta                                                       | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/41.png) |

### Comandos de Docker y Utilidades de Red

| Comando                                 | Sirve Para                                                                                                                     | Ejemplo                                                                                            |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| docker images                           | Muestra las imágenes de docker descargadas                                                                                     | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/42.png) |
| docker pull {imagen}                    | Descarga una imagen de docker                                                                                                  | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/43.png) |
| docker ps -a                            | Muestra todos los contenedores y su respectivo estado                                                                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/44.png) |
| docker history nginx                    | Muestra el historial de una imagen                                                                                             | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/45.png) |
| docker info                             | Muestra información de docker y las configuraciones                                                                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/46.png) |
| docker network ls                       | Muestra las redes creadas por docker                                                                                           | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/47.png) |
| docker info                             | Muestra información de docker y las configuraciones                                                                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/48.png) |
| uname -a                                | Muestra el Kernel del sistema operativo                                                                                        | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/49.png) |
| ifconfig docker()                       | Ver la interfaz de red docker principal                                                                                        | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/50.png) |
| docker network create --driver {nombre} | Crea un driver de red                                                                                                          | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/51.png) |
| ifconfig {red}                          | Muestra ls contenedores que están conectados a una red                                                                         | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/52.png) |
| ifconfig -a                             | Muestra todas las interfaces de red                                                                                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/53.png) |
| docker run -it {imagen}                 | Monta un contendor de docker con la imagen específicada, lo hace de manera con terminal interactiva                            | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/54.png) |
| docker run -it -rm {imagen} bash        | Monta un contendor de docker con la imagen específicada y nos mete a la consola, cuando salgamos del contenedor, se va a parar | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/55.png) |
| docker rmi {imagen}                     | Elimina una imagen específica                                                                                                  | ![alt text](https://github.com/Anderlyn/SISTEMAS_OPERATIVOS_LINUXCMD/blob/main/screenshots/56.png) |
