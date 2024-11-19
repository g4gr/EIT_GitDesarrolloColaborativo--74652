# Comandos UNIX

## Listar carpeta

`ls` ( List Directory ) : Listar los directorios
`ls -l` ( List Directory + Long View ) : Permite ver el listado de archivos y carpetas con más detalles
`ls -la` ( List Directory + Hidden ) : Permite ver el listado de archivos y ccarpeta completo, incluyendo a los que están ocultos a simple vista
`ls -lah` ( List Directory + Human View ) : Permite ver el listado de archivos y carpetas con las tamaños expresado en Kb

---

## Navegar

`cd` ( Change Directory ) : Cambiar de directorio --> 'cd [ Carpeta ]'
`cd ..` ( Change Directory + Up ) : Cambiar de directorio hacia arriba --> 'cd ..'
`cd ~` ( Change Directory + Home ) : Cambiar de directorio hacia mi carpeta Home --> 'cd ~'

---

## Mover
`mv` ( Move ) : Mover archivos --> 'mv [ Nombre Archivo ] [ Carpeta Destino ]/
`mv` ( Move ) : Renombrar Archivos --> 'mv [ Archivo + Extension ] [ Nuevo Nombre + Extension ]/

---

## Eliminar

`rm` ( Remove ) : Eliminar Archivos --> 'rm [ Archivo ]'
`rm -rd` ( Remove ) : Eliminar Carpetas --> 'rm -r [ Carpeta ]'
`rm -rdf` ( Remove + Recursive ) : Eliminar Carpetas y sus contenidos --> 'rm -rdf [ Carpeta ]'

---

## Crear archivos y carpetas

`touch` ( Touch ) : Crear Archivos --> 'touch [ Archivo ]'
`mkdir` ( Make Directory ) : Crear Carpetas --> 'mkdir [ Carpeta ]'

---

## Copiar

`cp` ( Copy ) : Copiar Archivos --> 'cp [ Archivo ]'
`cp -r` ( Copy + Recursive ) : Copiar Carpetas y sus contenidos --> 'cp -r [ Carpeta ]'
pwd ( Ruta Absoluta ) : Conocer la ruta absoluta hasta mi ubicación actual.



---
# Git

## Comandos de consulta de Git

`git --version` ( Version ) : Muestra la versión de Git instalada.
`git -v` ( Version corta ) : Muestra la versión de Git instalada.
`git status` ( Status ) : Muestra el estado de los archivos en el directorio actual.


`git add` ( Add ) : Añade archivos a la lista de cambios.
`git commit` ( Commit ) : Crea un nuevo commit.
`git log` ( Log ) : Muestra el historial de commits.
`git log --oneline` ( Log + Oneline ) : Muestra el historial de commits en una sola línea.
`git show` ( Show ) : Muestra el contenido de un commit.
`git diff` ( Diff ) : Muestra las diferencias entre dos commits.

## Comandos de gestión de git
`git config --local user.name "Nombre"` ( Config + Local + Name ) : Configura el nombre del usuario.
`git config --local user.email "Email"` ( Config + Local + Email ) : Configura el email del usuario.
`git config --global user.name "Nombre"` ( Config + Global + Name ) : Configura el nombre del usuario.
`git config --global user.email "Email"` ( Config + Global + Email ) : Configura el email del usuario.

--
## Scopes de Git
- **Local**: Configuración local para el repositorio actual.
- **Global**: Configuración global para el repositorio actual.
- **System**: Configuración global para el sistema.
