Backlog
--------

+------------------------------------------------------------------------------+
| #1 Registro de Usuario.                                                      |
+------------------------------------------------------------------------------+
| **Descripción:** como usuario quiero poder registrarme en el sistema.        |
+------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                 |
| 1. Ingresar nombre y apellido.                                               |
| 2. Ingresar fecha de nacimiento.                                             |
| 3. Ingrear Email.                                                            |
| 4. Ingresar password.                                                        |
| 5. Ingresar password confirmation.                                           |
| 6. Validación de todos los campos anteriores.                                |
+------------------------------------------------------------------------------+
| Story points: 5                                                              |
+------------------------------------------------------------------------------+

.. figure:: pictures/backlog/1/exito.png
  :scale: 80%

  Registro exitoso.

.. figure:: pictures/backlog/1/step-1.png
  :scale: 80%

  Formulario de registro.

.. figure:: pictures/backlog/1/step-2.png
  :scale: 80%

  Billing: elegir plan.

.. raw:: PDF

  PageBreak

+----------------------------------------------------------------------------+
| #2 Ingreso al sistema.                                                     |
+----------------------------------------------------------------------------+
| **Descripción:** Como usuario registrado deseo poder ingresar al sistema.  |
+----------------------------------------------------------------------------+
| **Criterios de aceptación:**                                               |
| 1. Ingresar email y password.                                              |
| 2. Validar email y password.                                               |
| 3. Luego de ingresar se redirecciona al usuario a la página principal.     |
| 4. Mantener la sesión por 1 semana aunque la aplicación se cierre.         |
+----------------------------------------------------------------------------+
| Story points: 5                                                            |
+----------------------------------------------------------------------------+

.. figure:: pictures/backlog/2/login.png
  :scale: 80%

  Formulario de ingreso al sistema.

.. raw:: PDF

  PageBreak

+-----------------------------------------------------------------------------------------------------------------------+
| #3 Registo de torneos.                                                                                                |
+-----------------------------------------------------------------------------------------------------------------------+
| **Descripción:** Como usuario registrado deseo poder crear un torneo.                                                 |
+-----------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                          |
| 1. Se deben ingresar los campos: nombre de torneo, descripción, fecha de inicio, cantidad de equipos                  |
| 2. Los campos nombre, cantidad de equipos y fecha de inicio son obligatorios.                                         |
| 3. La cantidad mínima de equipos es de 2                                                                              |
| 4. Luego de registrar el torneo exitosamente se redirecciona al usuario a la lista de torneos                         |
| 5. El torneo deberá tener un estado inicial: "creado". Más adelante se definiran los posibles cambios de estados.     |
+-----------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                       |
+-----------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/3/agregar.png
  :scale: 80%

  Formulario para crear un nuevo torneo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------------+
| #4 Lista de Torneos                                                                             |
+-------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder visualizar mi lista de torneos             |
| de tal manera que pueda acceder fácilmente a la información de un torneo enparticular.          |
+-------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                    |
| 1. Mostrar una tabla con nombre fecha de inicio, descripción, cantidad de equipos, y su estado. |
| 2. Se desea poder utilizar paginado.                                                            |
| 3. Se desea poder ordenar por nombre y por fecha.                                               |
| 4. Se desea poder buscar un torneo a traves de un campo de texto1.                              |
+-------------------------------------------------------------------------------------------------+
| Story points: 5                                                                                 |
+-------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/4/lista.png
  :scale: 80%

  Lista de torneos.

.. figure:: pictures/backlog/4/datos-ok.png
  :scale: 80%

  Se agrego exitosamente un nuevo torneo.

.. figure:: pictures/backlog/4/datos-error.png
  :scale: 80%

  No se pudo agregar un nuevo torneo

.. raw:: PDF

  PageBreak

+--------------------------------------------------------------------------------------------------------------+
| #5 Modificar Torneo                                                                                          |
+--------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder modificar/editar un torneo particular.                  |
+--------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                 |
| 1. Desde la tabla de mis torneos deseo poder seleccionar uno para editarlo.                                  |
| 2. Se desea poder modificar nombre, descripción, fecha de inicio, cantidad de equipos y su estado.           |
| 3. Validar los campos modificados                                                                            |
| 4. Si el torneo se encuentra en progreso, los campos fecha de inicio y cantidad de equipos se dehabilitarán. |
+--------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                              |
+--------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/5/editar.png
  :scale: 80%

  Formulario para editar torneo

.. raw:: PDF

  PageBreak

+----------------------------------------------------------------------------------------+
| #6 Eliminación de Torneo                                                               |
+----------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder eliminar uno de mis torneos, pero |
| dejando la posibilidad de poder recuperar la información en el futuro.                 |
+----------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                           |
| 1. Desde la tabla de mis torneos deseo poder seleccionar alguno para eliminarlo        |
| 2. Deberá mostrarse una notificación para confirmar dicha eliminación                  |
+----------------------------------------------------------------------------------------+
| Story points: 2                                                                        |
+----------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/6/eliminar.png
  :scale: 80%

  Dialogo de confirmación para eliminar un torneo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------+
| #7 Lista de equipos por torneo.                                                           |
+-------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario deseo poder observar la lista de mis equipos para un torneo |
| en particular, de tal manera que me permita visualizar y  obtener                         |
| información básica de un equipo.                                                          |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
| 1. Se deberá poder paginar una lista de equipos                                           |
| 2. Se deberá poder ordenar y buscar con filtros                                           |
+-------------------------------------------------------------------------------------------+
| Story points: 5                                                                           |
+-------------------------------------------------------------------------------------------+


.. figure:: pictures/backlog/7/lista-equipos.png
  :scale: 80%

  Lista de equipos para un torneo.

.. figure:: pictures/backlog/7/datos-ok.png
  :scale: 80%

  Equipo agregado exitosamente.

.. figure:: pictures/backlog/7/datos-error.png
  :scale: 80%

  Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak

+---------------------------------------------------------------------------------------------------------------------+
| #8 Registro de Equipo                                                                                               |
+---------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder crear un equipo.                                               |
+---------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                        |
| 1. Luego de elegir un torneo se deberá poder clickear un botón para crear un equipo ubicado en la lista de equipos. |
| 2. Se deberá ingresar la siguiente información: nombre de equipo, nombre del capitán o encargado.                   |
| 3. El campo nombre de equipo y del capitán son obligatorios.                                                        |
+---------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                     |
+---------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/8/agregar.png
  :scale: 80%

  Error al agregar un nuevo equipo.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------------------+
| #9 Modificar un Equipo                                                                                |
+-------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado quiero poder modificar la información de uno de mis equipos. |
+-------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                          |
| 1. Se deberá validar cada campo modificado.                                                           |
+-------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                       |
+-------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/9/editar.png
  :scale: 80%

  Formulario para editar un equipo.

.. raw:: PDF

  PageBreak

+------------------------------------------------------------------------------------+
| #10 Eliminar Equipo                                                                |
+------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado quiero poder eliminar uno de mis equipos. |
+------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                       |
| 1. Se deberá validar cada campo modificado.                                        |
+------------------------------------------------------------------------------------+
| Story points: 2                                                                    |
+------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/10/eliminar.png
  :scale: 80%

  Dialogo para confirmar la eliminación de un equipo.

.. raw:: PDF

  PageBreak

+------------------------------------------------------------------------------------------------------------------------------+
| #11 Registrar jugadores para un equipo                                                                                       |
+------------------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder registrar los jugadores pertenecientes a un equipo creado por mi.       |
+------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                 |
| 1. En la vista de un equipo se desea visualizar un botón para agregar una lista de jugadores.                                |
| 2. La información perteneciente a un jugador deberá ser: nombre, apellido, dni, fecha de nacimiento, teléfono, género, email |
| 3. Los campos nombre, apellido, email serán obligatorios                                                                     |
| 4. Para facilitar el ingreso de información se requiere una lista dinámica de campos, de esta                                |
| manera se pueden ingresar múltiples jugadores al mismo tiempo.                                                               |
+------------------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                              |
+------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/11/agregar.png
  :scale: 80%

  Formulario dinámico para agregar jugadores a un equipo.

.. raw:: PDF

  PageBreak

+--------------------------------------------------------------------------------------------------------------------------------+
| #12 Modificar información de jugador                                                                                           |
+--------------------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado y dueño de un equipo, deseo poder modificar la información de uno o varios jugadores. |
+--------------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                                   |
| 1. Se desea validar cada campo modificado                                                                                      |
| 2. Se deberá poder agregar información adicional de contacto, y extras de cada jugador                                         |
| 3. Una vez validada la información se redirije al usuario a la lista de jugadores                                              |
+--------------------------------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                                                |
+--------------------------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/12/editar.png
  :scale: 80%

  Formulario para editar un jugador.

.. raw:: PDF

  PageBreak

+------------------------------------------------------------------------------------------------------------+
| #13 Eliminar jugador de un equipo.                                                                         |
+------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado y dueño de un equipo, deseo poder eliminar jugadores de la lista. |
+------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                               |
| 1. Se deberá confirmar la eliminación o bien proceder con una cancelación.                                 |
+------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                            |
+------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/13/eliminar.png
  :scale: 80%

  Dialogo de confirmación para eliminar un jugador.

.. raw:: PDF

  PageBreak

+---------------------------------------------------------------------------------------------------------------------------+
| #14 Dockerizar aplicación.                                                                                                |
+---------------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder tener el entorno dockerizado para un trabajo más ágil. |
+---------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                              |
| 1. Levantar un servicio para la base de datos.                                                                            |
| 2. Levantar un servicio para el cliente web.                                                                              |
| 3. Levantar un servicio para la API REST                                                                                  |
+---------------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                           |
+---------------------------------------------------------------------------------------------------------------------------+

+---------------------------------------------------------------------------------------------------------------------+
| #15 Crear estructura base de proyecto back-end.                                                                     |
+---------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una estructura base para el back-end. |
+---------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                        |
| 1. Generar boilerplate o plantilla y hacer el commit inicial para el proyecto back-end.                             |
+---------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                     |
+---------------------------------------------------------------------------------------------------------------------+

+--------------------------------------------------------------------------------------------------------------------+
| #16 Crear estructura base de proyecto front-end.                                                                   |
+--------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una base de proyecto para front-end. |
+--------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                       |
| 1. Generar en commit inicial con la estructura del proyecto front-end.                                             |
+--------------------------------------------------------------------------------------------------------------------+
| Story points: 1                                                                                                    |
+--------------------------------------------------------------------------------------------------------------------+

+------------------------------------------------------------------------------------------------------------------------+
| #17 Configuración integración contínua.                                                                                |
+------------------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como miembro del equipo de desarrollo deseo poder contar con una herramienta de integración contínua. |
+------------------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                                           |
| 1. Utilizar circle-ci, travis o jenkins.                                                                               |
+------------------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                                        |
+------------------------------------------------------------------------------------------------------------------------+

+------------------------------------------------------------------------------------------------------------+
| #18 Generar Fixture.                                                                                       |
+------------------------------------------------------------------------------------------------------------+
| **Descripción**: Como organizador de un torneo deseo poder generar un fixture para un torneo de tipo Liga. |
+------------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                               |
| 1. Generar un fixture de todos contra todos de manera automática.                                          |
+------------------------------------------------------------------------------------------------------------+
| Story points: 3                                                                                            |
+------------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/18/vista-previa.png
  :scale: 80%

  Fixture vista previa.

.. figure:: pictures/backlog/18/agregar-generacion-fixture.png
  :scale: 80%

  Boton para generar fixture.

.. figure:: pictures/backlog/18/confirmacion.png
  :scale: 80%

  Dialogo para confirmar generación de fixture.

.. raw:: PDF

  PageBreak

+-------------------------------------------------------------------------------------------+
| #19 Crear game/match/partido.                                                             |
+-------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado y creador de un torneo, deseo  poder agregar los |
|  resultados de los partidos o enfrentamientos una vez concluidos.                         |
+-------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                              |
| 1. Crear un juego o partida con los campos date, local_score y visitor_score.             |
| 2. Vincular el juego con los equipos que se enfretan.                                     |
| 3. Asociar el partido al fixture.                                                         |
+-------------------------------------------------------------------------------------------+
| Story points: 3                                                                           |
+-------------------------------------------------------------------------------------------+


+---------------------------------------------------------------------------------------------------------+
| #20 Ver estadísticas equipo.                                                                            |
+---------------------------------------------------------------------------------------------------------+
| **Descripción**: Como usuario registrado deseo poder visualizar las estadísticas de uno de mis equipos. |
+---------------------------------------------------------------------------------------------------------+
| **Criterios de aceptación:**                                                                            |
| 1. En una tabla se deberá reflejar información según el tipo de juego, y                                |
| deberé poder dirigirme a dicha página desde la tabla de equipos.                                        |
| 2. La primera columna en común será el nombre del jugador.                                              |
| 3. Para el tipo de juego fútbol la información a presentar será:                                        |
| goles,  goles en contra, tarjetas amarillas y rojas, asistencias.                                       |
| 4. Debo tener la posibilidad de volver a la lista de equipos                                            |
+---------------------------------------------------------------------------------------------------------+
| Story points: 2                                                                                         |
+---------------------------------------------------------------------------------------------------------+

.. figure:: pictures/backlog/20/estadisticas-jugadores.png
  :scale: 80%

  Tabla editable para estadísticas de jugadores.

.. figure:: pictures/backlog/20/estadisticas-equipos-lista.png
  :scale: 80%

  Lista de equipos, boton para ver estadísticas.

.. raw:: PDF

  PageBreak





