# Practica 1: Introducción a Git

# Descripción:
> Este proyecto contiene un programa basico en Python que imprime un mensaje en la consola. La practica tiene el objetivo de reforzar los conocimientos de GIT y GitHub, incluyendo la creación de commits, el uso de '.gitignore' y la carga de archivos a un repositorio remoto en GitHub.

# Instrucciones de uso:

> Para ejecutar el programa "HolaMundo.py" asegurate de tener Python instalado. Despues desde la terminal navega a la carpeta donde se encuentra el archivo y ejecuta el siguiente comando:

```
python HolaMundo.py

```

# Comandos utilizados

| Comando | Descripción |
| --- | --- |
| `git init` | Inicializa un nuevo repositorio Git |
| `git add HolaMundo.py` | Añade el archivo `HolaMundo.py` |
| `git commit -m "Se agrego el programa de Hola Mundo en Python"` | Realiza el primer commit |
| `git add .gitignore` | Añade el archivo `.gitignore` |
| `git commit -m "Se agrego el archivo .gitignore"` | Realiza el segundo commit |
| `git status` | Verifica el estado del repositorio |
| `git add HolaMundo.py` | Añade el archivo actualizado `HolaMundo.py` |
| `git commit -m "Se actualizó el mensaje en HolaMundo.py"` | Realiza el tercer commit |
| `git remote add origin https://github.com/UserName/ProyectoEjemploGit.git` | Conecta el repositorio local al remoto en GitHub |
| `git push -u origin master` | Sube los cambios al repositorio remoto |

# Notas sobre el archivo .gitignore

> El archivo `.gitignore` se creo para indicar a Git que debe ignorar ciertos archivos que no se deben incluir en el repositorio, en este caso debe ignorar los archivos con extensión `.log`, como `debug.log`, esto para evitar que se suba al repositorio por se archivos de registro.

> Al ejecutar el programa este debe mostrar el siguiente mensaje en la terminal:

```
Hola git

```
> Para verificar que `debug.log` no se subio podemos usar el comando `git status`, este no debe listar este archivo entre los archivos no rastreados