# Curso git

En este repositorio se encuentran las notas del curso de git y github impartido por ESCOM-IPN.
NOTA: la pagina web solo es para hacer pruebas.

## Comandos

### git init

Crea un repositorio de git ya sea un proyecto existente y sin versión o simplemente uno vacío.

```git init```

### git add

Añade un cambio en el directorio de trabajo en lo que se conoce como staging.

Añadir un archivo:

```git add archivo```

Añadir todos los cambios:

```git add .```

### git commit

Aceptar o confirmar los cambios hechos en un directorio de trabajo.

```git commit -m "descripción del cambio realizado"```

### git status

Ver cambios actuales al proyectos que aún no se han añadido al staging.

```git status```

### git log

Muestra un historial de los cambios realizados en un directorio de trabajo.

```git log```

### git show

Muestra varios tipos de objetos ya sean blobs, ramas, commits, etc.

```git show [<opciones>] [<objeto>]```

### git diff

Compara los cambios entre dos commits, se deben insertar los códigos de los respectivos commits, estos
pueden ser vistos con git log.

```git diff commitA commitB```

### git rm

Elimina los archivos de git especificados.

```git rm archivos```

### git branch

Crea una rama a partir del trabajo actual. 

Mostrar la rama de trabajo actual:

```git branch```

Crear rama:

```git branch nombre```

### git checkout

Permite moverte a cierta rama.

```git checkout nombre_rama```