# Curso de Git, GitHub y GitLab

## Ejemplo de repositorio de curso

Este repositorio contiene el material del curso de Git, GitHub y GitLab impartido por Alejandro Cerezo.

Lo incluimos en un segundo commit para que se pueda ver la diferencia entre el primer commit y el segundo commit. En este caso, el primer commit contiene un archivo README.md con información sobre el curso, mientras que el segundo commit contiene un archivo .editorconfig con configuraciones de estilo de código.

## Comandos de Git

- `git init`: Inicializa un nuevo repositorio de Git en el directorio actual.
- `git add <archivo>`: Agrega un archivo al área de preparación (staging area) para su posterior commit.
- `git commit -m "<mensaje>"`: Crea un nuevo commit con los cambios agregados al área de preparación y un mensaje descriptivo.
- `git log`: Muestra el historial de commits del repositorio, incluyendo los mensajes de
- `git status`: Muestra el estado actual del repositorio, incluyendo los archivos modificados y los cambios pendientes de commit.

## Ramas (Branch)

- `git branch`
- `git checkout` 

## Repositorios remotos

- `git remote add origin <url>`: Agrega un repositorio remoto con el nombre "origin" y la URL especificada.
- `git push -u origin master`: Envía los cambios locales al repositorio remoto "origin" en la rama "master" y establece la rama remota como predeterminada para futuros pushes.
- `git pull origin master`: Obtiene los cambios del repositorio remoto "origin" en la rama "master" y los fusiona con la rama local actual.
