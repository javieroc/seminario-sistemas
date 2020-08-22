.. raw:: PDF

    PageBreak

Anexo I
-------

.. class:: user-story

+--------------------------------------------------------------------------------------------------------------+
| #5 Modificar Torneo                                                                                          |
+==============================================================================================================+
| **Descripción**: Como usuario registrado deseo poder modificar/editar un torneo particular.                  |
+--------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                 |
|                                                                                                              |
|- Desde la tabla de mis torneos deseo poder seleccionar uno para editarlo.                                    |
|- Se desea poder modificar nombre, descripción, fecha de inicio, cantidad de equipos y su estado.             |
|- Validar los campos modificados                                                                              |
|- Si el torneo se encuentra en progreso, los campos fecha de inicio y cantidad de equipos se dehabilitarán.   |
+--------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                              |
+--------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/5/editar.png
  :scale: 120%

  Figura 47: Formulario para editar torneo

.. raw:: PDF

  PageBreak


.. class:: user-story

+----------------------------------------------------------------------------------------+
| #6 Eliminación de Torneo                                                               |
+========================================================================================+
| **Descripción**: Como usuario registrado deseo poder eliminar uno de mis torneos, pero |
| dejando la posibilidad de poder recuperar la información en el futuro.                 |
+----------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                           |
|                                                                                        |
|- Desde la tabla de mis torneos deseo poder seleccionar alguno para eliminarlo          |
|- Deberá mostrarse una notificación para confirmar dicha eliminación                    |
+----------------------------------------------------------------------------------------+
| Story points: 2                                                                        |
+----------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/6/eliminar.png
  :scale: 120%

  Figura 48: Dialogo de confirmación para eliminar un torneo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-------------------------------------------------------------------------------------------+
| #7 Lista de equipos por torneo                                                            |
+===========================================================================================+
| **Descripción**: Como usuario deseo poder observar la lista de mis equipos para un torneo |
| en particular, de tal manera que me permita visualizar y  obtener                         |
| información básica de un equipo.                                                          |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
|                                                                                           |
|- Se deberá poder paginar una lista de equipos                                             |
|- Se deberá poder ordenar y buscar con filtros                                             |
+-------------------------------------------------------------------------------------------+
| Story points: 5                                                                           |
+-------------------------------------------------------------------------------------------+


.. figure:: pictures/backlog/7/lista-equipos.png
  :scale: 120%

  Figura 49: Lista de equipos para un torneo.

.. figure:: pictures/backlog/7/datos-ok.png
  :scale: 120%

  Figura 50: Equipo agregado exitosamente.

.. figure:: pictures/backlog/7/datos-error.png
  :scale: 120%

  Figura 51: Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+---------------------------------------------------------------------------------------------------------------------+
| #8 Registro de Equipo                                                                                               |
+=====================================================================================================================+
| **Descripción**: Como usuario registrado deseo poder crear un equipo.                                               |
+---------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                        |
|                                                                                                                     |
|- Luego de elegir un torneo se deberá poder clickear un botón para crear un equipo ubicado en la lista de equipos.   |
|- Se deberá ingresar la siguiente información: nombre de equipo, nombre del capitán o encargado.                     |
|- El campo nombre de equipo y del capitán son obligatorios.                                                          |
+---------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                     |
+---------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/8/agregar.png
  :scale: 120%

  Figura 52: Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-------------------------------------------------------------------------------------------------------+
| #9 Modificar un Equipo                                                                                |
+=======================================================================================================+
| **Descripción**: Como usuario registrado quiero poder modificar la información de uno de mis equipos. |
+-------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                          |
|                                                                                                       |
|- Se deberá validar cada campo modificado.                                                             |
+-------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                       |
+-------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/9/editar.png
  :scale: 120%

  Figura 53: Formulario para editar un equipo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------------------------+
| #10 Eliminar Equipo                                                                |
+====================================================================================+
| **Descripción**: Como usuario registrado quiero poder eliminar uno de mis equipos. |
+------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                       |
|                                                                                    |
|- Se deberá validar cada campo modificado.                                          |
+------------------------------------------------------------------------------------+
| Story points: 2                                                                    |
+------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/10/eliminar.png
  :scale: 120%

  Figura 54: Dialogo para confirmar la eliminación de un equipo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------------------------------------------------------------------+
| #11 Registrar jugadores para un equipo                                                                                       |
+==============================================================================================================================+
| **Descripción**: Como usuario registrado deseo poder registrar los jugadores pertenecientes a un equipo creado por mi.       |
+------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                 |
|                                                                                                                              |
|- En la vista de un equipo se desea visualizar un botón para agregar una lista de jugadores.                                  |
|- La información perteneciente a un jugador deberá ser: nombre, apellido, dni, fecha de nacimiento, teléfono, género, email   |
|- Los campos nombre, apellido, email serán obligatorios                                                                       |
|- Para facilitar el ingreso de información se requiere una lista dinámica de campos, de esta                                  |
|  manera se pueden ingresar múltiples jugadores al mismo tiempo.                                                              |
+------------------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                              |
+------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/11/agregar.png
  :scale: 120%

  Figura 55: Formulario dinámico para agregar jugadores a un equipo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+--------------------------------------------------------------------------------------------------------------------------------+
| #12 Modificar información de jugador                                                                                           |
+================================================================================================================================+
| **Descripción**: Como usuario registrado y dueño de un equipo, deseo poder modificar la información de uno o varios jugadores. |
+--------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                   |
|                                                                                                                                |
|- Se desea validar cada campo modificado                                                                                        |
|- Se deberá poder agregar información adicional de contacto, y extras de cada jugador                                           |
|- Una vez validada la información se redirije al usuario a la lista de jugadores                                                |
+--------------------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                                |
+--------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/12/editar.png
  :scale: 120%

  Figura 56: Formulario para editar un jugador.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------------------------------------------------+
| #13 Eliminar jugador de un equipo                                                                          |
+============================================================================================================+
| **Descripción**: Como usuario registrado y dueño de un equipo, deseo poder eliminar jugadores de la lista. |
+------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                               |
|                                                                                                            |
|- Se deberá confirmar la eliminación o bien proceder con una cancelación.                                   |
+------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                            |
+------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/13/eliminar.png
  :scale: 120%

  Figura 57: Dialogo de confirmación para eliminar un jugador.

.. raw:: PDF

  PageBreak


.. class:: user-story

+---------------------------------------------------------------------------------------------------------------------------+
| #14 Dockerizar aplicación                                                                                                 |
+===========================================================================================================================+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder tener el entorno dockerizado para un trabajo más ágil. |
+---------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                              |
|                                                                                                                           |
|- Levantar un servicio para la base de datos.                                                                              |
|- Levantar un servicio para el cliente web.                                                                                |
|- Levantar un servicio para la API REST                                                                                    |
+---------------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                           |
+---------------------------------------------------------------------------------------------------------------------------+


.. class:: user-story

+---------------------------------------------------------------------------------------------------------------------+
| #15 Crear estructura base de proyecto back-end                                                                      |
+=====================================================================================================================+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una estructura base para el back-end. |
+---------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                        |
|                                                                                                                     |
|- Generar boilerplate o plantilla y hacer el commit inicial para el proyecto back-end.                               |
+---------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                     |
+---------------------------------------------------------------------------------------------------------------------+


.. class:: user-story

+--------------------------------------------------------------------------------------------------------------------+
| #16 Crear estructura base de proyecto front-end                                                                    |
+====================================================================================================================+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una base de proyecto para front-end. |
+--------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                       |
|                                                                                                                    |
|- Generar en commit inicial con la estructura del proyecto front-end.                                               |
+--------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                    |
+--------------------------------------------------------------------------------------------------------------------+


.. class:: user-story

+------------------------------------------------------------------------------------------------------------------------+
| #17 Configuración integración contínua                                                                                 |
+========================================================================================================================+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una herramienta de integración contínua. |
+------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                           |
|                                                                                                                        |
|- Utilizar circle-ci, travis o jenkins.                                                                                 |
+------------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                        |
+------------------------------------------------------------------------------------------------------------------------+


.. class:: user-story

+------------------------------------------------------------------------------------------------------------+
| #18 Generar Fixture                                                                                        |
+============================================================================================================+
| **Descripción**: Como organizador de un torneo deseo poder generar un fixture para un torneo de tipo Liga. |
+------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                               |
|                                                                                                            |
|- Generar un fixture de todos contra todos de manera automática.                                            |
+------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                            |
+------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/18/vista-previa.png
  :scale: 120%

  Figura 58: Fixture vista previa.

.. figure:: pictures/backlog/18/agregar-generacion-fixture.png
  :scale: 120%

  Figura 59: Boton para generar fixture.

.. figure:: pictures/backlog/18/confirmacion.png
  :scale: 120%

  Figura 60: Dialogo para confirmar generación de fixture.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-------------------------------------------------------------------------------------------+
| #19 Crear game/match/partido                                                              |
+===========================================================================================+
| **Descripción**: Como usuario registrado y creador de un torneo, deseo  poder agregar los |
|  resultados de los partidos o enfrentamientos una vez concluidos.                         |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
|                                                                                           |
|- Crear un juego o partida con los campos date, local_score y visitor_score.               |
|- Vincular el juego con los equipos que se enfretan.                                       |
|- Asociar el partido al fixture.                                                           |
+-------------------------------------------------------------------------------------------+
| Story points: 3                                                                           |
+-------------------------------------------------------------------------------------------+


.. class:: user-story

+---------------------------------------------------------------------------------------------------------+
| #20 Ver estadísticas equipo                                                                             |
+=========================================================================================================+
| **Descripción**: Como usuario registrado deseo poder visualizar las estadísticas de uno de mis equipos. |
+---------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                            |
|                                                                                                         |
|- En una tabla se deberá reflejar información según el tipo de juego, y                                  |
|  deberé poder dirigirme a dicha página desde la tabla de equipos.                                       |
|- La primera columna en común será el nombre del jugador.                                                |
|- Para el tipo de juego fútbol la información a presentar será:                                          |
|  goles,  goles en contra, tarjetas amarillas y rojas, asistencias.                                      |
|- Debo tener la posibilidad de volver a la lista de equipos                                              |
+---------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                         |
+---------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/20/estadisticas-jugadores.png
  :scale: 120%

  Figura 61: Tabla editable para estadísticas de jugadores.

.. figure:: pictures/backlog/20/estadisticas-equipos-lista.png
  :scale: 120%

  Figura 62: Lista de equipos, boton para ver estadísticas.

.. raw:: PDF

  PageBreak


.. class:: user-story

+----------------------------------------------------------------------------------------------------------------+
| #21 Ver Estadísticas del Jugador                                                                               |
+================================================================================================================+
| **Descripción**: Como usuario registrado deseo poder ver las estadísticas de un jugador dentro de mis equipos. |
+----------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                   |
|                                                                                                                |
|- Desde la lista de jugadores dado un equipo, se deberá redirigir al usuario                                    |
|  a la página de estadísticas de jugadores.                                                                     |
|- Desde la nueva página se deberá poder regresar a la lista de jugadores.                                       |
|- La información a presentar será la relacionada al tipo de juego.                                              |
|- En el caso de que el tipo de juego sea fútbol, la información a                                               |
|  describir en gráficas será la correspondiente a: goles por partido                                            |
|  globales y por temporada, así como también las amonestaciones por temporada.                                  |
+----------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                |
+----------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/21/estadisticas-jugador.png
  :scale: 120%

  Figura 63: Estadística del Jugador.

.. figure:: pictures/backlog/21/estadisticas-jugador-lista.png
  :scale: 120%

  Figura 64: Lista de Jugadores.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-----------------------------------------------------------------------------------------------+
| #22 Agregar comentarios para un partido                                                       |
+===============================================================================================+
| **Descripción**: Como usuario deseo poder agregar comentarios a los resultados de un partido. |
+-----------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                  |
|                                                                                               |
|- Poder ingresar hasta 500 caracteres en un campo de texto.                                    |
|- Luego de ingresar el texto refrescar los comentarios para saber si han habiado               |
|  nuevos en el tiempo que se tardó el usuario en escribir el mensaje.                          |
+-----------------------------------------------------------------------------------------------+
| Story points: 2                                                                               |
+-----------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/22/partido-vista-con-comentarios.png
  :scale: 120%

  Figura 65: Agregar comentarios a un partido.

.. raw:: PDF

  PageBreak


.. class:: user-story

+--------------------------------------------------------------------------------------------------+
| #23 Habilitar mensajería entre usuarios                                                          |
+==================================================================================================+
| **Descripción**: Como usuario registrado necesito poder contactar a los usuarios del sistema.    |
+--------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                     |
|                                                                                                  |
|- Se deberá presentar un formulario detallando el nombre del contacto,                            |
|  y un campo que me permita ingresar hasta 500 caracteres.                                        |
|- Como consecuencia se deberá crear una página "bandeja de entrada" para poder                    |
|  leer los mensajes recibidos: se deberá contar con dos estados para los mensajes,                |
|  leído y no leído. Además en la misma página se agregará una sección para los mensajes enviados. |
+--------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                  |
+--------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/23/menu-usuario.png
  :scale: 120%

  Figura 66: Menu de Usuario.

.. figure:: pictures/backlog/23/mensaje-vista.png
  :scale: 120%

  Figura 67: Vista de un Mensaje recibido.

.. figure:: pictures/backlog/23/ventana-chat.png
  :scale: 120%

  Figura 68: Cuadro de dialogo para enviar un nuevo mensaje.

.. figure:: pictures/backlog/23/notificacion-nuevo-mensaje.png
  :scale: 120%

  Figura 69: Notificación de un nuevo mensaje.

.. figure:: pictures/backlog/23/bandeja-entrada-recibidos.png
  :scale: 120%

  Figura 70: Bandeja de entrada - Mensajes recibidos.

.. figure:: pictures/backlog/23/bandeja-entrada-enviados.png
  :scale: 120%

  Figura 71: Bandeja de entrada - Mensajes enviados.

.. raw:: PDF

  PageBreak


.. class:: user-story

+--------------------------------------------------------------------------------------------------+
| #24 Agregar notificaciones                                                                       |
+==================================================================================================+
| **Descripción**: Como usuario de la aplicación deseo poder recibir notificaciones en el celular. |
+--------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                     |
|                                                                                                  |
|- Se deberá poder visualizar notificaciones al estilo: push notifications.                        |
+--------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                  |
+--------------------------------------------------------------------------------------------------+


.. class:: user-story

+---------------------------------------------------------------------------------------------------------------+
| #25 Exportar fixture a excel                                                                                  |
+===============================================================================================================+
| **Descripción**: Como usuario deseo poder exportar el fixture generado a un archivo de formato excel.         |
+---------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                  |
|                                                                                                               |
|- Luego de clickear en el botón "Generar Fixture", un archivo será descargado hacia el dispositivo             |
|  del usuario en formato excel, donde se deberá volcar exactamente la misma información presente en la página. |
+---------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                               |
+---------------------------------------------------------------------------------------------------------------+


.. class:: user-story

+-----------------------------------------------------------------------------------------------------+
| #26 Generar pdf del fixture                                                                         |
+=====================================================================================================+
| **Descripción**: Como usuario deseo poder exportar el fixture generado a un archivo de formato pdf. |
+-----------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                        |
|                                                                                                     |
|- Luego de clickear en el botón "Generar Pdf", un archivo será descargado hacia el dispositivo       |
|  del usuario en formato pdf, donde se deberá volcar exactamente la misma información                |
|  presente en la página.                                                                             |
+-----------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                     |
+-----------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/25/exportar-a-excel.png
  :scale: 120%

  Figura 72: Exportar Fixture en un archivo excel.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-------------------------------------------------------------------------------------------+
| #27 Implementar sección de mis noticias                                                   |
+===========================================================================================+
| **Descripción**: Como usuario registrado y pagando un plan gold o platinum quisiera poder |
|  agregar noticias públicas de tal manera que cualquier usuario las pueda                  |
|  visualizar.                                                                              |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
|                                                                                           |
|- El usuario deberá poder acceder a un historial de las noticias publicadas.               |
|- El usuario deberá poder administrar las noticias.                                        |
+-------------------------------------------------------------------------------------------+
| Story points: 8                                                                           |
+-------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/27/mis-noticias.png
  :scale: 120%

  Figura 73: Sección de Noticias.

.. raw:: PDF

  PageBreak


.. class:: user-story

+--------------------------------------------------------------------------------------------------+
| #28 Importar nuevo equipo desde excel                                                            |
+==================================================================================================+
| **Descripción**: Como usuario deseo poder importar la lista de jugadores para un equipo.         |
+--------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                     |
|                                                                                                  |
|- A partir de un archivo excel que contiene las columnas: apellido, nombre, fecha de nacimiento,  |
|  dirección. Deseo poder importar dicho archivo al sistema.                                       |
|- Mientras el archivo se encuentra procesando deseo poder continuar navegando y recibir una       |
|  notificación cuando la carga haya finalizado, permitiendo desde aquí al usuario visualizar      |
|  la lista cargada.                                                                               |
+--------------------------------------------------------------------------------------------------+
| Story points: 5                                                                                  |
+--------------------------------------------------------------------------------------------------+


.. figure:: pictures/backlog/28/importar-equipo-1.png
  :scale: 120%

  Figura 74: Botón para importar equipo.

.. figure:: pictures/backlog/28/importar-equipo-2.png
  :scale: 120%

  Figura 75: Seleccionar archivo desde los archivos de la computadora del usuario.

.. figure:: pictures/backlog/28/importar-equipo-3.png
  :scale: 120%

  Figura 76: Procesando datos.

.. figure:: pictures/backlog/28/importar-equipo-4.png
  :scale: 120%

  Figura 77: Proceso de carga de datos finalizado.

.. raw:: PDF

  PageBreak


.. class:: user-story

+---------------------------------------------------------------------------------------------------------------------------------+
| #29 Crear página resultados de la última fecha                                                                                  |
+=================================================================================================================================+
| **Descripción**: Como usuario deseo poder acceder a una página donde se visualicen un resumen de resultados de la última fecha. |
+---------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                    |
|                                                                                                                                 |
|- Para calcular la última fecha se deberá tener en cuenta todos los partidos que se jugaron en la última semana                  |
|- Es necesario poder visualizar los equipos con sus logos con su información básica como ser:                                    |
|  nombre, director, capitán Mostrar el resultado.                                                                                |
+---------------------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                                 |
+---------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/29/resultados-ultima-fecha.png
  :scale: 120%

  Figura 78: Lista de resultados de todo el torneo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------------------------------------------------------------------------------+
| #30 Agregar una nueva noticia                                                                                                            |
+==========================================================================================================================================+
| **Descripción**: Como usuario administrador deseo poder administrar la sección de noticias teniendo la posibilidad de agregar una nueva. |
+------------------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                             |
|                                                                                                                                          |
|- A través de una interfaz deseo poder cargar contenido que le podría resultar interesante al público.                                    |
|  Ejemplo: eventos atractivos, un posible enfrentamiento apasionante, promociones en el establecimiento, etc.                             |
|- Se deberá poder cargar la siguiente información: Título  - Foto principal - Contenido.                                                  |
|- Se deberá poder volver a la lista de notificas luego de la carga exitosa.                                                               |
+------------------------------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                                          |
+------------------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/30/add.png
  :scale: 120%

  Figura 79: Crear una nueva noticia.

.. raw:: PDF

  PageBreak


.. class:: user-story

+----------------------------------------------------------------------------------------------------------------------+
| #31 Calificar noticia                                                                                                |
+======================================================================================================================+
| **Descripción**: Como usuario deseo poder votar una noticia.                                                         |
+----------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                         |
|                                                                                                                      |
|- Una interfaz sencilla donde se visualice un pulgar hacia arriba,                                                    |
|  otro hacia abajo (ambo clickeables para sumar o restar un voto respectivamente) y la cantidad de votos actualmente. |
|- El usuario no tiene limite de comentarios.                                                                          |
|- Por el momento no se podrán crear hilos de conversación.                                                            |
+----------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                      |
+----------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/31/comentario-noticia.png
  :scale: 120%

  Figura 80: Agregar comentarios y votar una notica.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------+
| #32 Crear página para lista de torneos públicos                  |
+==================================================================+
| **Descripción**: Como usuario deseo poder buscar un torneo.      |
+------------------------------------------------------------------+
| **Criterios de aceptación:**                                     |
|                                                                  |
|- El usuario deberera poder ver la lista de torneos disponibles.  |
|- Se deberá poder filtrar la lista de torneos a través de texto.  |
+------------------------------------------------------------------+
| Story points: 2                                                  |
+------------------------------------------------------------------+

.. figure:: pictures/backlog/32/torneos-publico.png
  :scale: 120%

  Figura 81: Lista de torneos públicos.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-------------------------------------------------------------------------------------------+
| #33 Crear página para torneo                                                              |
+===========================================================================================+
| **Descripción**: Como usuario, luego de proceder con la búsqueda de torneos, deseo poder  |
| acceder a la información que respecta a un torneo. Dicha página estará                    |
| disponible en forma pública, de tal manera que los usuarios no                            |
| registrados también puedan ingresar.                                                      |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
|                                                                                           |
|- Resumen: Torneos que se jugaron en la última fecha.                                      |
|- Registración: Si soy un usuario registrado, debería poder accerder a un formulario para  |
|  registrar instantáneamente un nuevo equipo. En el caso de no ser un usuario registrado   |
|  esta pestaña permanecerá no visible.                                                     |
|- Estadísticas de equipos                                                                  |
|- Sección de fotos                                                                         |
|- Información del torneo                                                                   |
+-------------------------------------------------------------------------------------------+
| Story points: 8                                                                           |
+-------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/33/contactar-capitan.png
  :scale: 120%

  Figura 82: Cuadro de dialogo para enviar notificacion al capitán de un equipo.

.. figure:: pictures/backlog/33/estadisticas-torneo.png
  :scale: 120%

  Figura 83: Tabla general del torneo.

.. figure:: pictures/backlog/33/informacion-torneo.png
  :scale: 120%

  Figura 84: Pestaña con la información del torneo.

.. figure:: pictures/backlog/33/lista-de-equipos.png
  :scale: 120%

  Figura 85: Lista de equipos participantes del torneo.

.. figure:: pictures/backlog/33/registro-instantaneo.png
  :scale: 120%

  Figura 86: Formulario para registrar un nuevo equipo al torneo.

.. figure:: pictures/backlog/33/resumen-fecha.png
  :scale: 120%

  Figura 87: Resultados de la última fecha jugada.

.. figure:: pictures/backlog/33/seccion-fotos.png
  :scale: 120%

  Figura 88: Fotos del torneo.

.. raw:: PDF

  PageBreak


.. class:: user-story

+---------------------------------------------------------------------------------------------------+
| #34 Administrar estado de torneo                                                                  |
+===================================================================================================+
| **Descripción:** Como usuario registrado deseo tener la posibilidad de dar inicio a un torneo.    |
+---------------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                      |
|                                                                                                   |
|- Añadir un botón en la tabla de la lista de torneos para poder dar inicio a un torneo.            |
|- Cuando un torneo se encuentra en proceso, el botón deberá permitir cambiar el estado del mismo.  |
+---------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                   |
+---------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/34/torneo-estados.png
  :scale: 120%

  Figura 89: Estados por los cuales puede pasar un Torneo.

.. figure:: pictures/backlog/34/administrar-estados.png
  :scale: 120%

  Figura 90: Tabla con la lista de torneos.

.. figure:: pictures/backlog/34/iniciar-confirmar.png
  :scale: 120%

  Figura 91: Cuadro de dialogo para iniciar un torneo.

.. figure:: pictures/backlog/34/nuevo-estado.png
  :scale: 120%

  Figura 92: Cuadro de dialogo para cambiar el estado de un torneo iniciado.

.. raw:: PDF

  PageBreak


.. class:: user-story

+----------------------------------------------------------------------------------------------------------------+
| #35 Ver una Noticia                                                                                            |
+================================================================================================================+
| **Descripción:** Como usuario registrado deseo poder ver una noticia en detalle.                               |
+----------------------------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                                   |
|                                                                                                                |
|- Desde la lista de mis noticias se deberá poder acceder a cada uno para su visualización en una nueva página.  |
|- La nueva página mostrará el contenido publicado, como así también los comentarios.                            |
+----------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                |
+----------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/35/vista-noticia.png
  :scale: 120%

  Figura 93: Vista de una noticia.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-----------------------------------------------------------------------------------------------+
| #36 Ocultar una noticia                                                                       |
+===============================================================================================+
| **Descripción:** Como usuario registrado deseo poder ocultar una de mis noticias.             |
+-----------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                  |
|                                                                                               |
|- Desde la vista de la publicación deseo poder acceder a una opción para ocultar una noticia,  |
|  de esta manera los usuario ya no tendrán acceso para su visualización.                       |
|- Luego de ocultar la noticia el usuario es redirigido a la lista de noticias.                 |
|- Luego de ocultar la noticia debería poder publicarla nuevamente en caso necesario.           |
+-----------------------------------------------------------------------------------------------+
| Story points: 1                                                                               |
+-----------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/36/publicar.png
  :scale: 120%

  Figura 94: Botón para publicar una noticia.

.. figure:: pictures/backlog/36/ocultar-noticia.png
  :scale: 120%

  Figura 95: Botón para ocultar una noticia.

.. raw:: PDF

  PageBreak


.. class:: user-story

+-----------------------------------------------------------------------------------------------------+
| #37 Censurar comentarios                                                                            |
+=====================================================================================================+
| **Descripción:** Como usuario registrado deseo poder censurar comentarios en una noticia publicada. |
+-----------------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                        |
|                                                                                                     |
|- A través de un botón quisiera poder censurar un comentario por parte de un usuario.                |
|- No se necesitará confirmación.                                                                     |
|- En el futuro se deberá poder agregar un posible motivo de censura,                                 |
|  pero esto último no es un bloqueante para continuar por el momento.                                |
+-----------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                     |
+-----------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/37/censurar.png
  :scale: 120%

  Figura 96: Botón para censurar un comentario.

.. figure:: pictures/backlog/37/censurado.png
  :scale: 120%

  Figura 97: Comentario censurado.

.. raw:: PDF

  PageBreak


.. class:: user-story

+------------------------------------------------------------------------------------------------------------------+
| #38 Pagina perfil de usuario                                                                                     |
+==================================================================================================================+
| **Descripción:** Como usuario registrado quisiera poder visualizar la información básica de otro usuario.        |
+------------------------------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                                     |
|                                                                                                                  |
|- Se debe crear una página no pública                                                                             |
|- Se deberá mostrar un avatar, nombre y apellido, así como también permitirá el contacto directo con el usuario.  |
+------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                  |
+------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/38/perfil-usuario.png
  :scale: 120%

  Figura 98: Pantalla de perfil de usuario.

.. raw:: PDF

  PageBreak


.. class:: user-story

+---------------------------------------------------------------------------------------------+
| #39 Ver un resultado de un juego                                                            |
+=============================================================================================+
| **Descripción:** Como usuario quisiera poder visualizar un partido de la última fecha.      |
+---------------------------------------------------------------------------------------------+
| **Criterios de Aceptación:**                                                                |
|                                                                                             |
|- A traves de la lista de partidos jugados en la última fecha,                               |
|   el usuario deberá poder clickear una fila para poder observer los detalles de un partido. |
+---------------------------------------------------------------------------------------------+
| Story points: 1                                                                             |
+---------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/39/resultado-partido.png
  :scale: 120%

  Figura 99: Resultado de un Juego.

.. raw:: PDF

  PageBreak
