20 COMANDOS DE GIT

- - 1
- Comando: git init 
- descripccion: inicializa un repositorio git en una carpeta.
- ejemplo de uso: git init

- - 2
- Comando: git clone
- descripccion: Copia un repositorio remoto a tu computadora.
- ejemplo de uso: git clone <url>

- - 3
- Comando: git add    
- descripccion: Agrega varios archivos al índice
- ejemplo de uso: git add <nombredearchivo>

- - 4
- Comando: git status 
- descripccion:Lista un estado actual del repositorio con lista de archivos modificados o agregados
- ejemplo de uso: git status

- - 5
- Comando: git commit
- descripccion: Guarda los cambios preparados en el historial.
- ejemplo de uso: git commit -m "Mensaje del commit"

- - 6
- Comando: git log
- descripccion: El comando git log muestra el historial de commits en orden cronológico inverso.
- ejemplo de uso: git log

- 7
- Comando: git show
- descripccion:El comando git show muestra la información de un commit. El mensaje se divide en dos bloques: la parte con los metadatos y la lista de cambios realizados en el commit
- ejemplo de uso: git show abc12345  # Solicita ver el commit con el hash abc12345

- - 8
- Comando: git diff
- descripccion: Muestra los cambios realizados a un archivo
- ejemplo de uso: git diff 
	git diff --staged

- - 9
- Comando: git restore
- descripccion:El comando git restore devuelve un archivo al estado del último commit. Deshace todos los cambios si el archivo no se ha transferido al índice. 
- ejemplo de uso: git restore nombre_de_archivo

- - 10
- Comando: git rm
- descripccion: El comando git rm permite eliminar un archivo que se ha añadido al índice por error.
- ejemplo de uso: git rm nombre_de_archivo

- - 11
- Comando: git branch <nombre_de_rama>
- descripccion: Crea un branch
- ejemplo de uso: git branch <nameBranch>

- - 12
- Comando: git branch
- descripccion: El comando git branch permite obtener una lista de todas las ramas disponibles en el proyecto. 
- ejemplo de uso: git branch

- - 13
- Comando: git checkout
- descripccion:El comando git checkout permite cambiar de una rama a otra
- ejemplo de uso: git checkout nombre_de_rama

- - 14
- Comando: git merge
- descripccion: El comando git merge permite añadir cambios de una rama a otra.
- ejemplo de uso:
Cambia a la rama principal que recibirá los cambios
- git checkout rama_principal

 Fusiona los cambios de la rama secundaria a la principal
- git merge rama_secundaria
- 
- - 15
- Comando:  git pull
- descripccion: El comando git pull descarga los cambios del repositorio remoto al local.
- ejemplo de uso: git pull

- - 16
- Comando: git remote -v
- descripccion: El comando git remote solo muestra los nombres de los repositorios remotos vinculados al tuyo. 
- ejemplo de uso: git remote -v

- - 17
- Comando: git remote
- descripccion: Si introduces el comando git remote, puedes ver los nombres de estos repositorios y eliminar los innecesarios.
- ejemplo de uso: git remote

- - 18
- Comando:git reset
- descripccion:El comando git reset permite deshacer cualquier cantidad de commits realizados y devolver el proyecto a un estado anterior
- ejemplo de uso: git reset

- - 19
- Comando: git add docs/
- descripccion: Añadimos todos los archivos dentro de un directorios
- ejemplo de uso:	git add docs/


- - 20
- Comando: git tag
- descripccion: Muestra una lista de todos los tags
- ejemplo de uso: 	git tag
