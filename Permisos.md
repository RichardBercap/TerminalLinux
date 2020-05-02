## Permisos

En el sistema **Unix** los archivos tienen:
* Dueño
* Grupo
* Otros

Los permisos están conformados por:
* Lectura
* Escritura 
* Ejecutar 

### Chmod
Quitar permiso write en nuevo.txt
    
    chmod o-w nuevo.txt
    chmod -w nuevo.txt

### Notación binaria
    111 111 111 = 777

### Listado de usuarios
    cat /etc/passwd
