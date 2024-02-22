#  Comando para listar las ramas

    git branch

# Comando para crear una nueva rama

    git branch nombre_nueva_rama

# Comando para eliminar una rama

    git branch -D (nombre de la rama)

# Comando para navegar entre ramas

    git checkout (nombre de la rama)

    git swtich (nombre de la rama)

    git checkout -b (nombre de la rama) => Creamos la rama y nos cambiamos de una vez a la nueva rama


# Desvincular un archivo que se le estaba dando segumiento

    git rm --cached nombre_archivo

# Crear una nueva version con archivos que ya se le estaban dando seguimiento

    git commit -am "Nombre del commit"

# Comando para unir ramas

    git merge nombre_rama