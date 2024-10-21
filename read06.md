# READ 06: Developer Tools

## ¿Qué hacen los siguientes comandos?

- `pwd`: Muestra la ruta del directorio de trabajo actual.
- `ls`: Lista el contenido de un directorio.
- `cd`: Cambia el directorio actual.
- `mkdir`: Crea un nuevo directorio.
- `touch`: Crea un archivo vacío o actualiza la fecha y hora de un archivo existente.

## Escenario en la línea de comandos

A continuación se explica lo que sucede si ingresas estos comandos y argumentos en la línea de comandos:

1. <span style="color:blue">cd projects</span>   
   Cambia el directorio actual a la carpeta "projects" (si existe en el directorio actual).

2. `mkdir new-project`  
   Crea un nuevo directorio llamado "new-project" dentro de "projects".

3. `touch new-project/newfile.md`  
   Crea un nuevo archivo llamado "newfile.md" dentro del directorio "new-project".

4. `cd ..`  
   Vuelve al directorio superior (el directorio padre de "projects").

5. `ls projects/new-project`  
   Lista los archivos dentro de "new-project", mostrando "newfile.md".

## Listar archivos ocultos en Linux o macOS

Para listar todos los archivos, incluidos los ocultos, en un directorio de Linux o macOS, usarías el siguiente comando:

```bash
ls -a
