Entorno de Trabajo
------------------

Gitflow
#######

Todos los miembros del equipo cuentan con un conocimiento avanzado del uso de git, este punto es
a nuestra forma de ver el desarrollo, fundamental para que el proyecto tenga éxito.

Con gitflow nos referimos al flujo de trabajo que el equipo debe seguir al utilizar git, es decir que
tipos de ramas se crearán y como estas se fusionaran entre sí. El flujo de trabajo con git más popular
fue el diseñado y publicado por Vincent Driessen[1] y es el que seguiremos en este proyecto.

**Como funciona**

En lugar de tener una sola rama *master*, este flujo de trabajo propone tener dos ramas (branches) para
guardar el historial del proyecto. La rama *master* que contendrá el historial oficial de *releases*
y la rama *develop* que nos servirá como rama de integración para las nuevas *features*. será
conveniente agregar una etiqueta (tag) a todos los cambios (commits) que se hagan en la rama
master con un número de versión.

.. figure:: pictures/entorno/git1.png
  :scale: 170%

  Figura 7: Gitflow, Rama master y develop.

Cada nueva *feature* debe tener su propia rama que puede ser enviada al repositorio central para
permitir el trabajo en equipo o simplemente de backup. Cada nueva rama del tipo *feature* debe crearse
con *develop* como rama padre. Cuando el trabajo en la rama *feature* termina esta debe volver a fusionarse con
*develop*. Las ramas de tipo *feature* no deben interactuar directamente con *master*.

.. figure:: pictures/entorno/git2.png
  :scale: 170%

  Figura 8: Gitflow, Ramas del tipo features.

Se debe tratar que, siempre que creamos una nueva rama *feature*, crearla a partir de la versión más actualizada de *develop*
y en caso de que el trabajo en la rama *feature* se extienda por demasiado tiempo, actualizarse con la rama padre
antes de crear la solicitud de *merge* (Pull Request).

Una vez que la rama *develop* tiene una cantidad suficiente de nuevas características para lanzar una nueva versión
de la aplicación, creamos una rama *release* desde *develop*. A partir de este punto no se pueden agregar nuevas *features*
a la rama *release* creada. Esta rama será probada y se podrán agregar correcciones de bugs en caso de ser necesario. Una vez
que las pruebas finalicen la rama *release* estará lista para fusionarse con *master* y agregar una etiqueta con el número
de versión.

Durante el tiempo transcurrido, la rama *develop* puede haber avanzado con respecto a la rama *release*, por lo tanto
también debemos fusionar la rama *release* de nuevo con su padre *develop*. Esta es una de las ventaja que este flujo de trabajo
ofrece, mientras parte del equipo trabaja en lanzar una nueva versión de la aplicación, el resto del equipo puede seguir
trabajando y agregando nuevas *features* a la rama *develop* para la siguiente *release*.

.. figure:: pictures/entorno/git3.png
  :scale: 170%

  Figura 9: Gitflow, Ramas del tipo releases.


Por último tenemos las ramas de tipo *hotfix* que serán utilizadas para agregar parches y correcciones de bugs que
seán urgentes en releases en producción. Este tipo de ramas son las únicas que son creadas a partir de master en lugar
de develop. Tan pronto el fix sea completado se deberá fusionar con master y develop, para que estas ramas se mantengan
actualizadas, y se deberá actualizar el número de versión con una etiqueta.

.. figure:: pictures/entorno/git4.png
  :scale: 170%

  Figura 10: Gitflow, Ramas del tipo hotfix.

Circle CI y Heroku
###################

Circle CI es una plataforma para integración continua que permite a equipos
de distintos tamaños construir y liberar rápidamente software de calidad. 
Como nuestro proyecto es open source podemos utilizar la versión gratuita,
la cual provee la integración de infinitos repositorios y una cantidad ilimitada
de usuarios.

La configuración de Circle CI es muy sencilla, sólo hace falta escribir un 
archivo `.yaml` especificando sobre qué entorno correrá la aplicación, y los pasos
que se ejecutaran para el chequeo de código, en nuestro caso tenemos en cuenta

- Instalación de paquetes
- Corroboración de tests
- Comprobación de coverage mínimo 
- Chequeo de linting (reglas de buen estilo de código)

.. figure:: pictures/entorno/circleci-heroku.png
  :scale: 80%
  :alt: Circle CI y Heroku

  Figura 11: Integración continua y deploy continuo.

1- Nuestro repositorio está hosteado en github.

2- Los cambios que se envían hacia Github despacharán un proceso sobre CircleCI
para generar una nueva colección de archivos estáticos.

3- Estos archivos serán automáticamente enviados hacia Heroku, y de esta manera
nuestro sitio estará disponible para el usuario final en cuestión de segundos.

Flujo de autenticación
######################

Hoy en día la mayoría de las aplicaciones necesitan identificar distintos tipos de usuarios.
Encontrar una manera de identificar un usuario permite a la aplicación guardar sus datos en la nube 
de forma segura y proporcionar la misma experiencia de usuario en distintos dispositivos.

La autenticación que escogimos es la que provee el service Firebase de Google. Dicha solución 
provee de servicios para backend, SDK fáciles de usar, y bibliotecas UI para el frontend, las cuales 
permiten autenticar a los usuarios en nuestra aplicación. Además ofrece distintos métodos de autenticación:

1. Por contraseña
2. Números de teléfono
3. Google
4. Facebook
5. Twitter

La autenticación en Firebase aprovecha los estándares de la industria como OAuth 2.0 y OpenID, por lo que 
se puede integrar fácilmente con un backend personalizado.

.. figure:: pictures/entorno/oauth.png
  :scale: 80%
  :alt: Circle CI y Heroku

  Figura 12: Flujo de autenticación.

1. El front configura la interfaz para que el usuario pueda ingresar al sistema, y
es el encargado de conseguir el ID de autenticación desde Firebase.

2. El backend será el encargado de verificar la autenticación del usuario, y 
retornar el la información del perfil del usuario. 

3. La aplicación almacena las credenciales de usuario en el Cloud Datastore 
utilizando la librería NDB, pero se puede escoger el almacenamiento de credenciales 
en una base a elección también.

Planificación con Planning Poker
################################

La estimación es difícil. Para los desarrolladores de software, dicha tarea está entre las más difíciles, si no es la más difícil de todas.
En un entorno de desarrollo ágil, el product manager es el encargado de priorizar los items del backlog, en una lista de trabajo 
que contenga descripciones detalladas de las features e issues para el producto. Cuando el equipo de ingeniería comienza el proceso de estimación,
las preguntas aparecen sobre los requerimientos e historias de usuario. Esto último es buena señal: aquellas preguntas ayudan a que el equipo entero 
pueda estar alineado y entender el trabajo completamente. 

Por lo tanto, incluir a todo el equipo, es decir, desarrolladores, diseñadores, testers, etc., es clave. Cada miembro del equipo traerá una perspectiva diferente 
sobre el producto y el trabajo requerido para poder finalizar una historia de usuario.

En general, los equipos de software tradicionales estiman tareas en formato de tiempo: días, semanas, meses. 
Sin embargo, los equipos de desarrollo en entornos ágiles, transicionaron hacia los story points. Estos últimos permiten 
puntuar el esfuerzo relativo de trabajo utilizando la regla de Fibonacci: 0, 1, 2, 3, 5, 8, 13, 20, etc. Ésta abstracción permite 
tomar decisiones más difíciles sobre la dificultad de trabajo.

Los equipos que comienzan con story points utilizan un ejercicio conocido como: planning poker.
El equipo tomará un item del bkaclog, lo discutirá brevemente, y cada miembro mentalmente podrá formular o estimar la cantidad de story points para una
historia en particular. Si todo el equipo está de acuerdo se prosigue con la siguiente, en el caso que no haya acuerdo, se discute y luego se puede volver a votar.

En nuestro caso utilizamos la siguiente herramienta https://www.planitpoker.com/ ya que nos permitía realizar la estimación entre miembros remotos.

El proceso es el siguiente:

1. El product owner selecciona los items del backlog para el sprint

.. figure:: pictures/entorno/poker1.png
  :scale: 80%
  :alt: Selección de items

  Figura 13: Planning poker tool.

2. El product owner inicia el proceso de votación

.. figure:: pictures/entorno/poker2.png
  :scale: 80%
  :alt: Inicio de votación

  Figura 14: Planning poker tool.

3. Los miembros del equipo proceden a votar 

.. figure:: pictures/entorno/poker3.png
  :scale: 80%
  :alt: votación

  Figura 15: Planning poker tool.

4. Se visualizan los resultados 

.. figure:: pictures/entorno/poker4.png
  :scale: 80%
  :alt: Circle CI y Heroku

  Figura 16: Planning poker tool.

Esta herramiento resulta muy útil, ya que se puede tomar fácilmente estadísticas del tiempo utilizado para votar cada una de las tareas.