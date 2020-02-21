creo un reopsitorio nuevo en github.
copio la url del repositorio.
creo una carpeta en el escritorio
hago git clone url del repositorio para clonar el repositorio en mi archivo local.
introduzco notepad README.md para crear el archivo.
- para hacer el commit primero hago:
git add .
git commit -m "commit inicial"
git push -u origin master
ignorar archivos:
creo el fichero con el comando: notepad privado.txt
creo la carpeta llamada privada: mkdir privado
para ignorar estos ficheros:
creo el archivo .gitignore en repositorio local.
dentro de .gitignore escribo:
privado.txt
privado
(para que me ignore el commit de estos archivos).

notepad 1.txt
git tag v0.1
git add .
git commit -m "tag v0.1" 
