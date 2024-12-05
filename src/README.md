# 1. Primer exercici

# 1.1.1 Desde tu carpeta principal (~/), crea un directorio llamado GitApellido1Nombre2425.
  En wl 1.3 se be como lo e echo con mkdir
# 1.1.2 Dentro del directorio GitApellido1Nombre2425, crea una subcarpeta llamada src usando rutas relativas.
  He usado mkdir para crearlo
# 1.1.3 Crea un archivo README.md en GitApellido1Nombre2425 con una breve descripción del proyecto, usa costantemente el terminal.
  Usado touch para crearlo
! [Imagen de los tres primetros apartados](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 08-31-43.png)
# 1.2.1 Entra en el directorio y conviértelo en un repositorio Git.
  iniciamos el repositorio y subimos el src
! [Imagen de icializar repositorio](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 08-33-49.png)
! [Imagen comit del src](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 08-39-21.png)
# 1.2.2 Agrega un archivo .gitignore y configúralo para ignorar archivos de log y carpetas de configuración temporales.
comandos usados
! [Imagen de .gitignore](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 09-06-46.png)
# 1.2.3 ¿Qué es el archivo .gitignore y para que sirve?
Es un arxivo de texto que sirve para especificar qué archivos o directorios no deben ser seguidos, 
versionados ni almacenados en el repositorio de Git.
# 1.2.4 Crea una estructura básica de web index.html, style.css, main.js.
creados agragados i commit echo
! [comentario](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 09-17-23.png)
# 1.3.1 Haz un git add de todos los archivos y realiza un commit inicial con el mensaje:
Devdo a que ja esta echo are un commit de los cambios
! [comentario](/home/oriol.canellas.7e3/Imatges/Captures de pantallaCaptura de pantalla de 2024-11-28 09-21-51.png)
# 2.1.1 Entra en GitHub y crea un repositorio.
Creacion de un repositorio con README
! [imagen de creacion](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 09-28-32.png)
! [Completada creacio](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 09-31-14.png)
# 2.1.2 ¿Qué pasa si creo un repositorio con el archivo README.md desde GitHub?
pasa que te viene con una fitxero README i que te hace un comit directamente
# 2.1.3 ¿Qué pasa si crea un repositorio sin el archivo README.md desde GitHub?
Que te viene sin el README y sin el commit autromatico
# 2.1.4 Explica las diferencias entre las 2 preguntas anteriores.
Uno te lo hacea todo directamente(Crear con README) y el otro no pero si te da comandos para empezar
# 2.1.5 Indica que comandos te da GitHub al crear un repositorio. Los encontrarás en el apartado …or create a new repository on the command line 
aqui esta
! [comentario](/home/oriol.canellas.7e3/Imatges/Captures de pantallaCaptura de pantalla de 2024-11-28 09-40-07.png)
# 2.1.6 Vincula el repositorio remoto con el repositorio local.
primera part
! [perimera part](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-11-28 09-46-27.png)
segona part
! [segona part](/home/oriol.canellas.7e3/Imatges/Captures de pantalla/Captura de pantalla de 2024-12->
# 2.2.1 Crea una nueva rama llamada feature/documentacion y cámbiate a ella. 
! [creada](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-26-20.png)
# 2.2.2 Cambia a la nueva rama:
# Crea un archivo docs.md en la carpeta raíz. Escribe un resumen de las funcionalidades del proyecto.
# Haz un commit con el mensaje:
# Agregada documentación inicial del proyecto.
! [crecio](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-35-53.png)
! [comit realitzat](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-40-29.png)
# 2.2.3 Cambia a la rama main y usa git diff para comparar las diferencias entre main y feature/docu>
! [cambia de branca](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-42-00.png)
! [diff realitzat](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-45-37.png)
# 2.3 Desde la rama main, realiza un git pull para simular la descarga de cambios del remoto. Si hay>
! [git pull fet sense provlemas](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 0>
# 3.1.1 Crea un nuevo archivo llamado src/app.py con un mensaje básico (print("Hola, mundo!")).
# 3.3.2 Haz un add y luego un commit. Verifica su estado con  status o con algún comando alias que h>
# 3.1.3 Visualiza el historial de commit con log o con algún comando alias que hayas creado tú.
# 3.1.4 Si has utilizado comandos alias, indica el equivalente al comando alias. Por ejemplo, mi com>
! [3.1.1 3.1.2](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-56-43.png)
! [3.1.3](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 08-59-27.png)
3.1.4 comando alias git cm para los commits y git s para el status
# 3.2 Borra el archivo src/app.py usando un comando de terminal. Recupera el archivo con el comando >
! [Borrar fixer](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 09-10-06.png)
! [recuperat](/home/oriol.canellas.7e3/Imatges/Captura de pantalla de 2024-12-05 09-16-38.png)
# 3.3.1 Desde main, haz un merge de feature/documentacion.
# 3.3.2 Usa log o un alias para verificar los cambios realizados y el historial.
! [fet sense commit](/home/oriol.canellas.7e3/Imatges/)

