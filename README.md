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
#### Por ejemplo, en el siguiente código se mueve el archivo hacia la parte superior
```bash
mv ../test.py
```
### Borrar un directorio. Para borrar un directorio primero se debe borrar todos los elementos internos.
```bash
rmdir test/
```
Otros comandos

- ls -t es para ordenar los archivos por fecha de modificación
- ls -x ordena primero por nombre y luego por extensión
