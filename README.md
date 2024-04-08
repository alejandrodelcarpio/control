# Mi primera Pagina Web
git init # comando para inicializar gitbash en yna carpeta 
# .gitignore Archivo que permite indicar a GIT los archivos que no van a   ser leidos para subir  al repositorio.
# inicializar un directorio existente como repositorio Git
# Este comando solo se hace la primera vez
git init

# mostrar los archivos modificados en el directorio de trabajo, preparados para su próxima confirmación
git status

# || = ó
# añade un archivo tal y como se ve ahora a tu próxima confirmación
git add [archivo] || . 

# confirmar el contenido preparado como una nueva instantánea de confirmación
git commit -m "comentario respecto al cambio"

# subir los cambio a la rama remota
git push origin [nombre-rama]