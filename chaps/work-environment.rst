Entorno de Trabajo
------------------

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

2. El product owner inicia el proceso de votación

.. figure:: pictures/entorno/poker2.png
  :scale: 80%
  :alt: Inicio de votación 

3. Los miembros del equipo proceden a votar 

.. figure:: pictures/entorno/poker3.png
  :scale: 80%
  :alt: votación

4. Se visualizan los resultados 

.. figure:: pictures/entorno/poker4.png
  :scale: 80%
  :alt: Circle CI y Heroku

Esta herramiento resulta muy útil, ya que se puede tomar fácilmente estadísticas del tiempo utilizado para votar cada una de las tareas.