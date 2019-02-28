# Punto de Inicio

- [Curso introductorio a Git y GitHub](https://github.com/oscarperpinan/intro_github/raw/master/intro_github.pdf)
- **NUEVO** [Instrucciones para crear los equipos del trabajo](https://github.com/aigora/punto_inicio/wiki/C%C3%B3mo-comenzar-con-el-trabajo-en-grupo-en-GitHub)

## Primer paso: Cómo utilizar github desde la web. 
 Acceso web
(https://github.com/)
 
Una vez accedéis al enlace, os registráis pulsando el botón de Sign Up.
Una vez hecho esto, accedéis a moodle y realizáis el registro accediendo al link hacia github classroom. 
Esto os va a permitir vincular vuestra cuenta institucional con el grupo de Github que existe para la asignatura. _Estos pasos sólo debéis realizarlos la primera vez._ 

Ahora crearemos un repositorio propio, que funciona de forma similar a los repositorios creados por otros controles de versiones (igual que drive o dropbox tienen el suyo). 
Para esto, debéis acceder a vuestro perfil, clicando en la esquina superior derecha.

Desde allí podéis acceder a la pestaña repositorios y pulsar en "nuevo".
Una vez hecho esto, podréis darle un nombre al proyecto y una breve descripción sobre el mismo.

Debéis asimismo seleccionar crear un README.md en el repositorio. En él debeis hacer una descripción general del proyecto (sin incluir explicaciones de código) 

También debéis seleccionar Público por defecto, ya que os facilitará compartir vuestros proyectos y archivos.

No obstante, no subáis a este repositorio información sensible. Recordad que todo lo publicado allí es accesible para todo el mundo.

Después debéis elegir entre licencias y gitignore.

- Las licencias son las "políticas" que vais a elegir a la hora de proteger y compartir vuestro proyecto, de momento basta con elegir una licencia GNU v3.0.
- El .gitignore es un archivo en el que váis a decirle que archivos no queréis subir a git. Por ejemplo, hay archivos que pueden serte útiles a ti, pero no al resto de la comunidad a la que vas a compartir (archivos temporales, hojas de texto con plannings, etc). Podéis editarlo más tarde así que no es algo crítico.

- Una vez habéis creado vuestro propio repositorio, podéis subir al mismo un archivo. 
      - Para ello, acceded a vuestro repositorio, y clicar en crear/subir un archivo.
      - Una vez habéis añadido el archivo, debéis seleccionar el título del commit, en el que resumiréis los cambios efectuados en una                sola frase.
      - Más abajo, podréis detallar los cambios efectuados en el commit.
      - Ahora debéis clicar en el commit para subir vuestros cambios al repositorio remoto
      - Una vez hecho, revisad vuestro repositorio y comprobad que los cambios se han efectuado correctamente.

> Recordad que un commit consiste en tomar una "foto" del estado de vuestro repositorio en un momento determinado, y queda registrada la fecha del commit y el usuario que lo ha realizado.

Una vez hecho esto, ¡estáis listos para empezar a participar en el proyecto de clase!
Para ello debéis acceder al repositorio [AIGORA](https://github.com/aigora)

Una vez allí, seleccionad un repositorio y, ¡listo!. Allí podéis compartir y subir ficheros de la forma que habéis aprendido.


Puntos básicos antes de realizar un cambio en AIGORA
--
1. Desde tu copia local, modifica el nombre del .c que vas a subir poniéndole un nombre que identifique su contenido. Para tener un criterio uniforme:
      - No utilices ni puntos ni espacios.
      - Cuando cambies de palabra comienza por mayúscula o emplea guión bajo. Por ejemplo,
      
      CambioBinarioDecimal.c 
          
      cambio_binario_decimal.c
      
2. En la cabecera del archivo .c escribe tu nombre, el grupo al que perteneces y una breve descripción que detalle el objetivo del programa que has realizado.
    Plantilla:
    ``` 
    /* Autor:
        Grupo:
        Descripción:*/
     ```
  Esta cabecera debe ponerse antes de los `#include`.

3. _Este paso sólo debes emplearlo de forma temporal, hasta que domines el uso de GitHub Desktop_. Sitúate en el repositorio al que debas subir el código dentro del proyecto AIGORA, haz clic en el botón Upload Files y arrastra el .c a la pantalla.

**IMPORTANTE: De un proyecto sólo se suben los ficheros .c, nunca los ejecutables .exe**

4. Realiza el commit. Completa la descripción del commit con los cambios realizados o con una breve descripción del contenido del archivo si lo has subido por primera vez.

5. IMPORTANTE: Hay que realizar todos los cambios en la rama master. Es decir, no se debe cambiar la configuración del commit. 

6. Comprueba que se han realizado los cambios.


  
