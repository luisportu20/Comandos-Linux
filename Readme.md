# Comandos-Linux
Este es un  repositorio de comandos de LINUX del curso de sistemas operativos
| Comandos-Linux                 |  Descripción                                                                                                                 | 
| -------------                  | -------------                                                                                                                |
| pwd                            | muestra la ruta del directorio de trabajo actual.                                                                            |
|  cd ..                         | Sirve para ir un directorio hacia atrás                                                                                      |
| cd (nombre de la carpeta/ruta) | Sirve para ir directamente a la carpeta o ruta en específico                                                                 |
| cd                             | Sirve para ir directamente a la carpeta de inicio.                                                                           |
| ls                             | Se usa para ver el contenido de un directorio                                                                                |
| ls-R                           | Listará todos los archivos en los subdirectorios                                                                             |
| ls -a                          | Mostrará los archivos ocultos                                                                                                |
| ls -al                         | Listará los archivos y directorios con información detallada como los permisos, tamaño, proprietario, etc.                   |
| cp                             | Copia los archivos del directorio actual a un directorio diferente. Ejemplo: cp imagen.jpg /home/folder1                     |
| cat (nombre del archivo)       | Crea un nuevo archivo                                                                                                        |
| mv                             | Su uso principal es mover archivos o  cambiar el nombre de los archivos                                                      |
| mkdir                          | Crea un nuevo directorio Ejemplo: mkdir musica                                                                               |
| rm -r                          | Elmina el directorio                                                                                                         |
| touch                          | Permite crear un nuevo archivo en blanco. Ejemplo: touch archivo1                                                            |
| sudo                           | Permite realizar tareas que requieren permisos administrativos o raíz                                                        |  
| top                            | Mostrará una lista de los procesos en ejecución y la cantidad de CPU que utiliza cada proceso                                |
| history                        | Lista los comandos que ingresados anteriormente                                                                              |
| clear                          | Utilizado para limpiar la línea de comandos                                                                                  |
| htop                           | Usado para monitorear los recursos vitales del sistema o los procesos en tiempo real.                                        |       
| su                             | Se usa para obtener permisos de root para operaciones administrativas.                                                       |
| stat                           | Muestra información detallada sobre archivos o sistemas de archivos determinados                                             | 
| file                           | Permite detectar el tipo y formato de un archivo                                                                             |
| chown                          | Se utiliza para cambiar el propietario de archivos del sistema de archivos, directorios.                                     | 
| chmod                          | Permite cambiar o transferir la propiedad de un archivo al nombre de usuario especificado                                    |
| df                             | Es muy útil cuando necesitamos ver el espacio de disco disponible en cada una de las particiones de su sistema.              |
| kill                           | Si se tiene un programa que no responde, se puede cerrar manualmente utilizando el comando kill                              |
| ps                             | Es un comando que permite visualizar el estado de un Proceso.                                                                |
| du                             | Permite verificar cuánto espacio ocupa un archivo o un directorio.                                                           |
| ping                           | verifica el estado de conectividad a un servidor.                                                                            |
| uname                          | Imprimirá información detallada sobre el sistema Linux.                                                                      |
| man                            | Muestra el manual de un comando.                                                                                             |
| echo                           | Permite mover algunos datos a un archivo                                                                                     |
| head - cp                      | Copia los archivos del directorio actual a un directorio diferente. Ejemplo: cp imagen.jpg /home/folder1                     |
| mv                             | Su uso principal es mover archivos o  cambiar el nombre de los archivos                                                      |
| touch                          | Emite crear un nuevo archivo en blanco. Ejemplo: touch archivo1                                                              |
| sudo                           | Permite realizar tareas que requieren permisos administrativos o raíz                                                        |
| top                            | Mostrará una lista de los procesos en ejecución y la cantidad de CPU que utiliza cada proceso                                |
| history                        | Lista los comandos que ingresados anteriormente                                                                              |
| clear                          | Utilizado para limpiar la línea de comandos                                                                                  |
| htop                           | usado para monitorear los recursos vitales del sistema o los procesos en tiempo real.                                        |
| su                             | Se usa para obtener permisos de root para operaciones administrativas.                                                       |
| stat                           | Muestra información detallada sobre archivos o sistemas de archivos determinados                                             |
| file                           | Permite detectar el tipo y formato de un archivo                                                                             |
| chown                          | Cambiar el propietario de archivos del sistema de archivos, directorios                                                      |
| chmod                          | Permite cambiar o transferir la propiedad de un archivo al nombre de usuario especificado                                    |
| df                             | Es muy útil cuando necesitamos ver el espacio de disco disponible en cada una de las particiones de su sistema.              |
| kill                           | Si se tiene un programa que no responde, se puede cerrar manualmente utilizando el comando kill                              |
| ps                             | Es un comando que permite visualizar el estado de un Proceso.                                                                |
| du                             | Permite verificar cuánto espacio ocupa un archivo o un directorio.                                                           |
| ping                           | Verifica el estado de conectividad a un servidor.                                                                            |
| uname                          | Imprimirá información detallada sobre el sistema Linux.                                                                      |
| man                            | Muestra el manual de un comando.                                                                                             |
| echo                           | Permite mover algunos datos a un archivo.                                                                                    |
| head                           | Ver primeras líneas de cualquier archivo de texto, mostrará las primeras 10 líneas, pero se  cambiar este número             |
| diff                           | Compara el contenido de dos archivos línea por línea, Después de analizar los archivos, genera las líneas que no coinciden.  |
| wget                           |  Descargar archivos de Internet.                                                                                             |
| hostname                       | Conocer el nombre de tu host/red, simplemente escribe hostname. Agregar un -I al final mostrará la dirección IP de tu red.a  |
| df                             | Obtener un informe sobre el uso del espacio en disco del sistema, que se muestra en porcentaje y KB o megabytes df -m.       |




|               Comando Docker                    |                                      Descripción                                                              |
|       -----------------                         |                              ------------------                                                               |
| @usuario:/home/usuario$ docker --version        | Encontrar la versión de Docker instalada.                                                                     |
| @usuario:/home/usuario$ docker pull httpd       | Extraer la imagen de la ventana acoplable de Dockerhub.                                                       |
| @usuario:/home/usuario$ docker images           | Todas las imágenes de la ventana acoplable extraídas en el sistema con detalles.                              |
| @usuario:/home/ususario$ docker ps              | Enumera todos los contenedores Docker que se están ejecutando con los detalles del contenedor.                |
| @usuario:/home/usuario$ docker ps -a            | Todos los contenedores de Docker que se ejecutan / salieron / detuvieron con los detalles del contenedor.     |
| @usuario:/home/usuario$ docker rm "ID cont."    | Elimina el contenedor de la ventana acoplable con el ID del contenedor mencionado en el comando.              |
| @usuario:/home/usuario$ docker restart "ID cont"| Reinicia el contenedor de la ventana acoplable con la identificación del contenedor.                          |
| @usuario:/home/usuario$ docker stop "ID cont"   | Detenga un contenedor con el ID de contenedor.                                                                |
| @usuario:/home/usuario$ docker start "ID cont"  | Inicia el contenedor de la ventana acoplable con la identificación del contenedor.                            |
| @usuario:/home/usuario$ docker kill "ID cont"   | Detenga el contenedor Docker inmediatamente.                                                                  |
| @usuario:/home/usuario$ docker commit "ID cont" | Guarde una nueva imagen de Docker con el ID de contenedor mencionado en el sistema local.                     |
| @usuario:/home/usuario$ docker login            | Inicie sesión en Docker Hub. Se pedirán las credenciales de su Docker Hub para iniciar sesión.                |
| @usuario:/home/usuario$ docker network ls       | Enumera los detalles de toda la red en el clúster.                                                            |
| @usuario:/home/usuario$ docker info             | Información detallada sobre la ventana acoplable instalada en el sistema.                                     |
| @usuario:/home/usuario$ docker history httpd    | Muestra el historial de una imagen de la ventana acoplable con el nombre de la imagen                         |
| @usuario:/home/usuario$ docker search hadoop    | Busque una imagen de docker en dockerhub con el nombre mencionado en el comando.                              |
| @usuario:/home/usuario$ docker update --help    | Actualiza las configuraciones de contenedores. Esto muestra todas las opciones de actualización.              |
| @usuario:/home/usuario$ docker volume create    | Crea un volumen que el contenedor de la ventana acoplable utilizará para almacenar datos.                     |
| @usuario:/home/usuario$ docker volume ls        |  Comando para ver si el volumen se creó o no.                                                                 |
| ''    docker plugin install vieux/sshfs DEBUG=1 | Instale un complemento de docker vieux/sshfs con el entorno de depuración establecido en 1.                   |
| @usuario:/home/usuario$ docker logout           |  Cerrar sesión en dockerhub.                                                                                  |
