# Ejercicios Infraestructura de datos - Grupo N°7

    1. Camila Vidoni (camilavidoni7@gmail.com - camilavidoni)
    2. Gastón Rossi (gastonricardorossi@gmail.com - torino05)
    3. Alex Flores  (alexfloresunsam@gmail.com - afloreschoquehuanca-byte)  
    4. Morena Stolerman (morenastolerman@gmail.com - morenastolerman)
    5. Gonzalo Cárdenas (goncar1235@gmail.com - zagon22)
    6. Gabriela Gattas (evalauh@yahoo.com - Gabi6285)

## <ins>Ejercicios de creación y actualización de repositorios</ins>
### Ejercicio 1
Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida.<br>
Mostrar la configuración final.<br>

### Ejercicio 2
Crear un repositorio nuevo con el nombre libro y mostrar su contenido.<br>

### Ejercicio 3
Comprobar el estado del repositorio.<br>
Crear un fichero <ins>indice.txt</ins> con el siguiente contenido:<br>

    Capítulo 1: Introducción a Git
    Capítulo 2: Flujo de trabajo básico
    Capítulo 3: Repositorios remotos

Comprobar de nuevo el estado del repositorio.<br>
Añadir el fichero a la zona de intercambio temporal.<br>
Volver a comprobar una vez más el estado del repositorio.<br>

### Ejercicio 4
Realizar un commit de los últimos cambios con el mensaje *“Añadido índice del libro.”* y ver el estado del repositorio.

### Ejercicio 5
Cambiar el fichero <ins>indice.txt</ins> para que contenga lo siguiente:<br>

    Capítulo 1: Introducción a Git
    Capítulo 2: Flujo de trabajo básico
    Capítulo 3: Gestión de ramas
    Capítulo 4: Repositorios remotos

Mostrar los cambios con respecto a la última versión guardada en el repositorio.<br>
Hacer un commit de los cambios con el mensaje *“Añadido capítulo 3 sobre gestión de ramas”*.<br>

### Ejercicio 6
Mostrar los cambios de la última versión del repositorio con respecto a la anterior.<br>
Cambiar el mensaje del último commit por *“Añadido capítulo 3 sobre gestión de ramas al índice”*.<br>
Volver a mostrar los últimos cambios del repositorio.<br>

## <ins>Ejercicios de manejo del historial de cambios</ins>
### Ejercicio 1
Mostrar el historial de cambios del repositorio.<br>
Crear la carpeta capítulos y crear dentro de ella el fichero <ins>capitulo1.txt</ins> con el siguiente texto.<br>

    Git es un sistema de control de versiones ideado por Linus Torvalds.

Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit de los cambios con el mensaje *“Añadido capítulo 1”*. Volver a mostrar el historial de cambios del repositorio.<br>

### Ejercicio 2
Crear el fichero <ins>capitulo2.txt</ins> en la carpeta capítulos con el siguiente texto.<br>
    El flujo de trabajo básico con Git consiste en: 1. Hacer cambios en el repositorio. 2. Añadir los cambios a la zona de intercambio temporal. 3. Hacer un commit de los cambios.
Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit de los cambios con el mensaje *“Añadido capítulo 2”*.<br>
Mostrar las diferencias entre la última versión y dos versiones anteriores.<br>

### Ejercicio 3
Crear el fichero capitulo3.txt en la carpeta capítulos con el siguiente texto.<br>
    Git permite la creación de ramas lo que permite tener distintas versiones del mismo proyecto y trabajar de manera simultánea en ellas.
Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit de los cambios con el mensaje *“Añadido capítulo 3”*.<br>
Mostrar las diferencias entre la primera y la última versión del repositorio.<br>

### Ejercicio 4
Añadir al final del fichero indice.txt la siguiente línea:<br>
    Capítulo 5: Conceptos avanzados
Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit de los cambios con el mensaje *“Añadido capítulo 5 al índice”*.<br>
Mostrar quién ha hecho cambios sobre el fichero <ins>indice.txt</ins>.<br>

## <ins>Ejercicios de deshacer cambios</ins>
### Ejercicio 1
Eliminar la última línea del fichero indice.txt y guardarlo.<br>
Comprobar el estado del repositorio.<br>
Deshacer los cambios realizados en el fichero <ins>indice.txt</ins> para volver a la versión anterior del fichero.<br>
Volver a comprobar el estado del repositorio.<br>

### Ejercicio 2
Eliminar la última línea del fichero <ins>indice.txt</ins> y guardarlo.<br>
Añadir los cambios a la zona de intercambio temporal.<br>
Comprobar de nuevo el estado del repositorio.<br>
Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.<br>
Comprobar de nuevo el estado del repositorio.<br>
Deshacer los cambios realizados en el fichero <ins>indice.txt</ins> para volver a la versión anterior del fichero.<br>
Volver a comprobar el estado del repositorio.<br>

### Ejercicio 3
Eliminar la última línea del fichero indice.txt y guardarlo.<br>
Eliminar el fichero <ins>capitulos/capitulo3.txt</ins>.<br>
Añadir un fichero nuevo <ins>capitulos/capitulo4.txt</ins> vacío.<br>
Añadir los cambios a la zona de intercambio temporal.<br>
Comprobar de nuevo el estado del repositorio.<br>
Quitar los cambios de la zona de intercambio temporal, pero mantenerlos en el directorio de trabajo.<br>
Comprobar de nuevo el estado del repositorio.<br>
Deshacer los cambios realizados para volver a la versión del repositorio.<br>
Volver a comprobar el estado del repositorio.<br>

### Ejercicio 4
Eliminar la última línea del fichero <ins>indice.txt</ins> y guardarlo.<br>
Eliminar el fichero <ins>capitulos/capitulo3.txt</ins>.<br>
Añadir los cambios a la zona de intercambio temporal y hacer un commit con el mensaje *“Borrado accidental”*.<br>
Comprobar el historial del repositorio.<br>
Deshacer el último commit pero mantener los cambios anteriores en el directorio de trabajo y la zona de intercambio temporal.<br>
Comprobar el historial y el estado del repositorio.<br>
Volver a hacer el commit con el mismo mensaje de antes.<br>
Deshacer el último commit y los cambios anteriores del directorio de trabajo volviendo a la versión anterior del repositorio.<br>
Comprobar de nuevo el historial y el estado del repositorio.<br>

## <ins>Ejercicios de repositorios remotos</ins>
### Ejercicio 1
Crear un nuevo repositorio público en GitHub con el nombre <ins>libro-git</ins>.<br>
Añadirlo al repositorio local del libro.<br>
Mostrar todos los repositorios remotos configurados.<br>

### Ejercicio 2
Añadir los cambios del repositorio local al repositorio remoto de GitHub.<br>
Acceder a GitHub y comprobar que se han subido los cambios mostrando el historial de versiones.<br>

### Ejercicio 3
Colaborar en el repositorio remoto <ins>libro-git</ins> de otro usuario.<br>
Clonar su repositorio <ins>libro-git</ins>.<br>
Añadir el fichero <ins>autores.txt</ins> que contenga el nombre del usuario y su correo electrónico.<br>
Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit con el mensaje *“Añadido autor”*.<br>
Subir los cambios al repositorio remoto.<br>

### Ejercicio 4
Hacer una bifurcación del repositorio remoto <ins>asalber/libro-git</ins> en GitHub.<br>
Clonar el repositorio creado en la cuenta de GitHub del usuario.<br>
Crear una nueva rama <ins>autoría</ins> y activarla.<br>
Añadir el nombre del usuario y su correo al fichero <ins>autores.txt</ins>.<br>
Añadir los cambios a la zona de intercambio temporal.<br>
Hacer un commit con el mensaje *“Añadido nuevo autor”*.<br>
Subir los cambios de la rama autoria al repositorio remoto en GitHub.<br>
Hacer un Pull Request de los cambios en la rama <ins>autoría</ins>.<br>
