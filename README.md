## Documentación de Ubuntu Server 22

####Comandos de Usuarios
                
+ Crear Un Nuevo Usuario
    + sudo adduser nombre_de_usuario
  
+ Dar permisos al Usuario
    * sudo usermod -aG nuevo_grupo nombre_de_usuario
###### - Para agregar un usuario a un grupo 
    * sudo usermod -aG sudo nombre_de_usuario
###### - Para agregar a un usuario al grupo de sudo


+ Verificar Permisos
		ls -l ruta_del_archivo_o_directorio
###### - Ver permisos de archivos/directorios Puedes usar el comando ls con la opción -l para ver los permisos de archivos y directorios


		id nombre_de_usuario
###### - Verificar Cambios 


		su nombre_usuario
###### - Cambiar de usuario sin salir de consola
