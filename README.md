# THE TERMINAL</br>
## COMANDOS PARA BORRAR ARCHIVOS </br>
### Crear un directorio llamado test </br>
```bash
mkdir test
```
### Listar los elementos dentro de un directorio actual
```bash
ls
```
### Listar los elementos del directorio superior
```bash
ls ../
```
### Listar todo el contenido incluyendo los archivos ocultos
```bash
ls -al
```
### Borrar todos los elementos
```bash
rm 'file_name'
```

### Mover archivos
```bash
mv 'file_name'
```
#### Por ejemplo, en el siguiente c�digo se mueve el archivo hacia la parte superior
```bash
mv ../test.py
```
### Borrar un directorio. Para borrar un directorio primero se debe borrar todos los elementos internos.
```bash
rmdir test/
```
Otros comandos

- __ls -t__ es para ordenar los archivos por fecha de modificaci�n
- __ls -x__ ordena primero por nombre y luego por extensi�n
- __ls -X__ ordena primero por extensi�n y luego por nombre
- __ls -l__ muestra toda la informaci�n: usuario, grupo, permisos, tama�o, fecha y hora de creaci�n.
- __ls -lh__ muestra lo mismo que ls -l pero con unidades de tama�o de KM, MB.
- __ls -R__ muestra el contenido de todos los subdirectorios de forma recursiva
- __ls -S__ Ordena los resultados por tama�o de archivo
- __pwd__ Print Working Directory, se usa para mostrar el directorio actual en el que nos encontranmos trabajando.
- __cd__ se usa para cambiar el directorio
- __cp carpetaOrigen carpetaDestino __ copiar un archivo

