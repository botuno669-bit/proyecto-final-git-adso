Taller Git y Git Hub



Objetivo del Proyecto



El objetivo de este proyecto es aplicar el uso de Git y GitHub para gestionar el control de versiones de un proyecto real, utilizando ramas, commits, fusión de cambios, solución de conflictos y repositorios remotos. El proyecto busca que el estudiante aprenda a trabajar de forma organizada, segura y colaborativa utilizando buenas prácticas de control de versiones.



Integrante



Juan Sebastian Bonilla Arias



Fecha



24 de noviembre de 2025



¿Qué es Git?



Git es un sistema de control de versiones distribuido utilizado para llevar el registro del historial de cambios en proyectos de software. Permite que varios desarrolladores trabajen simultáneamente sin perder versiones ni sobrescribir el trabajo de otros. Con Git es posible crear copias completas de un repositorio, comparar versiones, volver atrás si ocurre un error y fusionar diferentes desarrollos que ocurren en paralelo.

Funciona mediante snapshots que almacenan estados del proyecto cada vez que se realiza un commit, asegurando así trazabilidad total. Además, ofrece herramientas para trabajar tanto localmente como de manera remota con plataformas como GitHub, lo que facilita la colaboración y profesionaliza el flujo de trabajo en el desarrollo de software.



10 Comandos de Git Explicados

Comando	Explicación

git init	Crea un repositorio de Git en una carpeta.

git clone <url>	Descarga un repositorio remoto a la computadora.

git status	Muestra el estado del repositorio (archivos modificados, nuevos, etc.).

git add <archivo>	Agrega un archivo al área de preparación (staging).

git commit -m "mensaje"	Guarda un snapshot del proyecto con un mensaje descriptivo.

git log	Muestra el historial de commits del proyecto.

git branch	Lista las ramas del repositorio.

git checkout <rama>	Cambia a una rama distinta.

git merge <rama>	Fusiona otra rama con la actual.

git push	Sube los cambios al repositorio remoto.



Flujo de Trabajo Recomendado



Actualizar el repositorio local



git pull





Crear una nueva rama para la tarea a realizar



git checkout -b nombre-de-rama





Realizar cambios en el código.



Agregar los archivos al staging



git add .





Crear un commit con mensaje descriptivo



git commit -m "Descripción clara del cambio"





Subir la rama al remoto



git push -u origin nombre-de-rama





Crear un Pull Request en GitHub.



Revisar y fusionar cuando esté aprobado.



Repetir para nuevas tareas.



Problemas Encontrados Hoy



Error 403 al intentar hacer push debido a que Git estaba usando credenciales de otro usuario.



Git Bash había guardado un usuario diferente en el Administrador de Credenciales.



Se tuvo que eliminar el registro y volver a autenticarse con la cuenta correcta.



Conclusión del Día



Hoy se logró avanzar en el manejo de Git y GitHub comprendiendo mejor cómo funciona el sistema de credenciales, repositorios remotos y errores de autenticación. Se reforzó el conocimiento del flujo profesional de trabajo con ramas y commits, mejorando las habilidades para trabajar con control de versiones en proyectos reales y colaborativos.

