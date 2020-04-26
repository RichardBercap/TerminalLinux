## Manipulación del Directorio
>En caso de que el propietario de los archivos o directorio pertenezcan a otro usuario y/o tengan permisos delimitados anteceder con la palabra sudo..
### Crear directoios

    mkdir nombre_directorio
### Crear archivos
    touch archivo.txt
### Renombrar carpetas y archivos
    mv -v archivo.txt archivo_nuevo.txt
    mv -v nombre_directorio nuevo_nombre
#### Mover archivos o directorios
    mv nombre_archivo /ruta_directorio
#### Eliminar archivos
    rm nombre_archivo
#### Eliminar directorio
    rm -r nombre_directorio
    rmdir nombre_directorio
#### Vaciar directorio
	rm -r ruta_directorio/*