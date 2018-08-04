Arquitectura de FrontEnd
########################

Se optó por desarrollar una Single Page Application (SPA), la cual es una aplicación o 
sitio web que interactúa con el usuario dinámicamente re-escribiendo la página actual
sin tener que descargarla por completo desde el servidor, lo cual mejora considerablemente
la experiencia de usuario (UX).

.. figure:: pictures/sprint1/spa-vs-traditional.png
  :scale: 100%
  :alt: spa-comp

  Figura X: Enfoque tradicional vs SPA
  Comparación entre ciclo de vida tradicional vs una SPA.

Para lograr el comportamiento anterior se deberá plantear una arquitectura acorde. 
A continuación se describe una posible solución a partir del Front-End

.. figure:: pictures/sprint1/arq-fe.png
  :scale: 100%
  :alt: arq-fe

  Figura X: Arquitectura Front-End.
  Se demuestra la interacción entre distintos dispositivos que componen la arquitectura del Front-End

Con esta arquitectura, el cliente y el servicio son independientes. Se podría reemplazar
el servicio de back-end por completo y no se necesitará cambiar el cliente. La reversa es también verdadera,
se puede reemplazar por completo el front-end sin tener que realizar cambios en el servicio de back-end. 
Por ejemplo, se podría escribir una aplicación móvil nativa que consuma el servicio.

Descripción de los dispositivos en el Front-End:

* Aplicación: Compuesta por páginas combinado estilos y componentes de la librería UI escogida.
La misma es la que será presentada al usuario final para su interacción.

* Páginas: Las mismas se component de un conjunto de componentes (secciones de interfaz para presentar datos)
y contenedores (secciones que manipulan datos y lógica en la aplicación). Para poder navegar entre distintas
páginas, se utilizará un component especial denominado: Router, el mismo permite manejar rutas públicas, privadas, redirecciones y errores.

* Estilos: Código que permite modificar la presentación visual de un componente determinado, ejemplo: bordes, márgenes, colores, fuentes, etc.

* Librería UI: Librería de componentes visuales seleccionada para facilitar y acelerar el proceso de desarrollo.

* Store: Para poder compartir datos entre componentes que no se relacionan directamente se necesita un store global,
para ello se puede utilizar una librerá como redux, o bien sacar provecho de la nueva API de React: Context.

* Session Storage: Un almacenamiento local dentro del navegador web en el cual se salvan datos de usuario que perduran en el tiempo hasta que la sesión termina.

* Bugsnag: Un servicio en la nube que permite recolectar errores dentro de la aplicación para su posterior corrección.

* Apollo Client: Paquete que nos permite realizar consulta sobre esqumas de datos a nuestro servicio back-end, añadiendo además características como caching y optimistic ui (forma de predecir la respuesta desde el servidor).
