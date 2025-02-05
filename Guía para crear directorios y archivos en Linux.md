# Guía para crear directorios y archivos en Linux
## 1. Crear una carpeta
```bash
mkdir carpeta1
```
## 2. Dentro de una carpeta crear un archivo llamado "file1"
```bash
touch file1
```
## 3. Dentro de una carpeta crear un directorio llamado "subdirectorio1"
```bash
mkdir subdirectorio1
```
## 4. Ir al directorio raíz
```bash
cd /
```
## 5. Desde el directorio raiz crear un directorio
```bash
mkdir /home/adriana/[carpeta]/[directorio]
```
## 6. Regresar al directorio home
```bash
cd ~
```
## 7. Mostrar en la carpeta que está
```bash
pwd
```
## 8. Mostrar el arbol del home del usuario
```bash
tree
```
## 9. listar archivos y directorios de una carpeta 
```bash
ls -l [su_carpeta]
```
## 10. Editar el archivo file1
```bash
nano carpeta/file1
```
## 11.  Mostrar el historial hasta ahora
```bash
history
```
## 12.  Entrar en el directorio subdirectorio [del # 5]
```bash
cd carpeta/subdirectorio1
```
## 13. Crear un archivo dentro de folder1 llamado file1
```bash
cd /home/adriana/carpeta/subdirectorio1/folder1
touch file2
```
## 14. Eliminar una carpeta
```bash
rmdir carpeta
```
## 15. Crear usuario
```bash
sudo useradd [el_usuario]
```
## 16. Crear contraseña del usuario
```bash
sudo passwd [el_usuario]
y despues escribes la contraseña
```
## 16. Crear grupo
```bash
sudo groupadd [el_grupo]
```
## 16. Ver grupos creados 
```bash
less /etc/group
```
## 16. Asignar user a un grupo
```bash
sudo usermod -aG grupo usuario
```
## 16. Ver a cuales grupo pertenece un usuario
```bash
groups [el_usuario]
```
