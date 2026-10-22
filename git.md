# 2. Sistemas de control de versiones: Git

## ¿Qué es el control de versiones?

El control de versiones es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, de manera que sea posible recuperar versiones específicas posteriormente.

Permite volver a estados anteriores, comparar cambios, consultar quién modificó por última vez un archivo e investigar cuándo se introdujo un error. También facilita recuperar archivos si se pierden o se estropean.

## Tipos de sistemas de control de versiones

### Sistemas locales

Mantienen una base de datos local en la que se registra el historial de cambios de los archivos.

### Sistemas centralizados

Disponen de un único servidor que contiene los archivos versionados. Los colaboradores obtienen los archivos desde ese servidor central.

### Sistemas distribuidos

Cada colaborador no descarga únicamente la última versión de los archivos, sino que puede tener una copia completa del repositorio. Esto permite recuperar el proyecto a partir de otra copia si el servidor deja de funcionar.

## ¿Qué es Git?

Git es un sistema de control de versiones distribuido. Se utiliza para registrar y gestionar los cambios de un proyecto y facilitar el trabajo conjunto de varias personas.

## Las tres áreas de Git

1. **Working (área de trabajo):** directorio en el que se editan los archivos.
2. **Staging (área de preparación):** zona donde se seleccionan los archivos cuyos cambios se quieren guardar en la siguiente versión.
3. **Repository (repositorio):** lugar donde se almacenan los datos y los cambios registrados.

## Comandos básicos

```bash
git status
git add archivo.md
git commit -m "Añade documentación"
git log
git push
git pull
```

- `git status`: consulta el estado de los archivos.
- `git add`: prepara los cambios seleccionados.
- `git commit`: registra los cambios en el repositorio local.
- `git log`: consulta el historial.
- `git push`: envía cambios al repositorio remoto.
- `git pull`: obtiene e integra cambios del repositorio remoto.

Los commits deben tener mensajes breves y claros para que el historial sea fácil de entender.
