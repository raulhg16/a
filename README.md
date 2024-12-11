Pasos para importar un proyecto Java en Eclipse

1. Abre Eclipse
•	Ejecuta el IDE de Eclipse.
•	Si es la primera vez que lo usas, Eclipse te pedirá que selecciones una workspace (espacio de trabajo). Escoge una ubicación en tu sistema de archivos donde quieras guardar tu configuración y proyectos de Eclipse.

2. Selecciona el menú de importación
•	En la barra superior, haz clic en File > Import. Esto abrirá el asistente de importación de Eclipse.

3. Selecciona el tipo de proyecto
•	En el asistente de importación, selecciona General > Existing Projects into Workspace y haz clic en Next.

4. Selecciona la carpeta del proyecto
•	En la siguiente pantalla, haz clic en el botón Browse junto al campo Select root directory.
•	Navega hasta la carpeta que contiene tu proyecto Java y selecciona la carpeta raíz del proyecto (donde se encuentran los archivos de configuración del proyecto como src, lib, y los archivos .classpath y .project).

5. Importar el proyecto
•	Una vez que selecciones la carpeta, Eclipse debería mostrar una lista con los proyectos encontrados en esa ubicación. Asegúrate de que el proyecto que deseas importar esté seleccionado.
•	Haz clic en Finish para completar el proceso de importación.

6. Configura el JDK (si es necesario)
•	Si tu proyecto necesita una versión específica del JDK, asegúrate de configurarlo correctamente. Para hacerlo:
o	Haz clic derecho en el proyecto en el Project Explorer.
o	Selecciona Properties.
o	En el menú de propiedades, selecciona Java Build Path > Libraries.
o	Aquí puedes agregar o cambiar la versión del JDK seleccionando Add Library y luego JRE System Library.

7. Ejecuta el proyecto
•	Una vez que el proyecto esté importado, puedes ejecutarlo.
•	Si el proyecto tiene una clase con un método main, haz clic derecho en el archivo de la clase y selecciona Run As > Java Application.
Pasos para ejecutar el proyecto




-	Para el ejercicio 1, 2, 3 y 4 vas a la clase DilemaDelPrisionero y en la línea 5 puedes cambiar el numero de partidas pudiendo poner las que tu quieras y elegir los jugadores en la línea 22 y 23 puedes cambiarlos, después de eso le das a ejecutar y debería de funcionar
-	Para el ejercicio 5 vas a la clase Servidor y la ejecutas y luego vas a la clase Cliente y lo ejecutas dos veces para que empiece a funcionar

