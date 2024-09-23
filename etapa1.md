# Etapa 1

## Problemas a resolver:

### Problema 1

En primer lugar se deberán distribuir tareas y roles dentro del equipo. En la hoja entregable cada miembro debe explicar qué rol le corresponde y qué tareas hará. Tiempo estimado de resolución: 30 min.

### Problema 2

Realizar una secuencia de comandos para crear un repositorio compartido, siguiendo los pasos detallados a continuación:

a.  Uno de los integrantes crea un repositorio local en su máquina con una serie de archivos.
  1. Utilizando la terminal de un IDE, nos posicionamos en el directorio que alojará el proyecto.
  2. “mkdir tio_tpe_2024”: creamos el directorio del proyecto.
  3. “cd tio_tpe_2024”: nos posicionamos dentro del directorio.
  4. “git init”: inicializamos el repositorio.
  5. ”touch .gitignore”: creamos un archivo para ignorar archivos innecesarios.
  6. ”touch .htaccess”: creamos el archivo que contendrá la configuración del servidor.
  7. “touch router.php”: creamos el archivo que enrutará las solicitudes del usuario.
  8. “git add app templates css database images .htaccess router.php”: añadimos los cambios al área de preparación (staging area).
  9.”git commit –m ‘initial proyect setup”: confirmamos los cambios realizados.

b.	Publicar el repositorio en GitHub de forma privada o pública. Todos los archivos del repositorio local creados en el inciso a. deben aparecer en el repositorio remoto alojado en Github.
  1. Ingresamos a nuestra cuenta en GITHUB.
  2. Creamos un nuevo repositorio con nombre “tio_tpe_2024”.
  3. Volvemos a la terminal del IDE.
  4. “git remote add origin https://github.com/dnl243/tio_tpe_2024.git”: enviamos el repositorio a remoto.
  5. ”git push –u origin master”: enviamos los cambios al repositorio remoto.

c.	Invitar a todos los miembros del grupo como colaboradores.
  1. Dentro del proyecto en GITHUB nos dirigimos a “settings”, “collaborators”, y en “manage access” agregamos a los miembros del equipo con “add people”. 

d.	Cada miembro del grupo debe clonar el repositorio en su máquina local.
  1. ”git clone https://github.com/dnl243/tio_tpe_2024.git ”: clonará el repositorio localmente dentro de un directorio con el nombre “tio_tpe_2024”.

En máquina deberán realizar el ejercicio 2 completo. En la hoja entregable deberán indicar qué hicieron en los puntos a, b y d. Tiempo estimado: 10 min

### Problema 3

Gestión de ramas. Cada integrante debe crear un nueva rama en el repositorio con un nombre que refleje la función en el proyecto. Por ejemplo: el desarrollador de frontend, puede nombrar la rama como "frontend"; el tester o QA, puede nombrar la rama como "testing"; y así sucesivamente, asegurándose de que el nombre de la rama sea descriptivo de la tarea.

Escribir el o los comandos git en la hoja entregable. Tiempo estimado: 5 min
  1. ”git checkout –b frontend”

### Problema 4
 
Trabajar en sus respectivas ramas. Simular cambios relevantes en la funcionalidad o aspecto relacionados con el rol en el proyecto. Pueden simular nombres de archivos relativos a las tareas que desarrollan.
 
Ejemplos de posibles puntos donde realizar confirmaciones según cada rol:

Desarrollador de Frontend:
●	Agregar una nueva página de categoría de productos y/o servicios.
●	Modificar la página de gestión de turnos.

●	Mejorar la navegación del sitio, agregando un menú desplegable de navegación o un filtro de búsqueda.

Desarrollador de Backend:

●	Crear un programa para gestionar la autenticación de usuarios y sus datos de perfil.
●	Implementar un sistema de gestión de historias clínicas de mascotas.

Tester o QA:

●	Resolver problemas de navegabilidad de una página a la otra.
●	Crear un programa para reservar turnos en la página.
●	Reportar faltas de ortografía en los textos del front-end.
●	Reportar comportamiento incorrecto de los botones.

Líder:
●	Investigar una nueva tecnología de pago electrónico.

●	Revisar los documentos de diseño y diagramas técnicos realizados por los desarrolladores
●	Averiguar licencias y precios de motores de bases de datos comerciales
●	Conseguir licencia de herramientas de modelado de software.

Para la resolución de este punto deberán entregar las secuencias de acciones para realizar al menos tres confirmaciones. Utilizar nombres representativos para identificar los mensajes de las confirmaciones.

Escribir los comandos git en la hoja entregable. Tiempo estimado: 20 min

### Problema 5

Mostrar las diferencias entre la primera confirmación y la última. Escribir el o los comandos git en la hoja entregable. Tiempo estimado: 3 min
  1.	git log –oneline –graph
  2.	2.git diff <hash 1er commit> <hash último commit>

### Problema 6

Fusionar los cambios que hicieron a la rama principal de proyecto. NO eliminar la rama local. Escribir el o los comandos git en la hoja entregable. Tiempo estimado: 5 min
  1. “git checkout master”: nos posicionamos en la rama master.
  2. ”git merge frontend”: fusionamos la rama en la que trabajamos individualmente. 
### Problema 7

Desde la rama principal, modificar un archivo y confirmar los cambios. Escribir el o los comandos git en la hoja entregable. Tiempo estimado: 5 min

### Problema 8

Crear un commit que deshaga los cambios introducidos en el paso 4. Escribir el o los comandos git en la hoja entregable. Tiempo estimado: 5 min

Anexar a la entrega cualquier otro tipo de información que consideren relevante.

Tiempo total estimado de resolución: 01:30 hs